# [596. Classes More Than 5 Students](https://leetcode.com/problems/classes-more-than-5-students/description/)

## 2018/5/23 beats 79.55 % of python3
### Spend 1394  ms
```sql
# Write your MySQL query statement below
SELECT
    class
FROM
    courses
GROUP BY
    class
HAVING
    COUNT(DISTINCT student) >= 5;
```
