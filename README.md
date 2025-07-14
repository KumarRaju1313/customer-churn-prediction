**Data**  

The dataset used in this project is provided in the data directory. It includes customer demographics, account information, and services availed by the customers. Some columns include:  

Gender,  
SeniorCitizen,    
Partner,   
Dependents,  
tenure,  
PhoneService,  
MultipleLines,  
InternetService,  
OnlineSecurity,  
OnlineBackup,  
DeviceProtection,  
TechSupport,  
StreamingTV,  
StreamingMovies,  
Contract,  
PaperlessBilling,  
PaymentMethod,  
MonthlyCharges,  
TotalCharges,  
Churn,  

Missing values in TotalCharges have been handled by replacing them with the median value.  

**Methodology**  
  
Data Preprocessing:  

Handle missing values.  
Convert categorical variables to numerical using one-hot encoding.  
Standardize numerical variables.  

Model Training:  

Train various machine learning models, including KNN, Logistic Regression, SVM, Decision Tree, and Random Forest.  

Model Evaluation:  
  
Evaluate the models using accuracy as the metric.  

**Results**  

The accuracy of the different models on the test set are as follows:  

KNN achieved an accuracy of 74.7%  
Logistic Regression achieved an accuracy of 79.1%  
Support Vector Machines achieved an accuracy of 78.4%  
Decision Trees achieved an accuracy of 71.5%  
Random Forest achieved an accuracy of 76.3%  

The algorithm with the highest accuracy is "Logistic Regression" with an accuracy of 79.1%. Therefore, for churn prediction based on the provided data and model evaluation, Logistic Regression is the recommended choice.
