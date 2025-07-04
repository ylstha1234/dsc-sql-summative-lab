# SQL Analysis & Visualization 

# Overview

This lab has two parts:
Part 1: Guided SQL Queries
  Analyze customer and product data from a miniature model company using SQL and create visualizations to support business insights.
Part 2: Exploratory Analysis with SQL
  Explore an IMDB movie dataset (2010–2019), identify trends, formulate a business question, and assess data quality issues.
  
# Part 1: Guided SQL Queries

1. Connected to 'data.sqlite'.
2. Queried customers by region, credit limits, and purchase behavior.
3. Visualized average credit by state, top customers, and product line sales.
4. Used joins, aggregation, subqueries, and filters.
5. Reflected on query and visualization choices.
   
# Findings

1. California customers with high credit limits are prime for promotions.  
2. States vary widely in average credit limits, impacting inventory strategy.  
3. Top customers contribute significantly to revenue.  
4. Some product lines have many products but fewer orders, indicating potential overstock.
   
# Recommendations

1. Target high-credit California customers for new product promotions.  
2. Allocate inventory based on state purchasing power.  
3. Focus marketing on top customers and popular product lines.  
4. Review inventory for underperforming product lines.

# Part 2: Exploratory Analysis with SQL

1. Explored `im.db` movie dataset (2010–2019).
2. Investigated genres, ratings, runtimes, and personnel data.
3. Formulated a business question based on identified trends.
4. Noted data cleaning needs such as null values and inconsistencies.
5. Prepared a short slide presentation summarizing the work.

# Findings

1. Certain genres show higher average ratings.  
2. Release year impacts movie popularity and runtime trends.  
3. Data contains nulls in key fields requiring attention.
   
# Recommendations

1. Focus analysis on well-populated, high-quality data subsets.  
2. Address missing data before predictive modeling.  
3. Explore genre-specific marketing or production strategies.

# Tools Used

1. SQLite (sqlite3)  
2. Python (pandas, matplotlib, seaborn)  
3. Jupyter Notebook 

# Goals

1. Write complex SQL queries to answer business needs.  
2. Visualize data for clear communication.  
3. Develop data-driven business questions.  
4. Identify and acknowledge data quality issues.
   
# Conclusion

This lab provided hands-on experience in querying real-world datasets using SQL, interpreting results, and communicating insights through visualizations. We can practiced translating business problems into data questions, exploring data quality issues, and making actionable recommendations.
