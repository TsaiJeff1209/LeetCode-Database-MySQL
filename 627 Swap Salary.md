# [627. Swap Salary](https://leetcode.com/problems/swap-salary/description/)

## 2018/5/24 beats 85.56 % of python3
### Spend 301 ms
```sql
# Write your MySQL query statement below
UPDATE salary SET sex = CASE sex WHEN 'f' THEN 'm' ELSE 'f' END;
```
