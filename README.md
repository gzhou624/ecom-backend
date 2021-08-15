#### Ecom backend
This simple e-ecommerce backend allows you to manage the employee, customer, login, product and purchase info.  
Technologies used:
1. Java
2. Swing
3. mysql


Please see the document in the resources folder for screenshots.  
Mysql database is used to store data.
```
mysql> show tables;
+--------------+
| Tables       |
+--------------+
| customer     |
| employee     |
| login        |
| product      |
| purchaseinfo |
+--------------+
5 rows in set (0.00 sec)
```

sample data in customer table   
```
mysql> select * from customer;
+--------+--------------+--------------+------------+
| userId | customerName | phoneNumber  | address    |
+--------+--------------+--------------+------------+
| sara   | sara         | +12121112222 | California |
| deba   | Chloe        | +12121112222 | New York   |
+--------+--------------+--------------+------------+
```
sample data in product table
```
mysql> select * from product where productName like '%Album%';
+-----------+------------------+-------+----------+
| productId | productName      | price | quantity |
+-----------+------------------+-------+----------+
|     00006 | Black Pink Album | 20.00 |       10 |
|     00009 | Album #1         | 25.00 |        9 |
|     00010 | Album #2         | 25.00 |       20 |
+-----------+------------------+-------+----------+
3 rows in set (0.00 sec)
```
