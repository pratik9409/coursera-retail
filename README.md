# coursera-retail
## Perform exploratory data analysis on retail data with Python


### Overview
In this project, you will step into the shoes of an entry-level data analyst at an online retail company, helping interpret real-world data to help make key business decisions.

### Project Scenario

In this project, you will be working with transactional data from an online retail store. The dataset contains information about customer purchases, including product details, quantities, prices, and timestamps. Your task is to explore and analyze this dataset to gain insights into the store's sales trends, customer behavior, and popular products. 

By conducting exploratory data analysis, you will identify patterns, outliers, and correlations in the data, allowing you to make data-driven decisions and recommendations to optimize the store's operations and improve customer satisfaction. Through visualizations and statistical analysis, you will uncover key trends, such as the busiest sales months, best-selling products, and the store's most valuable customers. Ultimately, this project aims to provide actionable insights that can drive strategic business decisions and enhance the store's overall performance in the competitive online retail market.

### Project Objectives

1. Describe data to answer key questions to uncover insights

2. Gain valuable insights that will help improve online retail performance

3. Provide analytic insights and data-driven recommendations


### Your Challenge
Your challenge will be to conduct an exploratory data analysis to help make key business decisions. To do this, you will load, clean, process, analyze, and visualize data. You will also pose questions, and seek to answer them meaningfully using the dataset provided.

In this project, we'll use a data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.

After you perform your analysis, you will share your findings.




## Summary:
**To complete the project on analyzing the online retail dataset, I employed several techniques:**

1. **Data Loading and Inspection:** I used Pandas to load the dataset and inspected its structure, data types, and missing values using info() and describe().

2. **Data Cleaning:** I handled missing values by filling CustomerID with "Unknown" and removed duplicates. I also dropped unnecessary columns (InvoiceNo, StockCode) for further analysis.
  
3. **Feature Engineering:** I created new features such as Gross (calculated as Quantity * UnitPrice) and MonthYear (extracted from InvoiceDate) to enhance the analysis and visualization.

4. **Data Analysis:** I conducted various analyses such as calculating the total sales for each month, identifying the top customers, items, and selling countries, and analyzing the distribution of the gross amount.

5. **Data Visualization:** I used Matplotlib and Seaborn to create visualizations like line graphs, box plots, and heatmaps to present the analysis results in an understandable and insightful manner.

6. **Outlier Detection:** I used the Z-Score method to detect and remove outliers from the dataset, ensuring the accuracy of the analysis.

**The highlights and business impact of my solution include:**

1. **Sales Trends:** I identified patterns in sales trends over time, helping the business understand the seasonality and plan promotions accordingly.

2. **Customer Insights:** By identifying the top customers, the business can focus on providing personalized services and loyalty programs to retain them.

3. **Product Analysis:** The analysis of top-selling items can help in inventory management and marketing strategies.

4. **Geographic Insights:** Understanding the top selling countries can help the business tailor its products and services to specific markets.

5. **Outlier Detection:** Removing outliers ensures that the analysis is based on reliable data, leading to more accurate insights and decision-making.

Overall, the project provided valuable insights into the online retail business, enabling data-driven decisions to improve sales, customer satisfaction, and operational efficiency.



## Solution

**Data Preprocessing:** I started by loading the dataset and checking its structure and missing values. I handled missing CustomerID values by replacing them with "Unknown" and removed rows with missing Description values. This ensured data integrity for further analysis.

**Exploratory Data Analysis (EDA):** I explored the dataset to understand its characteristics. I calculated basic statistics, such as the number of unique transactions, products, and customers. This helped in gaining insights into the dataset's distribution and identifying potential areas of interest.

**Data Visualization:** I created visualizations to better understand the data. I plotted the distribution of gross amounts, sales trends by month, and the distribution of gross amounts without outliers using box plots. These visualizations provided insights into sales trends, customer behavior, and outlier detection.

**Statistical Analysis:** I performed statistical analysis to identify outliers using Z-scores. I removed outliers from the dataset to ensure that they did not skew the analysis and summary statistics.

**Business Impact:** The analysis provided insights into the online retail business, such as the busiest month and day of the week in terms of sales, top-selling items, and countries. These insights can help in making informed business decisions, such as optimizing inventory management, marketing strategies, and customer engagement.



## Approach
**Data Understanding:** Loaded the dataset using pandas and explored its structure and content. Identified missing values and duplicates.

**Data Cleaning:** Filled null CustomerIDs with "Unknown" and dropped rows with null Descriptions. Removed duplicate entries.

**Data Transformation:** Calculated the gross amount for each transaction by multiplying Quantity and UnitPrice. Created a new column 'MonthYear' to extract the month and year from the 'InvoiceDate' column.

**Exploratory Data Analysis (EDA):** Analyzed sales trends by month and day of the week. Identified top customers, items, and selling countries.

**Outlier Detection:** Calculated Z-scores for the 'Gross' column and removed outliers from the dataset.

**Data Visualization:** Used matplotlib and seaborn to create visualizations such as box plots and bar charts to represent the data distribution and trends.

**Summary and Conclusion:** Summarized the findings, highlighting key insights and business impacts.
