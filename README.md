
# Customer Churn Analysis

## Project Overview
This project analyzes customer churn data using Python to understand customer behavior, identify churn patterns, and generate business insights that may help improve customer retention.

## Objectives
- Calculate the overall customer churn rate.
- Compare churn rates across different contract types.
- Analyze the relationship between customer tenure and churn.
- Compare monthly charges for churned and retained customers.
- Analyze churn patterns based on Tech Support and Internet Service.
- Identify customer segments that may require retention strategies.

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Data Cleaning
- Standardized inconsistent text values.
- Removed unwanted spaces from text columns.
- Checked missing values.
- Identified duplicate records.
- Checked data types and data consistency.
- Prepared the dataset for analysis.

## Business Questions
1. What is the overall customer churn rate?
2. Which contract type has the highest churn rate?
3. How does customer tenure relate to churn?
4. Do monthly charges affect customer churn patterns?
5. How does Tech Support relate to churn?
6. Which customer groups have higher churn rates?

## Data Analysis & Visualization
The project uses Python libraries to analyze customer churn patterns and create visualizations that help explain customer behavior.

## Business Insights
- Identify contract types with higher churn rates.
- Understand customer segments that may need additional support.
- Explore relationships between customer charges and churn.
- Help businesses identify potential customer retention opportunities.

## Project Files
- `customers_churn_analysis.ipynb` — Jupyter Notebook containing data cleaning, analysis, and visualizations.
- `customer_churn.csv` — Dataset used for the analysis.

## How to Run This Project

### 1. Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/customer-churn-analysis.git
```

### 2. Install Required Libraries
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Load the Dataset
Keep the CSV file in the same folder as the notebook.

```python
import pandas as pd

df = pd.read_csv("customer_churn.csv")
```

### 4. Run the Notebook
Open `customers_churn_analysis.ipynb` in Jupyter Notebook or JupyterLab and run the cells in order.

## Conclusion
This project demonstrates the use of Python for data cleaning, exploratory data analysis, and data visualization to understand customer churn and explore customer retention opportunities.

## Author
Shreeram Shinde

**Role:** Aspiring Data Analyst
