#  Customer Churn Analysis

## An Overview
This project analyzes customer churn to help a company understand **why customers leave** and how to **predict which customers are at risk** of leaving.  
The analysis uses data exploration, visualization, and machine learning to uncover key patterns and build a model that can accurately predict churn.

The goal is to help businesses improve **customer retention** by identifying important churn factors and taking proactive steps to reduce customer loss.

---

##  Objectives
- Analyze customer demographics, account details, and service usage to understand churn patterns.  
- Build and evaluate predictive models that can identify customers likely to churn.  
- Provide actionable insights and recommendations to improve customer retention rates.

---

##  Dataset Description
The dataset contains customer data from a telecommunications company.  
Key columns include:

| Feature Category | Description |
|------------------|-------------|
| **Demographics** | Gender, SeniorCitizen, Partner, Dependents |
| **Account Information** | Tenure, Contract type, Payment method, Monthly charges, Total charges |
| **Services** | InternetService, PhoneService, StreamingTV, StreamingMovies, etc. |
| **Target Variable** | `Churn` — indicates whether the customer left or stayed |

---

##  Project Workflow

### 1️.Data Loading & Cleaning
- Imported dataset using **Pandas**.  
- Handled missing and inconsistent data.  
- Converted data types and removed unnecessary columns.  

### 2️.Exploratory Data Analysis (EDA)
- Explored churn patterns through summary statistics and visualizations.  
- Used **Matplotlib** and **Seaborn** to identify relationships between churn and key factors (tenure, contract type, monthly charges, etc.).  

### 3️.Feature Engineering
- Encoded categorical variables using **LabelEncoder** and **OneHotEncoder**.  
- Scaled numerical features to prepare for model training.

### 4️.Model Building
- Built multiple classification models:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
- Compared models to find the best-performing one for churn prediction.

### 5️.Model Evaluation
- Evaluated models using metrics like:
  - **Accuracy**
  - **Precision**
  - **Recall**
  - **F1-Score**
  - **ROC-AUC Curve**

### 6️.Insights & Recommendations
- Identified key churn factors such as contract type, tenure, and monthly charges.  
- Provided business recommendations to improve retention.

---

##  Tools & Technologies Used
- **Python**
- **Jupyter Notebook**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## Key Findings
- Customers with **month-to-month contracts** are more likely to churn.  
- **High monthly charges** increase churn risk significantly.  
- Customers with **longer tenures** are less likely to leave.  
- **Electronic check payments** had higher churn compared to other payment methods.

---

## 💡 Business Recommendations
- Offer **discounts or loyalty programs** for month-to-month contract customers.  
- Provide **customized plans** for customers with high monthly charges.  
- Improve **customer engagement** early in the contract to increase tenure.  
- Educate customers about **alternative payment methods** to reduce churn.

---

## Future Improvements
- Implement more advanced models like **XGBoost** or **Neural Networks**.  
- Build an **interactive dashboard** using Streamlit or Power BI.  
- Automate churn prediction using live data integration.

---

## 📂 How to Use
1. Download or clone this repository.  
2. Open `Customer Churn Analysis.ipynb` in **Jupyter Notebook** or **VS Code**.  
3. Run each cell sequentially to explore the data, train models, and view results.

---

## 👨‍💻 Author
**Oabile Moroka**  
📧 oabilemoroka@gmail.com  
🔗 Oabilemoroka (https://github.com/Oabilemoroka)

---

⭐ *If you found this project helpful, please give it a star on GitHub!*
