# JOIN
2개 이상의 테이블에 있는 정보 중 사용자가 필요한 집합에 맞게 가상의 테이블처럼 만들어 결과를 보여주는 것이다.

### Join의 종류
- **INNER JOIN**: 특정 컬럼을 기준으로 정확히 매칭된 집합을 출력한다.
- **OUTER JOIN**: 특정 컬럼을 기준으로 매칭된 집합을 출력하지만,    
한쪽의 집합은 모두 출력하고, 다른 한쪽의 집합은 매칭되는 컬럼의 값만을 출력한다.
- **SELF JOIN**: 동일한 테이블끼리의 특정 컬럼을 기준으로 매칭되는 집합을 출력한다.
- **FULL OUTER JOIN**: _INNNER_, _LEFT OUTTER_, _RIGHT OUTER_ JOIN 집합을 모두 출력한다.
- **CROSS JOIN**: Cartesian Product이라고 하며 JOIN되는 두 테이블의 곱집합을 반환한다.
- **NATURAL JOIN**: 특정 테이블의 같은 이름을 가진 컬럼 간의 JOIN 집합을 출력한다.
