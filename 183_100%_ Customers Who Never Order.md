# [183. Customers Who Never Order](https://leetcode.com/problems/customers-who-never-order/description/)

## 2018/5/24 beats 100.00 % of python3
### Spend 233 ms
```sql
# Write your MySQL query statement below
SELECT
    Name AS 'Customers'
FROM
    Customers
WHERE
    Id NOT IN (SELECT CustomerId FROM orders);
```
