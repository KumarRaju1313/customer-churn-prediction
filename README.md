# 🔄 Customer Churn Prediction

This project predicts whether a customer is likely to churn (discontinue service) based on their demographics, account details, and service usage patterns using various machine learning algorithms.

---

## 📁 Dataset

The dataset includes information about telecom customers and whether they have churned. Key columns include:

- Gender  
- SeniorCitizen  
- Partner  
- Dependents  
- Tenure  
- PhoneService  
- MultipleLines  
- InternetService  
- OnlineSecurity  
- OnlineBackup  
- DeviceProtection  
- TechSupport  
- StreamingTV  
- StreamingMovies  
- Contract  
- PaperlessBilling  
- PaymentMethod  
- MonthlyCharges  
- TotalCharges  
- **Churn** (Target)

🧹 **Note:** Missing values in the `TotalCharges` column were handled by replacing them with the **median value**.

---

## 🧰 Methodology

### 🔧 Data Preprocessing
- Handle missing values.
- Apply one-hot encoding to categorical variables.
- Standardize numerical columns.

### 🤖 Model Training
The following classification models were trained:
- K-Nearest Neighbors (KNN)  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Decision Tree  
- Random Forest

### 📏 Evaluation Metric
- **Accuracy** on the test set was used to evaluate performance.

---

## 📊 Results

| Model               | Accuracy   |
|---------------------|------------|
| KNN                 | 74.7%      |
| Logistic Regression | **79.1%** ✅ |
| SVM                 | 78.4%      |
| Decision Tree       | 71.5%      |
| Random Forest       | 76.3%      |

---

## 🔍 Conclusion

- **Logistic Regression** achieved the highest accuracy of **79.1%** and is the most suitable model for this churn prediction task.
- SVM also performed well, while Decision Trees had the lowest accuracy.
- Proper preprocessing and feature encoding significantly impacted model performance.

---

## ⚙️ Tools & Libraries

- Python  
- Pandas  
- NumPy  
- Matplotlib & Seaborn  
- Scikit-learn  
- Jupyter Notebook
