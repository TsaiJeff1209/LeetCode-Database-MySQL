# [175. Combine Two Tables](https://leetcode.com/problems/combine-two-tables/)

## 2018/5/22 beats 100.00 % of python3
### Spend 217 ms
```sql
# Write your MySQL query statement below
SELECT FirstName, LastName, City, State
FROM Person
LEFT JOIN Address
ON  Person.PersonId = Address.PersonId;
```
