# Telecom Customer Churn Analysis

A Python data analysis project focused on understanding customer churn in a telecommunications company and exploring the factors associated with customers leaving the service.

## Analysis Results Preview

The following values are reported in the committed notebook's saved outputs. They are descriptive analysis results, not prediction scores.

| Finding | Result |
| --- | ---: |
| Customer records | 7,043 |
| Dataset columns | 21 |
| Customers who churned | 1,869 |
| Customers who remained | 5,174 |
| Customers with monthly charges above 80 | 2,666 |

The most common payment method was **Electronic check** (2,365 customers). Average monthly charges were **66.40** for month-to-month contracts, **65.05** for one-year contracts, and **60.77** for two-year contracts. These summaries do not establish what causes churn.

## Project Objective

The goal is to practice a data-analysis workflow by cleaning telecom customer data and exploring patterns associated with churn.

## Project Files

- `telecom_customer_churn_analysis.ipynb` — Main Jupyter Notebook containing the analysis and project workflow.
- `WA_Fn-UseC_-Telco-Customer-Churn.csv` — Dataset used in the project.
- `Project_Report.xlsx` — Project report / supporting analysis.
- `requirements.txt` — Python dependencies required to run the project.

## Project Workflow

The notebook covers the following analysis and programming activities:

1. Data loading and exploration
2. Data cleaning and preprocessing
3. Exploratory Data Analysis (EDA)
4. Investigation of customer churn patterns
5. Python programming exercises and NumPy operations
6. Pandas data cleaning and analysis
7. Excel export and interpretation of results

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- openpyxl (Excel reporting)

 > Installation dependencies are listed in `requirements.txt`; the notebook currently uses NumPy, Pandas, and openpyxl.

## Dataset

The project uses the Telco Customer Churn dataset:

`WA_Fn-UseC_-Telco-Customer-Churn.csv`

The dataset contains customer-related information that can be used to study the relationship between customer characteristics, services, account information, and churn behavior.

## How to Run the Project

1. Clone the repository:

```bash
git clone https://github.com/MahmoudOsama260013/MahmoudOsama260013-Telecom_Customer_Churn_Project.git
```

2. Move into the project folder:

```bash
cd MahmoudOsama260013-Telecom_Customer_Churn_Project
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

4. Open the Jupyter Notebook:

```bash
jupyter notebook telecom_customer_churn_analysis.ipynb
```

## What I Practiced

Through this project, I practiced:

- Working with real-world tabular data
- Cleaning and preparing data for analysis
- Exploratory data analysis
- Data analysis workflow
- Exporting results to Excel
- Organizing a data analysis project

## Future Improvements

Possible improvements include:

- Add clearer visual summaries of the main findings
- Extend the analysis with an initial machine learning baseline and appropriate evaluation
- Explore feature engineering and compare models after establishing a baseline
- Consider an interactive dashboard for presenting analysis results

## Author

**Mahmoud Osama Hassan Alsagga**

Data Science & Artificial Intelligence Student
