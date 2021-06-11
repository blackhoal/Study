# 1. 데이터베이스
## ① 데이터베이스 개요
- 데이터베이스의 정의
- 파일 시스템과 데이터베이스의 차이
- 데이터베이스의 필요성
  - 종속성
  - 중복성
- 데이터베이스의 정의
  - 통합 데이터
  - 저장 데이터
  - 운영 데이터
  - 공용 데이터
- 데이터베이스의 특징
  - 실시간 접근성
  - 계속적인 변화
  - 동시 공용
  - 내용에 의한 참조
- 데이터베이스의 구성요소
  - 개체
  - 속성
  - 관계
## ② 데이터 모델 & 스키마
- 데이터 모델 3단계
  - 개념적 데이터 모델
  - 논리적 데이터 모델
  - 물리적 데이터 모델(중요도가 낮으므로 개념 정도만 인지)
- 데이터 모델의 3요소
  - 구조
  - 연산
  - 제약조건
- 스키마
  - 스키마의 정의
  - 스키마의 종류
    - 개념 스키마
    - 외부 스키마
    - 내부 스키마
## ③ 정규화
- 정규화란?
- 정규화의 목적
- 이상현상
  - 이상현상이란?
  - 이상현상의 종류
    - 삽입 이상
    - 삭제 이상
    - 갱신 이상
- 정규화 과정(3NF까지만 상세하게 / 예시를 통해 1NF ~ 3NF까지의 과정을 적으면 좋을것 같습니다 / 이후 과정은 조건 정도만 인지)
  - 1NF : 도메인이 원자값
  - 2NF : 부분적 함수 종속 제거
  - 3NF : 이행적 함수 종속 제거
  - BCNF : 결정자 중 후보키가 아닌 것 제거
  - 4NF : 다치 종속 제거
  - 5NF : 조인 종속 제거
## ④ 관계형 데이터베이스
- 관계형 데이터베이스란?
- 관계형 데이터베이스 용어
  - 속성
  - 도메인
  - 튜플
  - 릴레이션
  - 차수
  - 카디널리티
  - NULL
- 관계형 데이터베이스의 제약조건
  - Key
    - 슈퍼키
    - 후보키
    - 기본키
    - 대체키
    - 외래키
  - 무결성 제약조건
    - 개체 무결성
    - 참조 무결성
    - 도메인 무결성
## ⑤ SQL
- SQL의 정의(Structured Query Language)
- SQL 종류
  - DDL 정의 및 종류
    - CREATE
    - ALTER
    - DROP
  - DML 정의 및 종류
    - SELECT
    - INSERT
    - DELETE
    - UPDATE
  - DCL 정의 및 종류
    - GRANT
    - REVOKE
- 뷰
  - 뷰의 정의
  - 뷰의 사용 목적
  - 뷰의 장점 및 단점
- 절차형 SQL
  - 절차형 SQL의 정의
  - 절차형 SQL의 종류
    - 저장 프로시저
    - 트리거
    - 사용자 정의 함수
    - 위 3요소 간의 차이점
## ⑥ 트랜잭션 & NoSQL
- 트랜잭션의 정의
- 트랜잭션의 특성(ACID)
  - Atomicity
  - Consistency
  - Isolation
  - Durability
- 트랜잭션 제어어
  - COMMIT
  - ROLLBACK
  - SAVEPOINT
- NoSQL
  - NoSQL의 정의
  - RDBMS와 NoSQL의 차이점
## ⑦ 기술 면접 정리
#

# 2. 운영체제
## ① 운영체제 개요
## ② 프로세스 / 스레드
## ③ 스케줄러 / CPU 스케줄링
## ④ 교착상태 / 문맥 교환
## ⑤ 페이지 교체 알고리즘
## ⑥ 메모리 관리
## ⑦ 쉘 스크립트
## ⑧ 기술 면접 정리
#

# 3. 네트워크
## ① 네트워크 개요
## ② 웹 동작 방식
## ③ OSI 7계층
## ④ 프로토콜
- TCP/IP
- TCP VS UDP
- HTTP VS HTTPS
## ⑤ 기술 면접 정리
#

# 4. 자료구조
## 자료구조 개요  
## Array / LinkedList  
## Stack / Queue / Deque  
## Graph / Tree / Heap  
## Hash Table
## 문자열 처리  
## 기술 면접 정리
#

# ⑤ 알고리즘
01. 알고리즘 개요
02. 시간 복잡도 & 공간 복잡도
03. 시간 복잡도가 O(n^2)인 정렬 - 삽입 정렬 / 선택 정렬 / 거품 정렬
04. 시간 복잡도가 O(nlogn)인 정렬 - 퀵 정렬 / 병합 정렬 / 힙 정렬
05. 순차 탐색 / 이진 탐색
06. 완전 탐색(브루트포스)
07. 탐욕 알고리즘(그리디)
08. 동적계획법(다이나믹 프로그래밍)
09. DFS / BFS
10. 다익스트라 알고리즘
#

# ⑥ Conference
[자료 1 - CS 1](https://github.com/JaeYeopHan/Interview_Question_for_Beginner)  
[자료 2 - CS 2](https://gyoogle.dev/blog/)  
[자료 3 - 개발직 면접 준비](https://www.notion.so/Guide-b0c0d2c343f24ba5bb274e21630117b2#f31d028355474f3eba3c3039755fc9ee)  
[자료 4 - 백엔드 개발자 로드맵](https://roadmap.sh/backend)  
