# WHERE
집합을 가져올 때 어떤 집합을 가져올 것인지에 대한 조건을 설정하는 절이다.
```sql
SELECT 컬럼1, 컬럼2 FROM 테이블 이름 WHERE 조건;

SELECT first_name, last_name FROM customer WHERE first_name = 'Jamie';
-- first_name이 Jamie인 행만 출력

= 같음
> ~보다 큰
< ~보다 작은
>= ~보다 크거나 같은
<= ~보다 작거나 같은
<>,!= ~가 아닌
AND 그리고
OR 혹은
```
