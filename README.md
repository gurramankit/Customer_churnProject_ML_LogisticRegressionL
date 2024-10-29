# Customer_churnProject_ML_LogisticRegressionL
 this project involves analyzing customer churn data to identify patterns and prevent customer churn by understanding the behaviors and characteristics that lead to it.
## Overview
This project aims to understand and predict customer churn for a telecom company by analyzing customer behavior and demographics. By predicting the likelihood of churn, the company can take preemptive steps to retain valuable customers and address churn-related concerns effectively.

## Dataset
The data includes customer demographics, service information, and usage metrics, providing insights into customer behavior related to churn.

## Problem Statement
The goal is to predict if a customer will churn based on their usage patterns, contract, and payment methods, allowing the company to implement strategies to reduce churn.

## Project Tasks
### 1. Data Manipulation
- Extracted specific data subsets for senior citizens, long-tenure customers, and churned accounts.
- Calculated churn counts and filtered data for custom queries.

### 2. Data Visualization
- **Bar Plot**: Internet service category distribution.
- **Histogram**: Tenure distribution with 30 bins.
- **Scatter Plot**: Tenure vs. Monthly Charges.
- **Box Plot**: Contract types vs. Tenure distribution.

### 3. Linear Regression
Built a linear regression model to predict monthly charges from tenure:
- 70:30 train-test split.
- Calculated RMSE to evaluate model accuracy.

### 4. Logistic Regression
Developed a logistic regression model to predict customer churn:
- Simple model: Monthly charges as the independent variable.
- Multiple logistic regression model: Tenure and Monthly Charges as independent variables.
- Achieved **79% accuracy** on the test set.

### 5. Decision Tree
Implemented a decision tree model to predict churn with tenure as the feature:
- 80:20 train-test split, evaluated with a confusion matrix.

### 6. Random Forest
Built a random forest model using tenure and monthly charges to predict churn:
- 70:30 train-test split, evaluated accuracy and confusion matrix.

## Results
- Logistic regression model performed best, achieving **79% accuracy** in predicting customer churn.

## Installation and Usage
1. Clone this repository:
    ```bash
    git clone https://github.com/gurramankit/customer-churn-analysis.git
    ```
2. Install the necessary libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the project:
    ```bash
    python main.py
    ```

## Project Structure
- `data/` - Contains the customer churn dataset.
- `notebooks/` - Jupyter notebooks for data manipulation, EDA, and model development.
- `src/` - Python scripts for data processing and model implementation.
- `README.md` - Overview and instructions.
- `requirements.txt` - List of dependencies.

## Contact
For questions or suggestions, feel free to reach out at [ankithkumarankith122@gmail.com].
