# LIKE
```sql
SELECT * FROM 테이블 WHERE 컬럼1 LIKE 특정패턴;
-- 컬럼1의 값이 특정패턴과 유사한 집합을 출력한다.

SELECT FIRST_NAME, LAST_NAME FROM CUSTOMER WHERE FIRST_NAME LIKE 'Jen%';
-- FIRST_NAME이 'Jen'으로 시작하는 집합을 출력한다.

SELECT FIRST_NAME, LAST_NAME FROM CUSTOMER WHERE FIRST_NAME NOT LIKE 'Jen%';
-- FIRST_NAME이 'Jen'으로 시작하지 읺는 집합을 출력한다.

'FOO' LIKE 'FOO' -- true, 문자열 값이 동일
'FOO' LIKE 'F%' -- true, 문자열의 시작 값이 동일
'FOO' LIKE '_O_' -- true, 문자열의 자리수와 중간 값이 동일
'BAR' LIKE 'B_' -- false, 문자열의 길이가 같지 않음
```
