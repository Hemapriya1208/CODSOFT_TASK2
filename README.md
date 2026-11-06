# CODSOFT TASK 2 – Exploratory Data Analysis (EDA)

## Project Overview

This project performs **Exploratory Data Analysis (EDA)** on a sales dataset using Python. The main objective is to understand the dataset, identify important trends and patterns, study relationships between variables, and detect unusual values or outliers.

The analysis is performed using **Pandas** and statistical techniques in a Jupyter Notebook.

## Objectives

- Load and inspect the sales dataset.
- Understand the structure and characteristics of the data.
- Calculate descriptive statistics.
- Check for missing values and duplicate records.
- Analyze sales based on products, regions, and categories.
- Study relationships between numerical variables using correlation.
- Detect unusual sales values using the IQR method.
- Identify useful business insights from the dataset.

##  Technologies Used

- **Python**
- **Pandas**
- **Jupyter Notebook / Google Colab**
- **Statistical Analysis**

## 📂 Dataset

The project uses the dataset:

`EDA_sales_dataset.csv`

The dataset contains **50 records and 9 columns**, including:

- Order ID
- Product
- Category
- Region
- Quantity
- Unit Price
- Discount
- Customer Rating
- Sales

##  Analysis Performed

The notebook performs the following analysis:

### 1. Data Inspection
The dataset is loaded using Pandas and its shape, information, and sample records are examined.

### 2. Descriptive Statistics
Statistical measures such as mean, standard deviation, minimum, maximum, and quartiles are calculated to understand the numerical data.

### 3. Missing Values and Duplicates
The dataset is checked for missing values and duplicate records. The analysis found **no missing values and no duplicate rows**.

### 4. Sales Analysis
Sales are analyzed according to:

- Product
- Region
- Category

This helps identify the areas contributing the most to overall sales.

### 5. Correlation Analysis
Correlation is calculated between Quantity, Unit Price, Discount, Customer Rating, and Sales.

The analysis shows a strong positive relationship between **Unit Price and Sales**, while **Customer Rating and Sales** also have a positive relationship.

### 6. Outlier Detection
The **Interquartile Range (IQR)** method is used to identify unusual Sales values. The analysis found **0 sales outliers**.

##  Key Results

- Total records: **50**
- Total columns: **9**
- Average Sales: **119,185.40**
- Highest Sales: **414,000**
- Lowest Sales: **9,000**
- Missing values: **0**
- Duplicate records: **0**
- Sales outliers: **0**
- Highest-performing category: **Electronics**
- Highest sales region: **Chennai**
- Highest sales product: **Laptop**

##  Conclusion

This EDA project provides a clear understanding of the sales dataset through statistical analysis, grouping, correlation analysis, and outlier detection. The findings can help understand sales performance across different products, regions, and categories and support better data-driven business decisions.

