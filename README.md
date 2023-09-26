# Exploratory Data Analysis on Bank Churners

## Introduction

Customer churn is a major problem for banks as it can lead to significant losses in revenue. Understanding why customers leave and what factors contribute to their decision to do so is crucial in developing strategies to retain customers. This project aims to perform an exploratory data analysis on the Bank Churners dataset to gain insights into factors that contribute to customer churn.

## Dataset

The Bank Churners dataset is a public dataset that contains information on customer demographics, account information, and transaction history for a bank. The dataset contains 10,000 observations and 21 variables, including the target variable 'Attrition_Flag', which indicates whether a customer has churned or not.

## Methodology

The following methodology was used in this project:

1. Importing Libraries: Libraries such as Pandas, Numpy, Matplotlib, and Seaborn were imported for data manipulation and visualization.

2. Loading the Dataset: The dataset was loaded using pd.read_csv() from the local computer.

3. Exploratory Data Analysis: The dataset was explored to identify columns, unique values, missing values, shape of the entire dataset, info of the columns and data types, and statistical analysis of the data. Outliers were also identified in the dataset.

4. Relationship, Insights, and Visualizations: Univariate, bivariate, and multivariate analysis techniques were used to visualize the data and identify patterns and trends. Relationships between variables were explored using scatterplots, boxplots, and heatmaps.

## Results

The exploratory data analysis revealed several insights into factors that contribute to customer churn:

- The majority of customers who churned were credit card holders.
- Customers who had higher credit limits were less likely to churn.
- Customers who had lower utilization rates were less likely to churn.
- Customers who had lower total transaction counts were more likely to churn.
- Customers who had lower average transaction amounts were more likely to churn.
- Customers who had lower tenure were more likely to churn.

These insights can help banks develop strategies to retain customers and reduce revenue losses due to churn.

## Conclusion

Through exploratory data analysis on the Bank Churners dataset, we gained insights into factors that contribute to customer churn. By understanding these factors, banks can develop strategies to retain customers and reduce revenue losses due to churn.