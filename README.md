# Telco-Customer-Churn-_Task_04
This project focuses on predicting customer churn using the Telco Customer Churn dataset. The goal is to analyze customer behavior, identify key factors influencing churn, and build machine learning models to classify whether a customer is likely to leave.

**Project Overview**
The notebook includes the following steps:

Loading the Telco dataset and performing exploratory data analysis.
Cleaning the dataset, handling missing values, and preprocessing features.
Encoding categorical variables and scaling numerical features using ColumnTransformer and Pipeline.
Building and training classification models including Logistic Regression and Random Forest.
Evaluating the models using accuracy scores and classification reports.
Analyzing feature importance to understand key drivers of customer churn.

**Tools and Libraries Used**
Python
Pandas and NumPy for data handling
Scikit-learn for preprocessing, pipelines, and machine learning models
Matplotlib and Seaborn for visualizations
Openpyxl for working with Excel datasets

**How to Run**
Clone the repository and install the required Python packages. Place the Telco dataset file (Telco_customer_churn.xlsx) in the project folder or update the dataset path in the notebook. Then open the Jupyter Notebook and run all cells sequentially.

**Compatibility Note**
The OneHotEncoder parameter may vary depending on your scikit-learn version. Use sparse_output=False if you are on scikit-learn 1.2 or above, otherwise use sparse=False.

**Results**
The project compares Logistic Regression and Random Forest models. Both models achieve good accuracy, with Random Forest providing feature importance insights. These results help identify the most significant customer attributes related to churn.
