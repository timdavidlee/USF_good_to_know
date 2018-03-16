## SQL Whiteboard Questions

### Whiteboard Scenario #1 Blogging Platform

```
Given a Posting Table:
Id 
User_Id
Post_type_id
Date
Content
Parent_Id

```

|id|User_id|Post_type_id|Date|Content|Parent_id|
|---|----|----|---|---|---|
|1001|1|1|1/1/2017|~|NULL|
|1002|2|1|1/1/2017|~|NULL|
|1003|3|2|1/1/2017|~|1001|

1. How to get total posts by type?
2. How would you make a histogram of posts?
3. Write a query to delete duplicate rows in the posting table
4. How would you find popular posts?
5. how would you identify users that excessively comment on their own posts? 
6. How to determine the most popular posts?
7. How would you profile user activity? How would you compare similar users?

---

### Whiteboard Scenario #2 User Activity

```
Given a Activity Table:
Id 
User_Id
Event_Type_id
Date
Parent_Id
```

|id|User_id|Post_type_id|Date|Content|Parent_id|
|---|----|----|---|---|---|
|10001|1|1|1/1/2017|~|NULL|
|10002|2|1|1/1/2017|~|NULL|
|10003|3|2|1/1/2017|~|10001|

|id|Event Name|
|---|------|
|1|View ad|
|2|click|
|3|download|
|4|Usage|

1. How many of each type of event is there?
2. How would you determine the biggest (event) barrier to installation?
3. Considering real-life user behavior (with ads), how would you determine the % ad conversion? (% of ads that lead to clicks?
4. What can go wrong in the installation processes? Name 2 How would you write a query to check each of those 2 testsf
5. Whats the breakdown of view→ click / per day?
6. Biggest obstacle in funnel
7. How to tell if funnel is broken

---

### Whiteboard Scenario #3 Warehouse
```
Given a Orders and Inventory Table:

Orders
------
Id
line_id
Product_id
Quantity
Date
Customers_id
Sales_price

Inventory (stocking and shipment)
------------
Id
Product_id
Quantity
Date
Transaction_type

Product_Table
------------
Id
Name
List_price
```


1. Which month is the busiest for sales?
2. How would you determine if there is enough inventory to ship an order on specific date?
3. How would you identify products sold at a loss?
4. How would you identify Customers getting preferential discounts?

---

### Whiteboard Scenario #4 Shipping Company

```
Given a Customer Table
----------------------
Id 
Customer_Name
Creation_date
Update_date
Industry

Sales Table
-----------
Id
Invoice
Date
Product_id
Customer_id
Units
Price
```

1. How would you get a distinct list of customers?
2. Given that customers change, how would you generate “total sales per customer”?
3. How would you check to ensure customers are not double charged?
4. How would you identify which customers bought the largest variety of products?
5. Think of a way of categorizing your customers

---

### Whiteboard Scenario #5 Real Estate Company 

```
Given a Posting Table
---------------------
Id
User_id
Date
Building_ID
Asking price
Region_id

Building Table
--------------
Id
Building_type
Bedroom
Sqft
Pool
Yard
Lot size


Sales Table
-----------
Id
User_id
Post_id
Date
Offer_price
Closed
Final_offer
```

1. How would you find total posts?
2. What region has the most posts?
3. Which building type has the highest average asking price?
4. What whats the average asking price of having a pool vs. not?
5. Show me posts with no offers
6. Average offer price per bedroom?
7. How would you find out most dense region of posts?
8. What other features would be good to know? 

A user might be trying to generate more activity for his own benefit (how would you find this fraud)




