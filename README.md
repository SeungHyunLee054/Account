# Zerobase Practice Project 01 Account
## 사용한 기능
### Tool
1. IntelliJ
### database
1. H2 Database
### plugins
1. Spring boot
2. Gradle
3. Junit5
4. JPA
5. Redis
6. Mockito
7. Lombok
## 제공하는 기능(API)
### 계좌(Account) 관련 기능
1. 계좌 생성
2. 계좌 해지
3. 계좌 확인

### 거래(Transaction) 관련 기능
1. 잔액 사용(거래 생성)
2. 잔액 사용 취소(거래 취소)
3. 거래 확인

### 사용자 관련 기능
구현 간소화를 위해 DB에 데이터 자동 입력 구현

-----
### 배운점
* Jpa를 활용하여 sql문을 생성하는 것
* redis를 이용하여 Lock을 활용해서 동시성 이슈 방지
* Mockito와 Junit5을 이용해서 테스트 케이스 작성
* mvc 구조 사용법
* 커스텀 예외를 만들어서 처리하기
* enum 클래스를 활용하는 법
* entity와 dto를 활용하는 법
