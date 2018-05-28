# [184. Department Highest Salary](https://leetcode.com/problems/department-highest-salary/description/)

## 2018/5/28 beats 100.00 % of python3
### Spend 287 ms
```sql
# Write your MySQL query statement below
SELECT
    d.Name AS 'Department',
    e.Name AS 'Employee',
    e.Salary AS 'Salary'
FROM
    Employee e, Department d,
    (SELECT DepartmentId, MAX(Salary) AS 'Salary' FROM Employee GROUP BY DepartmentId) AS h
WHERE
    e.Salary = h.Salary
    AND e.DepartmentId = h.DepartmentId
    AND e.DepartmentId = d.Id;
```
