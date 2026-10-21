# E-Commerce Sales Performance Analysis 
# - Please view as RAW - 

## Project goal
Analyze customer and order data to identify revenue drivers, top customers, and regional performance using SQL and Python/pandas.

## Tools
- SQL
- Python
- pandas

## Dataset
- `project_customers.csv`
- `project_orders.csv`

## Questions answered
1. How much revenue came from paid orders?
    4760

2. Which categories generated the most revenue?
    Tech with 2235
    Home with 1400

3. Which regions generated the most revenue?
    West with 1640
    East with 965

4. Who were the highest-spending customers?
    Customer 04 with 690
    Customer 07 with 620

5. What were the top paid orders?
    p.key  OrderID   CustomerID  Category Amount Status Cx Name          City  

    9       2010          104     Tech     420   paid   Customer 04       Seattle   
    18      2019          107     Tech     360   paid   Customer 07        Denver   
    6       2007          103     Tech     310   paid   Customer 03       Chicago   
    24      2025          109     Tech     280   paid   Customer 09       Phoenix   
    0       2001          101     Tech     240   paid   Customer 01      New York  

6. How did missing region values affect the analysis?
These 3 rows and all values were missing from the analysis due to the lack of region for question 3; once properly defined, there should be an additional $470.00 added to the appropriate region. 
    p.key  OrderID   CustomerID  Category Amount Status Cx Name          City  
    33      2034          112     Tech     230   paid   Customer 12      Portland   
    34      2035          112     Home     170   paid   Customer 12      Portland   
    35      2036          112    Books      70   paid   Customer 12      Portland 

## Cleaning / preparation
Ensured that all values were legible by computer for analysis
Accounted for appropriate statuses in queries
Isolated missing values to report and account for

## Key findings
Tech and Home products should remain at forefront of company focus
Portland offices to fill out the excel sheet fully and accurately for improved accuracy of reports and/or limitations on excel sheet to be implimented for minimization of user error.

## What I learned
Furthered understanding and nuance of syntax of Python, SQL, and pandas.
Practiced: sum(), mean(), groupby(), head(), ==, left join, sort_value(), bracket use vs. parentheses use 
