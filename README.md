# Retail_Analytics_and_Business_Insights

This project involves analyzing customer and transaction data from a large retailer of apparel and accessories with locations across the U.S. The goal is to assess profitability and customer satisfaction with a focus on four store locations in the Boston metro area.

## Project Overview

The analysis is divided into two parts:

1. **Descriptive Analytics**
   - Data cleaning, manipulation, and inspection
   - Data visualization, including summary statistics and boxplots
   - Blended gross margin calculations
   - Identification and handling of outliers

2. **Statistical Inference**
   - Hypothesis testing
   - Regression analysis for predicting gross margin
   - Synthesis of actionable business insights

## Data Files

The following data files are provided for analysis:

- **stores.csv**: Information about the store locations.
- **customers.xlsx**: Demographic and satisfaction survey data for loyalty program members. Includes details about customer age, satisfaction, and membership length.
- **sales.xlsx**: Data on sales transactions, including product category, sale amount, gross margin, and customer loyalty status.

### Key Attributes

- **Customer Data**: Customer demographics, in-store and selection satisfaction, loyalty status, etc.
- **Sales Data**: Sales transactions, including store location, sale amount, product category, and gross margin.
- **Stores Data**: Information about each store location.

## Tasks

### Part 1: Descriptive Analytics

1. **Data Inspection and Cleaning**
   - Clean categorical and numerical data in the customers file.
   - Remove or handle missing values and outliers.
   
2. **Data Manipulation and Wrangling**
   - Create a table showing the number of items purchased and average item sale price for each customer.
   - Join the sales and cleaned customers data to create a 'customer_purchases' dataset.

3. **Summary Statistics and Visualization**
   - Calculate the mean, median, standard deviation, and skewness for sale amount.
   - Create boxplots for sale amounts across all records and for each product category.
   - Calculate the blended gross margin by product category.

4. **Outlier Detection**
   - Identify outliers in the sale amount and provide recommendations for handling them.

### Part 2: Statistical Inference

1. **Hypothesis Testing**
   - Formulate and test a hypothesis related to gross margin, product categories, or sales performance across stores.

2. **Regression Analysis**
   - Build a regression model to predict gross margin and identify key variables affecting it.

3. **Synthesis of Insights**
   - Summarize the most important findings and provide actionable recommendations to management.

## Files

1. `customer_purchases.csv` or `.xlsx`: The cleaned customer data with transaction details.
2. `analysis_code.R`: The code used for the analysis.
3. PDF Report:
   - Entity Relationship Diagram (ERD)
   - Summary of data cleaning steps
   - Summary statistics and visualizations
   - Analysis of outliers
   - Hypothesis test explanation
   - Regression model summary
   - Key findings and business insights

## Tools and Libraries

This analysis can be performed using tools like R or Python. Some useful libraries include:

- **Python**:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - statsmodels
  
- **R**:
  - tidyverse
  - ggplot2
  - dplyr
  - stats

