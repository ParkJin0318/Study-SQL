# INNER JOIN - 교집합    
특정 컬럼을 기준로 정확히 매칭된 집합을 출력한다. INNER JOIN은 대표적인 조인의 종류이다.
```sql
SELECT 
  A.ID ID_A,
  A.FLUIT FLUIT_A,
  B.ID ID_B,
  B.FLUIT FLUIT_B
FROM
  BASKET_A A
INNER JOIN
  BASKET_B B
ON
  A.FLUIT = B.FLUIT;
-- BASKET_A 테이블과 BASKET_B을 FLUIT 컬럼 기준으로 조인한다.
```
