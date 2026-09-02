# Customer-churn-prediction
Predict whether a customer will cancel a service.
# 📊 Customer Churn Prediction

## 🚀 Project Overview
Customer attrition costs telecom companies millions annually. The goal of this project is to predict which customers are at high risk of canceling their service, allowing the retention team to proactively offer incentives. 

**Business Impact:** Identifying at-risk customers early can optimize marketing spend and improve overall customer lifetime value.

## 📂 Data Source
* **Dataset:** Telco Customer Churn (Kaggle)
* **Description:** 7,043 rows and 21 features encompassing customer demographics, account information, and subscribed services.

## 🛠️ Tools & Methodology
* **Language:** Python
* **Libraries:** Pandas, Scikit-Learn, XGBoost, Matplotlib, Seaborn
* **Environment:** Google Colab
* **Workflow:**
  1. **Data Cleaning:** Handled missing values in the `TotalCharges` column and encoded categorical variables.
  2. **Exploratory Data Analysis (EDA):** Analyzed correlation between contract types, monthly charges, and churn rate.
  3. **Modeling:** Trained Logistic Regression, Random Forest, and XGBoost classifiers. Handled class imbalance using SMOTE.

## 📈 Key Findings & Results
* Customers on **Month-to-Month contracts** and those utilizing **Electronic Checks** have the highest churn rates.
* **Best Performing Model:** XGBoost achieved an **F1-Score of 0.82** and a **ROC-AUC of 0.86**.
* *Insert a link to an image of your Confusion Matrix or Feature Importance plot here, if available.*

## 💻 How to Run This Project
1. Clone the repository:
   `git clone https://github.com/YourUsername/customer-churn-prediction.git`
2. Open the `Customer_Churn_Analysis.ipynb` notebook in Google Colab or Jupyter.
3. Download the dataset from Kaggle and update the file path in the first cell.
4. Run the cells sequentially.
