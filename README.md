# 📌 Customer Churn Prediction – Machine Learning Project

## 📄 Problem Statement
Customer churn is a major challenge for subscription-based businesses because losing customers directly reduces revenue and growth. The objective of this project is to develop a **machine learning model** that predicts whether a customer is likely to churn based on their usage patterns, demographics, and subscription details.

This helps businesses:
- Identify customers at high risk of churn
- Take proactive retention actions
- Improve customer experience
- Reduce churn rate and maximize profitability

## 📊 Dataset Description
The dataset contains customer-level information with the following columns:

| Column | Description |
|--------|-------------|
| **CustomerID** | Unique identifier for each customer |
| **Name** | Customer name |
| **Age** | Age of the customer |
| **Gender** | Male or Female |
| **Location** | Customer's city (Houston, Los Angeles, Miami, Chicago, New York) |
| **Subscription_Length_Months** | Total months subscribed |
| **Monthly_Bill** | Customer's monthly bill amount |
| **Total_Usage_GB** | Total data usage in GB |
| **Churn** | Target variable: 1 (Churned), 0 (Not Churned) |

## 🛠️ Tech Stack Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow & Keras
- Neural Networks
- PCA
- VIF
- GridSearchCV
- Cross-Validation
- EarlyStopping
- ModelCheckpoint
- Jupyter Notebook

## 📈 Outcome
The final model predicts whether a customer is likely to churn using multiple ML algorithms. Key outcomes:

✔ Identifies customers with high churn probability  
✔ Helps plan personalized retention strategies  
✔ Reduces potential revenue loss  
✔ Demonstrates complete ML workflow

## 🚀 How to Run the Project
```bash
git clone <repo-link>
cd customer-churn-prediction
pip install -r requirements.txt
jupyter notebook
```
