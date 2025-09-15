📉 Customer Churn Prediction

📌 Project Overview

This project predicts whether a customer will churn (leave the service) or remain subscribed, using machine learning techniques.
The aim is to demonstrate data preprocessing, exploratory data analysis (EDA), and model building skills that are highly relevant for real-world business problems.

🛠️ Tools & Technologies

Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)

Machine Learning Models: Logistic Regression, Decision Tree, Random Forest

Google Colab / Jupyter Notebook for development & execution

📂 Dataset

The dataset used is a Telco Customer Churn dataset, containing customer demographics, account information, and service usage details.
Key columns include:

customerID – Unique customer identifier

gender, SeniorCitizen, Partner, Dependents – Demographics

tenure, Contract, MonthlyCharges, TotalCharges – Account & billing info

Churn – Target variable (Yes/No)

🔍 Analysis Stages
1. Beginner Level

Loaded dataset and performed initial exploration

Checked and cleaned missing/invalid values

Visualized churn distribution

2. Intermediate Level

Encoded categorical variables for ML compatibility

Split data into training and testing sets

Trained a Logistic Regression model with tuned iterations (max_iter)

3. Advanced Level

Evaluated the model using:

Accuracy

Precision

Recall

F1-score

Visualized feature correlations with churn

📈 Key Insights

Customers on month-to-month contracts are more likely to churn.

Higher monthly charges correlate with increased churn.

Longer tenure customers are less likely to leave.


🚀 How to Run

Clone the repository:

git clone https://github.com/<your-username>/<repo-name>.git


Open the notebook in Google Colab or Jupyter Notebook.

Install required libraries:

pip install pandas numpy scikit-learn matplotlib seaborn


Run all cells to reproduce results.
