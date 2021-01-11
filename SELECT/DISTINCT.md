# SELECT DISTINCT
SELECT시 DISTINCT를 사용하면 중복값을 제외한 결과값이 출력된다.   
즉, 같은 결과의 행이라면 중복을 제거할 수 있다.
```sql
SELECT DISTINCT 컬럼1 FROM 테이블 이름
-- 컬럼1의 중복값 존재시 컬럼1을 기준으로 중복값 제거 후 하나씩만 출력

SELECT DISTINCT 컬럼1, 컬럼2 FROM 테이블 이름
-- 컬럼1+컬럼2의 중복값 존재시 컬럼1, 컬럼2을 기준으로 중복값 제거 후 하나씩만 출력

SELECT DISTINCT ON (컬럼1) 컬럼1, 컬럼2 FROM 테이블 이름 ORDER BY 컬럼1, 컬럼2
-- 컬럼1을 기준으로 중복값 제거 후 오름차순 정렬, 컬럼2는 오른차순 정렬 후 첫번째 값 하나만 출력
```
