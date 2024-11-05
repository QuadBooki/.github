# 인하공전 시스템 분석 설계 도서관리 프로젝트
인하공업전문대학 시분설 도서관리 프로젝트입니다.


### 🙌 프로젝트 소개 
- 회원이 책을 대여하고, 관리자가 책을 관리하는 웹페이지

### 프로젝트 기술 요약 
- 회원 가입 기술 : id, pw, 이름, 생년월일, 전화번호를 받는다.
- 회원 기술
     1. 회원은 정보를 수정할 수 있다.
     2. 회원은 정보를 탈퇴할 수 있다.
     3. 회원은 정해진 id, pw로 로그인할 수 있다.
     4. 회원은 책을 최대 3권까지 대여할 수 있다.

- 도서 기술 : 도서는 제목, 저자, 사진, ISBN을 주요 테이블로 설정한다.
     1. 도서는 외부 도서관 API로 등록한다.
     2. 모든 도서는 1권만 있다.
     3. 중복된 ISBN을 가진 도서는 등록될 수 없다.

 - 대여 기술
     1. 대여기간은 도서 대여 기준 2주로 지정한다.
     2. 회원이 대여 신청을 하면 별도의 승인없이 바로 승인되도록 한다.
     3. 대출 정보는 전부 자동으로 입력되도록 한다.

  - 관리자 기술
     1. 관리자는 회원 정보를 검색 및 삭제할 수 있다.
     2. 관리자는 도서를 등록, 조회 및 삭제할 수 있다.
     3. 관리자는 회원이 빌린 도서의 대출 기한을 연장할 수 있다.
     4. 관리자는 회원이 대출 연체 시 대여의 제약을 걸 수 있다.
     5. 관리자는 도서 대출에 문제가 있을 시 도서 대여를 취소할 수 있다.
  

### 프로젝트 기간
 - 2024.8.27 ~ 2024.12.02
   
### 세부 일정
- 2024.09.24 : 프로젝트 계획 수립
- 2024.09.25 ~ 2024.10.08 : 프로젝트 기획서 작성(7월 20일 전 까지 최종 점검 후 발송)
- 2024.10.09 ~ 2024.10.21 : 테이블 구조 정의 및 CRUD 설계 완료
- 2024.10.22 ~ 2024.11.04 : 프론트 구현 완료
- 2024.11.05 ~ 2024.11.26 : 백엔드 구현 완료
- 2024.11.27 ~ 2024.12.02 : 테스트 및 보고서 완료.

   
### 👥 멤버 구성
👨🏻‍💻 박민제 : Back-end, Server, DB 
👨🏻‍💻 김태이 : Back_end, DB, Server
👨🏻‍💻 이현준 : Front-end, Back-end PM
👨🏻‍💻 김나희 : Front-end, Design, PM



 ----------------------------------------------------------------------

 ### ⚒️ 언어 및 구조

 언어
 - JAVA, HTML, CSS, JavaScript

프레임워크
- Spring Boot

tools
- IntelliJ IDEA

DB
- mySql