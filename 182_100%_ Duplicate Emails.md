# [182. Duplicate Emails](https://leetcode.com/problems/duplicate-emails/description/)

## 2018/5/22 beats 100.00 % of python3
### Spend 181 ms
```sql
# Write your MySQL query statement below
SELECT
    Email
FROM
    Person
GROUP BY
    Email
HAVING
    COUNT(*)>1;
```
