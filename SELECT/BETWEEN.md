# BETWEEN
특정 집합에서 어떠한 컬럼의 값이 특정 범위안에 들어가는 집합을 출력하는 연산자이다.
```sql
SELECT * FROM 테이블 WHERE 컬럼1 BETWEEN 값1 AND 값2;
SELECT * FROM 테이블 WHERE 컬럼1 >= 값1 AND 컬럼1 <= 값2;
-- 컬럼1의 값이 값1과 값2 사이에 있는 집합을 출력한다.

SELECT * FROM 테이블 WHERE 컬럼1 NOT BETWEEN 값1 AND 값2;
SELECT * FROM 테이블 WHERE 컬럼1 < 값1 OR 컬럼1 > 값2;
-- 컬럼1의 값이 값1과 값2 사이에 있지 않은 값을 출력한다.
```
