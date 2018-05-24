# [595. Big Countries](https://leetcode.com/problems/big-countries/description/)

## 2018/5/23 beats 71.95 % of python3
### Spend 1620 ms
```sql
# Write your MySQL query statement below
SELECT name,population,area FROM World
WHERE area > 3000000
OR population > 25000000;
```
