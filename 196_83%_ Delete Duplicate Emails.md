# [196. Delete Duplicate Emails](https://leetcode.com/problems/delete-duplicate-emails/description/)

## 2018/5/24 beats 83.85 % of python3
### Spend 645 ms
```sql
# Write your MySQL query statement below
DELETE
    P1
FROM
    Person P1
JOIN
    Person P2
WHERE
    P1.Email = P2.Email
    AND P1.Id > P2.Id;
```
