# [181. Employees Earning More Than Their Managers](https://leetcode.com/problems/employees-earning-more-than-their-managers/description/)

## 2018/5/24 beats 100.00 % of python3
### Spend 300 ms
```sql
# Write your MySQL query statement below
SELECT
    a.name 'Employee'
FROM
    Employee a,Employee b
WHERE
    a.ManagerId = b.Id
    AND a.Salary > b.Salary;
```
