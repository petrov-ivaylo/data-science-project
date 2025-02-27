# data-science-project

The project consists of 10 files where the "Data_Science_Project.ipynb" is the main one. The five .csv files represent the data, where the .pdf document includes information about the different attributes every data table has.

Aims and objectives

The main aim of the current project is to provide two prediction (classification) techniques in help of an insurance company such that the company minimises their loss from either losing clients because of misclassifying claims as being a fraud or from incorrectly marking a claim as genuine while it being a fraud. In order to do that the insurance company's historic insurance fraud dataset is used. The data is analysed and preprocessed before the two chosen classifiers are applied. The two techniques are optimised and their performances are compared to each other. Additionally, it is calculated which one of the classification models would lead to more financial loss for the company. Finally, based on all the comparisons, one of the classification models is recommended to the insurance company.

Case study analysis

Based on the provided context, some key points should be addressed.

1. The project is going to be based on the historic data of the insurance company which probably represents medium to large amount of records. Having big real data, this might mean dealing with numerous data problems. For example, the raw data may suffer from missing values, outliers, attributes correlations and others. Hence, the data should be thoroughly explored and suitable data preprocessing techniques might need to be implemented in order to prepare the dataset for further analyses.

2. The data should also be checked for class imbalance as it might lower the performaces of the classification techniques. The current project deals with a binary classification problem as there are two classes - "fraud" and "not fraud". If either of them is represented way more than the other, this might make a classification approach to prioritise the majority class and ignore the minority class. Hence, if there is a problem with a class imbalance, it should be resolved. For example, oversampling of the minority class and/or undersampling of the majority class may be done.

3. One of the main goals of the project is to present two classification techniques and by comparing them to propose one of them as the better option. In order to do that, suitable performance metrics should be applied. For example, the recall metrics should probably be used because it is a lot more important to minimise the cases where the model predicts a genuine claim while it is a fraud in reality as this would probably lead to more financial loss for the insurance company. Additionally, it should be made sure that the classifiers are compared in an unbiased way. So, a method such as the nested cross validation should be used, for example.

4. Finally, it should be shown to the insurance company which of the two classification techniques would lead to less financial loss for them. In order to do that an example pricing model should be constructed. It should be taken into consideration that misclassifying a fraudulent claim as genuine would most probably lead to a bigger loss compared to loosing a client for misclassifying a genuine claim. Hence, it is not guaranteed that the algorithm which has shown better performance metrics is the one which would lead to less financial loss for the company, as well.
