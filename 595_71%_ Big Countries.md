# [595. Big Countries](https://leetcode.com/problems/big-countries/description/)

## 2018/5/23 beats 71.95 % of python3
### Spend 1620 ms
```sql
# Write your MySQL query statement below
SELECT
    name,population,area
FROM
    World
WHERE
    population > 25000000
    OR area > 3000000;
```
