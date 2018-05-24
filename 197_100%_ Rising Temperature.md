# [197. Rising Temperature](https://leetcode.com/problems/rising-temperature/description/)

## 2018/5/24 beats 100.00 % of python3
### Spend 328 ms
```sql
# Write your MySQL query statement below
SELECT
    a.Id
FROM
    Weather a, Weather b
WHERE
    a.Temperature > b.Temperature
    AND DATEDIFF(a.RecordDate,b.RecordDate) = 1;
```
