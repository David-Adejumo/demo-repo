# Demo 
CTE FUNCTION 

WITH logs AS (
  SELECT DISTINCT *
  FROM health.user_logs
  )
SELECT COUNT(*)
FROM logs;

Usual Function
SELECT COUNT(*)
FROM (
  SELECT DISTINCT *
  FROM health.user_logs
  ) AS subquery 
  ;
