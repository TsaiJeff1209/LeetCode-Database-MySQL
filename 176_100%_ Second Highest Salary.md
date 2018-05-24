# [176. Second Highest Salary](https://leetcode.com/problems/second-highest-salary/description/)

## 2018/5/24 beats 100.00 % of python3
### Spend 121 ms
```sql
# Write your MySQL query statement below
SELECT (
    SELECT DISTINCT Salary
    FROM Employee
    ORDER BY Salary DESC
    LIMIT 1 OFFSET 1
    ) AS 'SecondHighestSalary';
```
