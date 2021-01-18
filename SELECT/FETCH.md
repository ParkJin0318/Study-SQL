# FETCH
특정 집합을 출력 시 출력하는 행의 수를 한정하는 역할을 한다. 부분 범위 처리시 사용된다.
```sql
SELECT * FROM 테이블 이름 FETCH FIRST 행의 수 ROW ONLY;
-- 출력하는 행의 수를 지정한다. N을 입력하지 않으면 단 한 건만 출력한다.

SELECT * FROM 테이블 이름 OFFSET 시작위치 ROWS FETCH FIRST 행의 수 ROW ONLY;
-- 출력하는 행의 수를 지정하면서 시작위치를 지정한다. OFFSET N값의 시작위치는 0이다.

SELECT FILM_ID, TITLE FROM FILM ORDER BY TITLE FETCH FIRST ROW ONLY;
SELECT FILM_ID, TITLE FROM FILM ORDER BY TITLE FETCH FIRST 1 ROW ONLY;
-- TITLE로 정렬한 집합 중 최초의 단 한 건의 행만 리턴한다.

SELECT * FROM 테이블 이름 OFFSET 5 ROWS FETCH FIRST 5 ROW ONLY;
-- TITLE로 정렬한 집합 중에서 6번째 행부터 5건의 행을 리턴한다.
```
