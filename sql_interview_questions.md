# Sample SQL Interview Questions - Paired Programming


Here are some of my favorite SQL-related questions to challenge thinking on SQL problems. There's a few easy `SELECT *` related questions to warm people up, but there are some difficult questions in there as well.

### The Schema
```
SQL Questions - based on available database (mySQL)

No partition functions available
Be mindful of substring vs. substr
Also note LIMIT vs. TOP differences
/*
CoderPad provides a basic SQL sandbox with the following schema.
You can also use commands like `show tables` and `desc employees`

employees                             projects
+---------------+---------+           +---------------+---------+
| id            | int     |<----+  +->| id            | int     |
| first_name    | varchar |     |  |  | title         | varchar |
| last_name     | varchar |     |  |  | start_date    | date    |
| salary        | int     |     |  |  | end_date      | date    |
| department_id | int     |--+  |  |  | budget        | int     |
+---------------+---------+  |  |  |  +---------------+---------+
                             |  |  |
departments                  |  |  |  employees_projects
+---------------+---------+  |  |  |  +---------------+---------+
| id            | int     |<-+  |  +--| project_id    | int     |
| name          | varchar |     +-----| employee_id   | int     |
+---------------+---------+           +---------------+---------+


+------------------+---------------+
| product_id       | int(11)       |
| store_id         | int(11)       |
| customer_id      | int(11)       |
| promotion_id     | int(11)       |
| store_sales      | decimal(10,4) |
| store_cost       | decimal(10,4) |
| units_sold       | decimal(10,4) |
| transaction_date | date          |
+------------------+---------------+


*/
```

### The Questions:

1. Whats the average salary?
2. How many people per salary?
3. And how many people above 50k
4. total sales?
5. total profit?
6. total profit excluding Promotions?
7. stores over xxx profit / under xxx profit?
8. Salary - certain portion goes to 401k?
9. profile is for stores over 50k salary (.70% Takehome) (.30%  401k)?
10. profile is for stores under <50k Salary?
11. Total units sold?
12. any product with no units sold?
13. histogram for units sold?
14. stores that sell less than 3 units for 80% or more of sales?
15. Show by project title, the number of unique departments
16. What's the 2nd highest salary from employee? (without creating tables)
17. which projects are over budget and by how much?
18. Who has the highest salary by department (single query)
19. Create a rolling (sum of sales ) by day table of sales per dept
20. Create a table of dates by rows and any 5 brandname as columns (without a pivot function), sum value is store_sales
21. Create a histogram (table) on the number of sales by day, put in 5 bins
22. Whats the % of promoted sales vs. non ->
23. Whats the most profitable transaction?
24. Which store has sold items for 7 consecutitive days?
25. Whats the longest day-to-day streak a store has sold items?
26. Which stores sell both `Tri-State` and `Top Measure` Brands? (use `SALES` and `Products` tables)
27. Who are the top 3 customers by education brand?
28. Give the common statistics of the customers age. Are there outliers? How do you find them with SQL?
29. Which product has the greatest diversity of customers (open ended)
30. What's the sales by month?
31. Whats the change in sales by month?
32. Which store has the most drops in sales month to month?
33. Which state has the highest expected sales for next year? (open ended)

---
