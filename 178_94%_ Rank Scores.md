# [178. Rank Scores](https://leetcode.com/problems/rank-scores/description/)

## 2018/5/28 beats 94.31 % of python3
### Spend 597 ms
```sql
# Write your MySQL query statement below
SELECT
    s.Score,
    (SELECT COUNT(DISTINCT Score) FROM Scores WHERE Score >= s.Score) AS 'Rank'
FROM
    Scores s
ORDER BY
    Rank;
```
