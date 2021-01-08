# ORDER BY
SELECT문에서 가져온 데이터를 정렬하는데 사용한다. 업무 처리상 매우 중요한 기능이다.
```sql
SELECT 컬럼1, 컬럼2 FROM 테이블 이름 ORDER BY 컬럼1 ASC, 컬럼2 DESC
-- 컬럼1은 오름차순 정렬, 컬럼2는 내림차순 정렬

SELECT first_name, last_name FROM customer ORDER BY first_name ASC, last_name DESC
SELECT first_name, last_name FROM customer ORDER BY 1 ASC, 2 DESC
-- ORDER BY문에 정수를 넣어도 결과는 동일
```
**ASC** = 오름차순    
**DESC** = 내림차순    
ORDER BY문은 기본적으로 오름차순(ASC)이다.
