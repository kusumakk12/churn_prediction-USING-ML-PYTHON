# churn_prediction-USING-ML-PYTHON
Churn prediction is a common use case in machine learning domain. If you are not familiar with the term, churn means “leaving the company”. It is very critical for a business to have an idea about why and when customers are likely to churn. Having a robust and accurate churn prediction model helps businesses to take actions to prevent customers from leaving the company.
In this project, I used “Telco Customer Churn” dataset which is available on Kaggle.
data source:https://www.kaggle.com/code/bandiatindra/telecom-churn-prediction
There are 20 features (independent variables) and 1 target (dependent) variable for 7043 customers. Target variable indicates if a customer has left the company (i.e. churn=yes) within the last month. Since the target variable has two states (yes/no or 1/0), this is a binary classification problem.

The variables are: 'customerID', 'gender', 'SeniorCitizen', 'Partner', 'Dependents', 'tenure', 'PhoneService', 'MultipleLines', 'InternetService', 'OnlineSecurity', 'OnlineBackup', 'DeviceProtection', 'TechSupport', 'StreamingTV', 'StreamingMovies', 'Contract', 'PaperlessBilling', 'PaymentMethod', 'MonthlyCharges', 'TotalCharges', 'Churn'.
 Outliers Analysis with IQR Method.
#work flow:
    1.importing libraries
    2.processing data using exploratory data analysis.
    3.visualization of data using graphs.
    4.Outliers Analysis with IQR Method.
    5.On Hot Encoding and feature selection.
    6.model training using various algorithms:
        a. Logistic Regression
        b.Decision Tree Classifier
        c.Support Vector Classifier
        d.random forest model
        and respective heatmaps ,confusion matrix,classification_report.
    7.opted the model with best accuracy(my case:LOGISTIC_REGRESSION)

    
