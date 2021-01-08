# SELECT

SQL에서 SELECT문은 일반적으로 테이블에 저장된 데이터를 가져오는데 쓰인다. SQL에서 가장 많이 쓰이는 문장이다.

```sql
SELECT 컬럼1, 컬럼2 FROM 테이블 이름;
SELECT * FROM 테이블 이름;

SELECT first_name, last_name, email FROM customer;
SELECT * FROM customer;
```

**SELECT** -> 추출 대상 컬럼, 모든 컬럼을 조회하려면 *   
**FROM** -> 추출 대상 테이블   
끝은 항상 세미 콜론으로 끝남


# ALIAS

두 개 이상의 테이블을 이용할 때 사용한다.

```sql
SELECT 테이블 별칭.컬럼1, 테이블 별칭.컬럼2 FROM 테이블 이름 테이블 별칭;

SELECT A.first_name, A.last_name, A.email FROM customer A;
```  
코드의 가독성 증가 및 SQL 성능 향상   
데이터 베이스의 최적화 도구인 옵티마이저가 가장 빠르고, 가장 저비용으로 실행하는데 도움을 줌
