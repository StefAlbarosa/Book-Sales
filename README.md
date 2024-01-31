# Book-Sales
Analysis of a bookstore's sales using python
This project was delivered as part of the openclassroom course. It is made in Python in a Jupyter notebook.
It is an exploratory analysis of sales of a bookstore, to target new areas of growth. 

There are two two files attached, one for cleaning and the other one for the analysis of the data.

DATA CLEANING: 
I replaced null values and searched for other inconsistencies. 

Instructions:
1.	Open folder: Cleaning.ipynb
2.	Run all cells.

Contents 
0.0.1  Libraries and Data preparation
0.1  Data Exploration
0.1.1  Customers:
0.1.2  Products:
0.1.3  Transactions
0.2  Merging
1  Task 1: Data Cleaning
1.1  Null Values
1.1.1  Replacing id_product null values
1.1.2  Replacing 0_2245 product pricing and category values.
1.2  Type conversion
1.3  Outliers
2  Saving cleaned data

DATA ANALYSIS
The analysis was based on the prices of products, gender and age of customers. The project also looked at the inequality distribution of purchases and clients, using the Lorenz Curve and Gini coefficient as well as correlations using three types of correlation methos such as Pearson Correlation Coefficient, Analysis of Variance (ANOVA) and Chi-Squared statistic.

INSTRUCTIONS:
1.	Open folder: Analysis.ipynb
2.	Run all cells.

Contents 
1  Task 2: Data Analysis
1.1  Indicators of central tendency and dispersion
1.1.1  Graphs of age, prices, categories
1.2  Concentration analysis: Lorenz curve
1.2.1  With Outliers
1.2.2  Without Outliers
2  Correlation Analyses
2.1  Gender-Category: Chi-squared
2.2  Gender- Price: ANOVA
2.3  Age - Purchase Frequency
2.4  Age-Basket total: Pierson correlation
2.5  Age - Price: Pierson correlation
2.6  Age-Total Spent
2.7  Age - Category: ANOVA
3  Adittional plots
3.1  Revenues per category per age
4  19 year Category 2 purchases
