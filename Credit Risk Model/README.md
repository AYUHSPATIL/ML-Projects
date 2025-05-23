# 💰 Credit Risk Modeling  

## 📌 Overview  
This project is a **Credit Risk Modeling** system that evaluates a borrower's creditworthiness based on financial indicators. The model predicts whether a loan application is risky or safe using machine learning techniques.  

---

## 💡 Intuition Behind the Project  
Understanding **credit risk** is crucial for financial institutions.  
- 📊 Helps banks and lenders assess **loan repayment probability**.  
- ⚖ Balances **risk vs. reward** when approving loans.  
- 🚀 Uses **data-driven insights** to make informed lending decisions.  

---

## 🎯 Project Idea  
🔹 **Objective**: Build a predictive model that classifies loan applicants as **safe or risky**.  
🔹 **Approach**: Use **financial ratios and metrics** to train a machine learning model.  
🔹 **Outcome**: A web-based tool to provide real-time risk assessment.  

---

## 📂 Data Description  
The dataset contains financial metrics for different loan applicants, including:  
- 📌 **ROCE (%)** – Return on Capital Employed  
- 📌 **CASA (%)** – Current and Savings Account Ratio  
- 📌 **Return on Equity (%)** – Profitability measure  
- 📌 **Non-Interest Income (%)** – Revenue Diversity  
- 📌 **Operating Profit (%)** – Bank efficiency  
- 📌 **Operating Expenses (%)** – Cost management  
- 📌 **Interest Expenses (%)** – Loan cost  
- 📌 **Face Value** – Market valuation  

🔹 Additional concepts such as **VIF (Variance Inflation Factor) & chi-2 Contingency Rule** were used for feature selection and collinearity analysis.  

---

## 🔍 Exploratory Data Analysis (EDA)  
- 📊 **Feature Distribution Analysis** – Understanding the spread of financial variables.  
- 📉 **Correlation Heatmaps** – Identifying relationships between financial metrics.  
- 🏷 **Class Distribution** – Checking the balance between risky and safe applicants.  
- 📈 **Boxplots & Histograms** – Detecting outliers and skewness in financial features.  

---

## 🏗 Model Development  
🔹 **Feature Engineering**  
- Created new ratios for better prediction accuracy.  
- Scaled numeric variables for model optimization.  
- Applied **VIF (Variance Inflation Factor)** to detect and remove multicollinearity.  
- Used **chi-2 Contingency Rule** to evaluate categorical feature dependencies.  

🔹 **Model Selection**  
- 📌 **Logistic Regression** – A simple and interpretable model.  
- 📌 **Random Forest Classifier** – Handles non-linearity and complex interactions well.  
- 📌 **XGBoost** – Achieved the best results with optimized hyperparameters.  

🔹 **Evaluation Metrics**  
- ✅ **Accuracy Score** – Measures the overall correctness of the model.  
- ✅ **Precision & Recall** – Essential for credit risk classification, ensuring fewer false positives and false negatives.  
- ✅ **F1-Score** – Balances precision and recall, which is crucial for imbalanced datasets.  

🛠 Since credit risk classification requires minimizing **false negatives** (wrongly classifying a risky applicant as safe), **recall** plays a significant role. However, **precision** is also vital to ensure that loans given to safe applicant.

---

## 📚 What I Learned from This Project  

### 🔍 Understanding Credit Risk Modeling  

- Fundamentals of **credit risk assessment**.  
- Role of **machine learning** in predicting defaults.  
- Importance of **financial indicators** in risk evaluation.  

---

### 🛠 Data Preprocessing & Feature Engineering  
  
- **Data cleaning** to handle missing values & outliers.  
- **VIF analysis** to remove multicollinearity.  
- **Chi2 Contingency Rule** for feature selection.  

---

### 🤖 Building ML Models for Credit Risk  
 
- Implemented **Logistic Regression, Random Forest, XGBoost**.  
- Feature selection & **hyperparameter tuning** for optimization.  
- Improved **model accuracy & generalization**.  

---

### 📊 Evaluation & Interpretation  
 
- Used **precision, recall, F1-score, accuracy**.  
- **Recall** prioritized to reduce false negatives.  
- **Interpreted model insights** for financial decision-making.  

---

### 🚀 Final Thoughts  
- Gained hands-on experience in **credit risk modeling**.  
- Improved **deployment skills with Flask**.  
- Next step: **Exploring deep learning for better predictions**!  
