# 1. 네트워크(Network)
- [X] [OSI 7 Layers]()
- [X] [GET VS POST]()
- [X] [URI VS URL VS URN]()
- [X] [HTTP Status Code]()
- [ ] [HTTP VS HTTPS]()
- [X] [TCP VS UDP]()
- [X] [How does the Internet & Web work]()
- [X] [DNS]()
- [X] [Cookie VS Session]()
- [ ] [3 way handshake & 4 way handshake]()
- [ ] [공개키 암호화 VS 대칭키 암호화]()


## 네트워크 기타
- [ ] 라우팅 프로토콜
- [ ] OSPF
- [ ] stp
- [ ] err-Disable
- [ ] lsa
- [ ] 백본 구성
- [ ] 이더채널
- [ ] 백플레인
#

# 2. 운영체제(Operating System)
- [X] [Process VS Thread]()
- [ ] [스케줄러 / CPU 스케줄링]()
- [ ] [교착상태 / 문맥 교환]()
- [ ] [페이지 교체 알고리즘]()
- [ ] [메모리 관리]()
- [ ] [쉘 스크립트]()
#

# 3. 데이터베이스
## 1-1. 데이터베이스 개요
- 데이터베이스의 정의
- 파일 시스템과 데이터베이스의 차이
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
## 1-2. 데이터 모델 & 스키마
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
## 1-3. 정규화
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
## 1-4. 관계형 데이터베이스
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
## 1-5. SQL
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

## 1-6. SQL 2
- JOIN
- 서브쿼리
- 절차형 SQL
  - 절차형 SQL의 정의
  - 절차형 SQL의 종류
    - 저장 프로시저
    - 트리거
    - 사용자 정의 함수
    - 위 3요소 간의 차이점
## 1-7. 트랜잭션 & NoSQL
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
## 1-8. 기술 면접 정리
#

# 4. 자료구조
1. 자료구조 개요  
2. [Array & ArrayList & LinkedList](https://github.com/blackhoal/Study/blob/main/Coding%20Test/Theory/1.%20Array%20%26%20ArrayList%20%26%20LinkedList.md)
3. Stack / Queue / Deque  
4. [Graph / Tree / Heap](https://github.com/blackhoal/Study/blob/main/Coding%20Test/Theory/4.%20Graph%20%26Tree%20%26%20Heap.md)  
5. Hash Table
6. 문자열 처리  
7. 기술 면접 정리
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
