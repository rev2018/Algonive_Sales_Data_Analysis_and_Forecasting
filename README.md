- Sales Data Analysis System
This repository contains a comprehensive end-to-end data analysis project developed as part of an internship assignment. The objective of this project is to analyze customer sales data, derive insights from trends and patterns, and implement forecasting and customer segmentation techniques.

- Dataset
File Used: customer_shopping_data.csv

- Source
https://www.kaggle.com/datasets/mehmettahiraslan/customer-shopping-dataset?resource=download

- Size
Approximately 10,000 rows

- Key Columns
Customer ID, Gender, Category, Quantity, Price, Review, Date

- Features and Project Scope

1. Data Cleaning
	Standardized column names, converted datatypes, removed null values and duplicates, and created a derived sales column.
2. Exploratory Data Analysis (EDA)
	Generated summary statistics, analyzed sales by gender/category/month, identified trends, and detected outliers using Isolation Forest.
3.  Feature Engineering
	Extracted temporal features (year, month, day, week), created cohort labels for retention analysis, and performed sentiment scoring for reviews.
4. Forecasting	
Applied Facebook Prophet for monthly revenue forecasting, incorporating holidays and seasonality.
5. Inventory Optimization	
Recommended optimal monthly stock levels for each category using historical averages and variability.
6. Customer Segmentation
	Used KMeans clustering based on features like total sales, average basket size, and purchase frequency.
7. Cohort Analysis	
Conducted retention analysis by cohort using pivot tables and heatmaps.
8. Interactive Dashboard	Built with Plotly to visualize key performance indicators, sales trends, and category-wise insights.

- Technologies Used
Language: Python

- Libraries
1. Data manipulation: pandas, numpy
2. Visualization: matplotlib, seaborn, plotly
3. Machine Learning: sklearn, prophet
4. Text Analysis: nltk (if applicable)

- Key insights include:
1. Top-performing product categories and time periods
2. Retention trends across customer cohorts
3. Forecasted monthly revenue based on past data
4. Clustered customer segments with distinct characteristics
(Consider including screenshots of visualizations in the /images directory and referencing them here.)

- Academic Context
This project was completed as part of an academic internship. It simulates real-world business intelligence workflows, including:

1. Data preprocessing and transformation
2. Descriptive and predictive analytics
3. Customer behavior modeling
4. Dashboard-based reporting

- Author
  
 Reva Saxena
 
 GitHub: https://github.com/rev2018
 
 LinkedIn: https://www.linkedin.com/in/reva-saxena-61bb33342/

- Contributions and Feedback

Feel free to fork the repository, raise issues, or suggest improvements. Collaboration and feedback are welcomed.

