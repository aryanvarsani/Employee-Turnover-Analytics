# Employee Turnover Analytics

## Overview
This project focuses on predicting employee turnover using machine learning. By analyzing various factors such as satisfaction levels, evaluations, hours worked, and salary, the goal is to identify patterns that lead to an employee leaving the company. This helps HR departments take proactive measures to retain valuable talent.

## Dataset
The dataset used is `HR_comma_sep.csv`, which contains information on 14,999 employees. 

The features include:
- **satisfaction_level**: Employee satisfaction level (0-1)
- **last_evaluation**: Score of the last evaluation (0-1)
- **number_project**: Number of projects the employee has worked on
- **average_montly_hours**: Average monthly hours worked
- **time_spend_company**: Years spent at the company
- **Work_accident**: Whether the employee had a work accident (1 = Yes, 0 = No)
- **left**: Whether the employee left the company (1 = Yes, 0 = No) - **Target Variable**
- **promotion_last_5years**: Whether the employee was promoted in the last 5 years (1 = Yes, 0 = No)
- **sales**: The department the employee works in
- **salary**: Salary level (low, medium, high)

## Technologies Used
- **Python 3**
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for data visualization
- **Scikit-Learn** for machine learning modeling (Logistic Regression, etc.)
- **Imbalanced-learn (SMOTE)** for handling imbalanced datasets

## Files in the Repository
- `HR_comma_sep.csv`: The dataset.
- `code.ipynb`: Jupyter notebook containing the Exploratory Data Analysis (EDA), data preprocessing, and model training/evaluation.
- `ppt.pdf`: Presentation slides summarizing the findings and project outcomes.

## Getting Started
To run the notebook locally:
1. Clone the repository:
   ```bash
   git clone https://github.com/aryanvarsani/Employee-Turnover-Analytics.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Employee-Turnover-Analytics
   ```
3. Install the required dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn imbalanced-learn jupyter
   ```
4. Open the Jupyter Notebook:
   ```bash
   jupyter notebook code.ipynb
   ```
