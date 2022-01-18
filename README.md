인천일보아카데미
2021. 11 ~ 2022. 01
프로젝트명 오늘의 GYM
(Spring MVC페이지 기반)
투입인원 7명
주요역할 및 담당
공통역할 :
1. 팀원들끼리 브레인스토밍 방식으로 모여서 주제 선정 및 기획.
2. 총괄/기획 후 데이터베이스 정의, 설계 및 구현.
3. 인원과 역할을 알맞게 분배.
4. 외부 css템플릿(bootstrap)을 사용하지 않고 코딩 시작.
5. DB에 필요한 자료 함께 수집하고 진행.

≪about페이지 제작≫
- 프론트 디자인 구성

≪회원권구매메인페이지 제작≫
- 한 페이지에 4가지 종목(헬스, 수영, 클라이밍, 크로스핏) 의 상세 회원권을 카테고리로 설정 후
[jQuery Plugin] isotope 필터 및 정렬 플러그인을 사용하여 해당 카테고리 클릭 시 해당되는
리스트만 출력되는 화면구성을 구현.
- AMG피트니스 홈페이지 벤치마킹.

≪구매상세페이지 제작≫
- 선택옵션을 select tag로 제작한 후 선택된 옵션의 DB에 저장된 내용(회원이 확인해야 되는
옵션명, 가격)을 화면에 출력 및 session 정보에 저장.
- 저장된 session 값을 구매하기와 장바구니 버튼을 이용하여 해당 페이지에 전송.
- 동영상 삽입 및 자동반복재생기능 구현.
- 카카오API 를 통한 주소로 장소표시하는 MAP구현.
- 다양한 쇼핑몰 제품상세페이지 벤치마킹.

≪장바구니페이지≫
- 넘어온 session정보를 구현한 장바구니 프론트화면에 배치
- checkbox를 통한 선택 및 해제로 하단 상품금액 및 총 주문금액표시 및 변경
- 설정 아이콘으로 개별 상품삭제기능 구현.
- 선택 된 상품 전체삭제기능 구현
- 개별 삭제 및 전체 삭제 전 확인 alert창 띄우기 구현.
- 계속하기 버튼으로 다시 구매페이지이동.
- 결제하기 버튼으로 최종 선택 된 정보값을 결제페이지로 전송.
- 네이버페이 장바구니 벤치마킹

개발도구
개발산출문서 eXERD, Excel
DB설계 - Oracle SQL Developer
IDE 도구 - Sts
웹 서버 - Apache Tomcat 9.0
언어 - JAVA / JavaScript / HTML
주요 라이브러리 - jQuery / Gson (JSON) / Apache Commons / MyBatis
프레임워크 - Spring

프로젝트 소개
운동 회원권 및 PT권의 획일화되지 않은 가격정책에 불편을 겪지 않기 위해 센터 별 종목별 가격정찰제를 투입 및 한눈에 보고 결제를 손쉽게하여 코로나 시대에 위험한 발품 을 덜 팔게하기위한 웹 페이지 제작.

소스 https://github.com/TaegyeongHwang/TodayGym
