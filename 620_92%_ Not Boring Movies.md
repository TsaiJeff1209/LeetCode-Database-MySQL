# [620. Not Boring Movies](https://leetcode.com/problems/not-boring-movies/)

## 2018/5/23 beats 92.46 % of python3
### Spend 133 ms
```sql
# Write your MySQL query statement below
SELECT
    *
FROM
    cinema
WHERE
    id%2 = 1
    AND descripTion != 'boring'
ORDER BY
    rating DESC;

```
