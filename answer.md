1. 관계형 데이터베이스(RDBMS)와 비관계형 데이터베이스(NoSQL)의 장단점 비교

- 관계형 데이터베이스는 수정과 추가에 대해 복잡하고, 비관계형 데이터베이스는 편리하다.
- 관계형 데이터베이스는 수직적 관계로 파악하기 편리하고, 비관계형 데이터베이스는 수평적으로 조직되어 있어 파악하기 어렵다.

2. 트랜잭션(transaction)이란 무엇인가요?

- 트랜잭션이란 하나의 작업을 수행하기 위한 논리적인 작업 단위

3. MySQL에서 조인(join)의 역할은 무엇인가요? 다양한 join의 방식에 대해 설명해주세요.

- 조인이란 두 개의 테이블을 연결하여 하나의 결과로 출력하는 것입니다.
- join에는 inner join, outer join, left outer join, right outer join, self join 등이 있습니다.
- inner join은 두 개의 테이블을 조인할 때, 두 테이블 모두 지정한 열이 존재해야 한다.
- outer join은 한 테이블의 모든 행과 다른 테이블의 모든 행이 조인된다.
- right outer join과 left outer join은 두 개의 테이블이 존재할 때, 하나의 테이블에만 열이 존재해도 결과가 나온다.
- self join은 한 개의 테이블이 자기 자신을 join한다. 

4. MySQL에서 인덱스(index)란 무엇인가요?

- 인덱스란 빠르게 데이터를 찾기 위해 데이터에 특정 번호를 지정해주는 것.
