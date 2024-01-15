# Credit-Card-Spending-Analysis

**Overview**

This project involves an Exploratory Data Analysis (EDA) of credit card transactions using Microsoft SQL Server. The analysis aims to understand spending patterns, identify trends, and address specific business questions related to credit card transactions.

**Project Contents**

**Data Source:**

The raw data is stored in a SQL Server database.
Ensure you have the necessary permissions to access and analyze the data.
Analysis Steps:

The EDA was performed using SQL queries to extract insights from the credit card transactions.
SQL Queries:

SQL queries were executed against the SQL Server database for various analyses.
Queries are available in the sql_queries directory.
Queries Overview:

1. top_cities_highest_spends.sql: 
Prints the top 5 cities with the highest spends and their percentage contribution to total credit card spends.

2. highest_spend_month_card_type.sql: 
Prints the highest spend month and amount spent for each card type.

3. cumulative_spends_card_type.sql: 
Prints transaction details for each card type when cumulative spends reach $1,000,000.

4. lowest_percentage_spend_gold_card.sql: 
Finds the city with the lowest percentage spend for the Gold card type.

5. city_expense_types_comparison.sql: 
Prints three columns: city, highest_expense_type, lowest_expense_type.

6. female_spend_percentage_by_expense_type.sql: 
Finds the percentage contribution of spends by females for each expense type.

7. highest_growth_card_expense_month_over_month.sql: 
Finds the card and expense type combination with the highest month-over-month growth in Jan-2014.

8. weekend_highest_spend_city_ratio.sql: 
Finds the city with the highest total spend to total number of transactions ratio during weekends.

9. least_days_to_500th_transaction.sql:
Finds the city that took the least number of days to reach its 500th transaction after the first transaction.
Instructions

Execute the SQL queries provided in the sql_queries directory against your SQL Server database.

Future Steps
Discuss potential next steps or areas for further investigation based on the insights gained from the SQL analysis.



