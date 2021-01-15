# LIMIT
특정 집합을 출력 시 출력하는 행의 수를 한정하는 역할을 한다. 부분 범위 처리시 사용된다.
PostgreSQL, MySQL 등에서 지원한다.
```sql
SELECT * FROM 테이블 이름 LIMIT 행의 수;
-- 출력하는 행의 수를 지정하여 조회

SELECT * FROM 테이블 이름 LIMIT 행의 수 OFFSET 시작위치;
-- 출력하는 행의 수를 지정하면서 시작위치를 지정하여 조회

SELECT FILM_ID, TITLE, RELEASE_YEAR FROM FILM ORDER BY FILM_ID LIMIT 5;

SELECT FILM_ID, TITLE, RELEASE_YEAR FROM FILM ORDER BY FILM_ID LIMIT 4 OFFSET 3;
```
