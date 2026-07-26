# Telecom Customer Churn Prediction using Machine Learning

## Project Overview

Customer churn is one of the biggest challenges faced by telecom companies. Predicting customers who are likely to leave helps businesses take proactive measures to improve customer retention and reduce revenue loss.

This project develops a machine learning model to predict customer churn using customer demographic information and telecom usage data. The project follows a complete data science workflow, including data collection, data preprocessing, exploratory data analysis (EDA), feature engineering, model building, model evaluation, and business insights.

---

## Objectives

* Connect to a MySQL database and load telecom customer data.
* Perform data cleaning and preprocessing.
* Explore the dataset using data visualization.
* Train multiple machine learning models for churn prediction.
* Compare model performance.
* Identify the best-performing model.
* Generate business insights to support customer retention strategies.

---

## Dataset

The dataset contains telecom customer information such as:

* Customer ID
* Telecom Partner
* Gender
* Age
* State
* City
* Pincode
* Date of Registration
* Number of Dependents
* Estimated Salary
* Calls Made
* SMS Sent
* Data Used
* Churn Status (Target Variable)

---

## 🛠️ Technologies Used

* Python
* Jupyter Notebook
* MySQL
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

1. Import Libraries
2. Connect to MySQL Database
3. Load Dataset
4. Data Exploration
5. Data Cleaning
6. Exploratory Data Analysis (EDA)
7. Feature Engineering
8. Feature Selection
9. Train-Test Split
10. Model Building
11. Model Evaluation
12. Model Comparison
13. Business Insights
14. Conclusion

---

## Machine Learning Models

The following classification algorithms were implemented:

* Logistic Regression
* Decision Tree Classifier
* Random Forest Classifier

---

## Model Performance

| Model               |   Accuracy |
| ------------------- | ---------: |
| Logistic Regression | **79.92%** |
| Decision Tree       | **66.57%** |
| Random Forest       | **79.92%** |

Although Logistic Regression and Random Forest achieved the same accuracy, Random Forest was selected as the preferred model because ensemble learning generally provides better robustness and reduces the risk of overfitting.

---

## Visualizations

The project includes:

* Customer Churn Distribution
* Correlation Heatmap
* Confusion Matrix
* Feature Importance Analysis

---

## Business Insights

* Customer demographics and telecom usage significantly influence churn.
* Machine learning models can identify customers who are at risk of leaving.
* Predictive analytics enables telecom companies to improve customer retention through targeted interventions.
* Feature importance analysis helps businesses understand the key factors contributing to customer churn.

---

## Challenges Faced

* Establishing a connection between Python and MySQL.
* Importing and validating data from the database.
* Encoding categorical variables.
* Handling date features for machine learning.
* Selecting appropriate features for prediction.
* Comparing multiple machine learning models.

---

## How to Run the Project

1. Clone the repository.
2. Install the required Python libraries:

```bash
pip install -r requirements.txt
```

3. Open the Jupyter Notebook.
4. Connect to your MySQL database.
5. Run all notebook cells sequentially.

---

## Project Structure

```text
telecom-customer-churn-prediction/
│
├── Telecom_Customer_Churn_Prediction.ipynb
├── README.md
├── requirements.txt
└── images/
```

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning
* Model Evaluation
* Data Visualization
* SQL Integration
* Business Insight Generation

---

## Author

**Abhilash Sonar**

GitHub: https://github.com/abhilashsonar9

---

## ⭐ If you found this project useful, consider giving it a star!
