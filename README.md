# Crowd Funding
스프링 활용 크라우드 펀딩 사이트 구현 프로젝트

## 🖥 프로젝트 소개
- 개발 동기 : <br>
1. 단순히 물건을 사고 파는 쇼핑몰에 그치는 것이 아니라 개인의 투자와 소비 트렌드 파악 및 반영
2. Java, Spring, DB, CSS, HTML 등의 기술 적극 활용 가능
3. 다양한 구현 경험을 통해 사용자 인터렉션에 대한 높은 이해력 습득 가능 및 팀과의 협업 경험을 향상 

- 개발 목표 : Java, Spring, JSP, HTML, CSS, JavaScript 등을 이용하여 펀딩 상품을 구매 및 판매할 수 있는 사이트를 구현합니다.

<br>

## 📅 개발 기간
2022.11.16 ~ 2022. 12.16
<br><br>

## 🔧 개발 환경
- OS : Microsoft Windows 10
- WAS : Apache Tomcat 9.0
- IDE : Eclipse
- DB : Oracle DB
- 개발 언어 : HTML, CSS, Bootstrap / JavaScript, jQuery, ajax / Java 11
- 개발 프레임워크 : Spring, Mybatis, Maven
- 라이브러리 : jQuery, jackson-json
<br>

## 📌 ERD
<img width="2034" alt="erd2" src="https://user-images.githubusercontent.com/112562015/208099595-ed925580-2d4d-4f9b-ba17-c61d63ef26a5.png">
<br><br>

## 📌 MY 구현 기능
#### [펀딩 프로젝트 만들기]
아래 블로그에서 자세한 화면 구현을 볼 수 있습니다.<br>
https://doyu053.tistory.com/71
- 요금제 선택 페이지 : 사용자는 요금제를 선택할 수 있습니다.
- 기본정보 페이지 : 사용자는 펀딩의 제목, 메인 사진, 목표 금액, 시작날짜, 종료날짜, 검색용 태그를 입력할 수 있습니다.
- 스토리 페이지 : 사용자는 펀딩의 상세 이미지를 등록할 수 있습니다.
- 옵션 페이지 : 사용자는 펀딩 상품의 옵션을 등록할 수 있습니다.(옵션 이름, 내용, 가격, 배송비 설정)
- 메이커 페이지 : 사용자(메이커)는 메이커 이름, 메이커 로고 사진, 함께하는 멤버, 홈페이지, 전화번호를 입력할 수 있습니다.<br><br><br>

#### [임시 저장 및 미리 보기]
아래 블로그에서 자세한 화면 구현을 볼 수 있습니다.<br>
https://doyu053.tistory.com/72
- 사용자는 펀딩 프로젝트 만들기 페이지에서 입력한 정보를 임시 저장할 수 있습니다.
- 사용자는 임시 저장한 프로젝트를 불러오기, 수정, 삭제, 최종 등록 할 수 있습니다.
- 사용자는 임시 저장한 프로젝트를 최종 등록 전 미리보기 할 수 있습니다.
- 사용자는 미리보기 페이지에서 프로젝트를 이미지 저장할 수 있습니다.<br><br><br>

#### [최종 등록]
아래 블로그에서 자세한 화면 구현을 볼 수 있습니다.<br>
https://doyu053.tistory.com/73
- 사용자는 필수 항목 값을 모두 입력시 펀딩 프로젝트를 최종 등록할 수 있습니다.<br><br><br>

#### [펀딩 프로젝트 관리 및 멤버 관리]
아래 블로그에서 자세한 화면 구현을 볼 수 있습니다.<br>
https://doyu053.tistory.com/74
- 사용자는 자신이 최종 등록한 펀딩 프로젝트를 조회할 수 있습니다.
- 펀딩 현황 : 사용자는 자신의 펀딩 프로젝트의 목표금액, 남은 기간, 현재까지의 펀딩 금액, 찜하기 개수를 조회할 수 있습니다.
- 결제 현황 : 사용자는 자신의 펀딩 프로젝트의 결제자 이름, 결제 날짜를 조회할 수 있습니다.
- 멤버 추가 : 사용자는 사이트에 가입된 사용자만 프로젝트를 함께하는 멤버로 추가할 수 있고, 멤버로 추가시 멤버의 이메일로 수락 메일을 보내 수락시에만 멤버로 추가됩니다. 
- 멤버 관리 : 멤버의 상태(수락 완료, 수락 대기중)확인, 멤버 조회, 삭제를 할 수 있습니다.

<br><br>

## 💁🏻‍♀️ 멤버 구성 및 업무 분담
-인원 : 5명<br>

- 김도유 :  펀딩 프로젝트 만들기 페이지/ 임시 저장 기능/ 프로젝트 수정 기능 / 최종 등록 전 미리보기 기능/ 프로젝트 최종 등록 기능/ 펀딩 프로젝트 관리 - 펀딩 현황, 결제 현황, 멤버 관리(멤버 추가 및 삭제) 
- A 팀원 : 스토어 메인, 상세 페이지/ 스토어 찜하기/ 결제/ 스토어 후기/ 판매자 문의
- B 팀원 : 메인 페이지/ 실시간 후기/ 팔로우/ 공지사항/ 고객센터(메일 및 채팅상담)
- C 팀원 : 회원가입/ 로그인/ 회원 정보 페이지/ 프로젝트 조회 / 관리자 페이지/ 광고서비스 및 통계
- D팀원 : 펀딩 메인, 상세 페이지/ 펀딩 검색기능/ 창작자 문의/ 펀딩 후기/ 펀딩 후원
