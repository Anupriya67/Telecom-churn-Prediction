# Telecom-churn-Prediction
Data Overview: 
The dataset contains information such as account length, service plans (International/VMail), call minutes, customer service calls (as an indicator of dissatisfaction), and churn (the target variable).  Features like daily, evening, night, and international call durations and charges were present, along with demographic features like state and area code.
Business Case:
No-Churn Telecom is an established Telecom operator in Europe with more than a decade in Business. Due to new players in the market, telecom industry has become very competitive and retaining customers becoming a challenge.
In spite of No-Churn initiatives of reducing tariffs and promoting more offers, the churn rate ( percentage of customers migrating to competitors) is well above 10%.  No-Churn wants to explore possibility of Machine Learning to help with following use cases to retain competitive edge in the industry.

PROJECT GOAL:
Understanding the variables that are influencing the customers to migrate.
Creating Churn risk scores that can be indicative to drive retention campaigns.
Introduce new predicting variable “CHURN-FLAG” with values YES(1) or NO(0) so that email campaigns with lucrative offers can be targeted to Churn YES customers.
Data Preprocessing: 
Data Cleaning: Handling missing values by filling, imputing, or removing them. Removing duplicates and correcting errors in the data.
Data Transformation: Normalizing or scaling numerical features to bring them into a comparable range. Encoding categorical variables using techniques like one-hot encoding or label encoding. 
Feature Engineering:Call minutes were converted to hours.New features such as total daily calls and charges per hour were created.
Handling Outliers:Outliers were detected and replaced with mean values using IQR. 
Imbalanced Data:The dataset was imbalanced, with more non-churn cases than churn cases.SMOTE (Synthetic Minority Oversampling Technique) was used to balance the target variable.

Exploratory Data Analysis:Univariate and bivariate analyses were conducted using histograms, scatter plots, and heatmaps.

Key Findings:International calls were slightly skewed.High charges during the day compared to the evening and night might indicate a potential reason for churn. Customer service call frequency strongly correlates with churn.Certain states showed higher churn rates.

Modeling and Evaluation:
Several machine learning models were tested, and their performance was evaluated using accuracy, confusion matrix, and ROC-AUC scores.
