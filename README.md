# Customer_Churn_Prediction
Customer churn is when customers stop doing business with a company.   In the telecom industry, predicting churn is critical for customer retention strategies.  

In this project, we use **machine learning** to predict whether a telecom customer will churn or not, based on customer demographics, account information, and service usage.

---

## 📊 Dataset
- **Source**: [Telco Customer Churn (Kaggle)](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)  
- **Rows**: 7,043 customers  
- **Columns**: 21 features + target (Churn)  

Key Columns:
- `gender`, `SeniorCitizen`, `Partner`, `Dependents`
- `tenure`, `PhoneService`, `InternetService`, `Contract`, `PaymentMethod`
- `MonthlyCharges`, `TotalCharges`
- `Churn` (target variable: Yes / No)

---

## ⚙️ Steps
1. **Data Cleaning**
   - Handled missing values in `TotalCharges`  
   - Dropped `customerID` column  

2. **Data Preprocessing**
   - Encoded categorical features using Label Encoding  
   - Standardized numerical features  

3. **Exploratory Data Analysis (EDA)**
   - Churn rate distribution  
   - Impact of Contract type, Tenure, and Internet service on churn  

4. **Modeling**
   - Logistic Regression  
   - Random Forest  
   - XGBoost  

5. **Evaluation**
   - Accuracy, Precision, Recall, F1-Score  
   - Confusion Matrix  
   - Feature Importance  

---

## 📷 Results & Visuals
Example visualizations (saved in `images/` folder):
- Churn distribution  
- Confusion matrix of models  
- Top features driving churn  

**Best Model:**  
✅ Random Forest with ~80% accuracy and balanced precision/recall  

---

## 🚀 Tech Stack
- **Python** (NumPy, Pandas)  
- **Visualization**: Matplotlib, Seaborn  
- **ML Models**: Scikit-learn, XGBoost  
- **Notebook**: Jupyter  

