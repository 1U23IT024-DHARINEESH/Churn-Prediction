# Churn-Prediction

# Customer Churn Prediction Using Machine Learning

## 1. Project Overview
Customer Churn Prediction is a Machine Learning project used to predict whether a customer will continue using a service or leave the organization.

This project analyzes customer demographic information, credit card details, account information, and transaction behavior to identify customers who are at risk of leaving.

## 2. Problem Statement
Customer churn is a major challenge for businesses because losing existing customers affects revenue and business growth.

This project uses Machine Learning classification algorithms to identify customers who are likely to become Attrited Customers and helps organizations improve customer retention.

## 3. Objectives
- Analyze customer demographic and behavioral data.
- Perform data cleaning and preprocessing.
- Understand factors associated with customer churn.
- Build Machine Learning classification models.
- Predict Existing Customers and Attrited Customers.
- Evaluate model performance using different metrics.

## 4. Dataset Description
The dataset contains:

- **Total Records:** 10,127
- **Total Attributes:** 21
- **Target Column:** Attrition_Flag

### Important Features
| Feature | Description |
|---|---|
| CLIENTNUM | Customer ID |
| Customer_Age | Customer age |
| Gender | Customer gender |
| Dependent_count | Number of dependents |
| Education_Level | Education qualification |
| Marital_Status | Marital status |
| Income_Category | Income category |
| Card_Category | Card type |
| Credit_Limit | Credit limit |
| Total_Trans_Amt | Total transaction amount |
| Total_Trans_Ct | Total transaction count |
| Avg_Utilization_Ratio | Credit utilization ratio |
| Attrition_Flag | Customer status (Target) |

## 5. Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## 6. Data Preprocessing
The following preprocessing steps are performed:
- Dataset loading and inspection.
- Checking missing values.
- Checking duplicate records.
- Separating categorical and numerical columns.
- Handling categorical and numerical data.
- Preparing data for Machine Learning.

## 7. Exploratory Data Analysis (EDA)
The project includes:

- Data Overview
- Univariate Analysis
- Bivariate Analysis
- Categorical Data Visualization
- Numerical Data Analysis
- Box Plot Analysis
- Correlation Analysis

## 8. Machine Learning Algorithms

Three classification algorithms are implemented:

**Model 1: Decision Tree Classifier**

Used to classify customers based on decision rules.

**Model 2: Random Forest Classifier**

Uses multiple decision trees to improve prediction performance.

**Model 3: Gradient Boosting Classifier**

Combines multiple weak learners to improve classification performance.

## 9. Model Evaluation
The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score

The performance of the three models is compared using a model evaluation table.

## 10. Train-Test Split
The dataset is divided into:

- Training Data: 70%
- Testing Data: 30%

Random State: 42

## 11. Project Structure

```text
Churn-Prediction/
│
├── Churn Prediction.ipynb
├── Churn Prediction.csv
└── README.md
```

## 12. Installation

Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```

## 13. How to Run the Project

1. Download or clone this repository.
2. Install the required Python libraries.
3. Place the dataset in the project folder.
4. Open the Jupyter Notebook.
5. Update the dataset file path if required.
6. Run all notebook cells.

## 14. Conclusion
This project demonstrates how Machine Learning can be used to predict customer churn.

Decision Tree, Random Forest, and Gradient Boosting algorithms are implemented and evaluated using Accuracy, Precision, Recall, and F1-Score.

The project helps identify customers who are at risk of leaving and supports organizations in taking proactive steps to improve customer retention.
