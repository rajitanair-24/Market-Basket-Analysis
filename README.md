# Market Basket Analysis
Market Basket Analysis (MBA) is a data mining technique used by retailers to understand the purchasing patterns of customers. By analysing transactional data, retailers can uncover associations between items frequently purchased together, identify popular combinations, and make informed decisions about product placement, target promotions and so on. 

# Objective:
The objective of this project is to analyse the transaction data to gain insight into customer behaviour, popular items, and pattern in sales over time.

# Tools Used:
Python programming language and libraries like pandas for data manipulation, numpy for numerical computations, matlplotlib and seaborn for visualization, mlxtend for association rule mining.

# Dataset Exploration:
The initial dataset has no missing values.
The dataset contains columns: Transaction, Item, date_time, period_day, weekday_weekend, month, hour.

# Data Preprocessing:
The date_time column is converted to datetime format to facilitate further analysis. Additional columns are derived from this date_time column, including date, month, hour and weekday.
The item column is standardized by converting all items to lowercase and removing whitespaces for ease of further analysis.

# Data Analysis:
The analysis starts with EDA. This includes bar plots to visualize the top 10 items sold and the distribution of transactions across month and weekdays.
Association rule mining is performed using the Apriori algorithm to identify frequent itemsets and association rules from the transaction data.
	Association rule mining is performed using the Apriori algorithm to identify frequent itemsets and association rules from the transaction data.
