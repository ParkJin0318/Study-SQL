# IS NULL
특정 컬럼 혹은 값이 널 값인지 아닌지를 판단하는 연산자이다. IS NULL 혹은 IS NOT NULL로 널 유무를 판단한다.
```sql
SELECT * FROM 테이블 WHERE 컬럼1 = NULL;
-- NULL은 '=' 연산으로 비교할 수 없다.

SELECT * FROM 테이블 WHERE 컬럼1 IS NULL;
-- 컬럼1의 값이 널인 집합을 출력한다.

SELECT * FROM 테이블 WHERE 컬럼1 IS NOT NULL; 
-- 컬럼1의 값이 널이 아닌 집합을 출력한다.
```
