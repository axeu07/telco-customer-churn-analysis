# Telco Customer Churn Analysis

## Introduction & Objective
The objective of this project is to analyze customer churn using a real-world telecom dataset and build machine learning models to predict whether a customer is likely to leave the service. This assessment evaluates data cleaning, exploratory data analysis (EDA), feature engineering, model building, and evaluation skills.

The dataset used is the **Telco Customer Churn** dataset, which contains customer demographics, service usage details, and churn information.

---

## Dataset
- **Source:** Kaggle – Telco Customer Churn Dataset  
- **Target Variable:** `Churn`
  - `0` → Customer did not churn  
  - `1` → Customer churned  

---

## Tools & Technologies
- Python
- Jupyter Notebook
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

## Part 1: Data Cleaning & Exploratory Data Analysis (EDA)

### Data Cleaning
- Converted `TotalCharges` from object to numeric format
- Handled missing values appropriately
- Removed unnecessary columns
- Encoded categorical variables using one-hot encoding

### Exploratory Data Analysis
- Analyzed churn distribution and class imbalance
- Examined relationships between churn and key features
- Generated visualizations to understand customer behavior

### Key Insights
- Customers with shorter tenure are more likely to churn
- Month-to-month contract customers show higher churn rates
- Higher monthly charges are associated with increased churn risk

---

## Part 2: Model Building & Evaluation

### Model Development
- Split data into training and testing sets (80/20 split)
- Trained a **Random Forest Classifier** to predict churn

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Classification report

### Results
- The Random Forest model achieved approximately **80% accuracy**
- Strong performance in identifying non-churn customers
- Moderate recall for churn customers due to class imbalance

---

## Conclusion
The Random Forest model performed well on the Telco Customer Churn dataset and provided meaningful insights into customer behavior. While overall accuracy is strong, improving recall for churned customers would further enhance business value. This project demonstrates the ability to handle real-world data, extract insights, and build interpretable machine learning models.

---

## How to Run
1. Clone the repository
2. Open the Jupyter Notebook (`churn_analysis.ipynb`)
3. Run all cells sequentially
4. Ensure required libraries are installed

---

## Author
Ayush Petwal