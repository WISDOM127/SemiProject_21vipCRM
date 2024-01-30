# SemiProject_21vipCRM
- 국비 세미 프로젝트<br/>
- CRM을 바탕으로 한 VIP 고객관리 및 바우처 생성 프로그램<br/>
- 개발 기간 : 2023.11~12

# 나의 역할
Oracle Database 생성 및 관리<br/>
Oracle 프리티어 인스턴스 생성 및 활용<br/>
고객 관리(Customer) / 바우처 관리(Voucher&VoucherC) 파트의 프론트&백엔드 개발<br/>

# 기술스택
Java 11<br/>
SpringBoot<br/>
Spring Data JPA, Querydsl<br/>
Spring Security<br/>
Oracle<br/>
AWS(Light sail)<br/>
tomcat9 배포<br/>


# 프로젝트 주요기능
<h6>  ✔️고객 관리 / 바우처 관리 파트</h6>
고객 CRUD<br/>
랜덤 기능 통한 고객번호 생성<br/>
고객별 바우처 발급<br/>
고객별 소유 바우처 리스트 조회<br/>
특이사항 메모 기능<br/>
문자메시지 발송<br/>
바우처 CRUD<br/>
바우처 관리<br/>
특정 코드를 암호화시킨 일련번호를 가지는 바우처 생성 프로그램<br/>
UUID 를 통한 암호화된 난수 생성 및 주입<br/>
조건에 따른 검색 기능<br/>

- <h6>예약관리 파트</h6>
우선입장 서비스 예약 관리<br/>
고객 예약정보 CRUD<br/>
예약정보 문자메시지 전송<br/>

- <h6>일정 관리 파트</h6>
캘린더를 통한 일정 CRUD<br/>
마이페이지
개인정보 수정
개인 일정 CRUD

- <h6>계정 관련 / 사원관리 파트</h6>
회원가입, 로그인, 로그아웃<br/>
아이디 찾기<br/>
임시 비밀번호 발급(이메일 발송)<br/>
사원 관리<br/>
사원조회(필터링 검색)<br/>
필터링 결과에 따른 엑셀로 내보내기<br/>
사원 정보 CRUD<br/>
