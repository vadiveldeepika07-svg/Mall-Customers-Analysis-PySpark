 Mall Customers Analysis using PySpark and Databricks

1. Project Overview

This project focuses on customer segmentation, spending behaviour analysis, and exploratory data analysis (EDA) using PySpark in Databricks.

The objective is to identify customer spending patterns based on age, gender, annual income, and spending scores.

2. Tools and Technologies

- Python
- PySpark
- Databricks
- Pandas
- Matplotlib
- Seaborn
- GitHub

 3. Dataset Description

The Mall Customers dataset contains 200 customer records with the following attributes:

- Customer ID
- Gender
- Age
- Annual Income (K$)
- Spending Score (1–100)

## 4. Data Cleaning and Preprocessing

The following data cleaning operations were performed using PySpark:

- Checked and handled missing values.
- Removed duplicate records.
- Standardized column names.
- Checked data types and schema.
- Prepared the cleaned dataset for analysis.

 5. Feature Engineering

Created two additional columns using PySpark conditional transformations.

Age Group Classification

Customers were categorized into:

- Teenager
- Young Adult
- Middle Aged
- Senior

Spending Category Classification

Based on spending score:

- High Spender: Score >= 70
- Medium Spender: Score >= 40 and less than 70
- Low Spender: Score less than 40

 Income Band Classification

Based on annual income:

- Low Income: Below 40K
- Medium Income: 40K to below 70K
- High Income: 70K and above

 6. Exploratory Data Analysis (EDA)

Performed customer analysis using PySpark DataFrame operations.

 A. Spending Score by Gender

- Calculated average spending score by gender.
- Counted customers in each gender category.


 B. Spending Category by Age Group

- Counted customers across age groups and spending categories.
- Calculated average annual income for each combination.

 C. Income Band vs Spending Category

- Analyzed customer spending behaviour across income bands.
- Identified customer distribution by spending category.

 D. Customer Segmentation

Analyzed:
- Spending Category vs Gender
- Age Group vs Spending Category

 7. Data Visualizations

Created six visualizations using Python, Pandas, Matplotlib, and Seaborn.

1. Spending Score Distribution – Histogram
2. Customers by Spending Category – Count Plot
3. Average Spending Score by Gender – Bar Chart
4. Average Spending Score by Age Group – Bar Chart
5. Annual Income vs Spending Score – Scatter Plot
6. Age vs Spending Score – Scatter Plot
7. Spending Category by Age Group – Stacked Bar Chart
8. Spending Category by Income Band – Stacked Bar Chart

