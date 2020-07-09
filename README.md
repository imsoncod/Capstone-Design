# Capstone-Design

  2020-1학기 캡스톤디자인 프로젝트

<br>

## 개발자

* imsoncod

* Raison-CJH

<br>

## 개요

대한민국 국민인 남성은 국방의 의무 중 하나인 병역의무를 수행하게된다. 즉, 군대를 다녀와야만 한다. 

옛날부터 욕설, 구타, 가혹행위 등 부조리가 가득했던 군대의 모습은 점차 사라지게 되었고 
최근에는 '선진병영'문화가 스며들면서 군인들의 자유를 보장해주고 존중해줄 수 있는 정책
들이 시행되기 시작했다. 그 중 하나가 '군 장병 스마트폰 사용' 정책이다. 

19년 4월, 이젠 간부뿐만 아니라 병사들도 부대내에서 스마트폰을 사용할 수 있게되었다. 
이를 계기로 개발진들의 군경험과 현역 장병들의 요구사항을 바탕으로 군생활에 유익함을 가져다줄 수 있는 App을 기획하였다. 
기존에 전역일계산기, 휴가계산기 등 유사 App들이 존재하지만 스마트폰 사용 정책 도입으로 필요성이 떨어지거나 기능들이 분산되어 있어 
이를 해결하는 방향으로 필요성이 있는 기능들만 통합시키는 방식으로 시스템을 설계할 계획이다.

<br>

## 시스템 구성도

  ![image](https://user-images.githubusercontent.com/48934537/87004479-71971b80-c1f8-11ea-8858-923be44a6aad.png)

<br>

## 서비스 소개

* 카카오 로그인 - 카카오 계정으로 서비스를 이용할 수 있습니다.

  ![image](https://user-images.githubusercontent.com/48934537/87006075-07cc4100-c1fb-11ea-8960-885fc7804fdd.png)
  
  <br>

* 내 정보 등록 - 입대/전역 날짜, 복무지를 등록할 수 있습니다.

  ![image](https://user-images.githubusercontent.com/48934537/87006007-ebc89f80-c1fa-11ea-922a-b40a7e7a791a.png)
  ![image](https://user-images.githubusercontent.com/48934537/87006209-4235de00-c1fb-11ea-8211-741642c3f3be.png)
  
  <br>

* 홈 - D-day, 날씨, 영어단어, 주간 핫 게시물, 국방부 소식을 확인할 수 있습니다.

  ![image](https://user-images.githubusercontent.com/48934537/87006400-9214a500-c1fb-11ea-8858-8869d1835c9b.png)
  
  <br>

* 전역일 계산 - 홈에서 D-day부분을 눌러 전역일 계산 정보를 세부적으로 확인할 수 있습니다.

  ![image](https://user-images.githubusercontent.com/48934537/87006794-3ac30480-c1fc-11ea-807a-d473c89ecb0e.png)

  <br>
  
* 운명 - 내일의 운세와 명언을 확인할 수 있습니다.

  ![image](https://user-images.githubusercontent.com/48934537/87007046-942b3380-c1fc-11ea-93f6-6cb92e112fca.png)

  <br>
  
* 캘린더 - 이벤트와 다이어리를 관리하고 주간 날씨를 확인할 수 있습니다

  ![image](https://user-images.githubusercontent.com/48934537/87007351-19aee380-c1fd-11ea-9cfb-2a134de2978b.png)
  ![image](https://user-images.githubusercontent.com/48934537/87007672-980b8580-c1fd-11ea-99cd-1a854ee8cfc2.png)
  ![image](https://user-images.githubusercontent.com/48934537/87007445-45ca6480-c1fd-11ea-8838-e7a24ad41a19.png)
  ![image](https://user-images.githubusercontent.com/48934537/87007760-b8d3db00-c1fd-11ea-86f8-b7f31e6ddc76.png)
  ![image](https://user-images.githubusercontent.com/48934537/87007945-f6386880-c1fd-11ea-9567-99c79d0b038d.png)
  ![image](https://user-images.githubusercontent.com/48934537/87007986-04868480-c1fe-11ea-9a5f-68c145657f5d.png)

  <br>
  
* 체력측정 - 종목별 타이머를 사용할 수 있고 등급컷을 확인할 수 있습니다.

  ![image](https://user-images.githubusercontent.com/48934537/87008161-4d3e3d80-c1fe-11ea-9f04-e3d8fa041172.png)
  ![image](https://user-images.githubusercontent.com/48934537/87008226-63e49480-c1fe-11ea-905f-f8e78e116abe.png)
  
  <br>
  
* 커뮤니티 - 여러 장르의 커뮤니티에서 게시글을 작성하여 소통할 수 있습니다.

  ![image](https://user-images.githubusercontent.com/48934537/87008612-fd13ab00-c1fe-11ea-8513-7ea9089a8ed2.png)
  ![image](https://user-images.githubusercontent.com/48934537/87008955-71e6e500-c1ff-11ea-98f3-9e5756d36e5c.png)
  ![image](https://user-images.githubusercontent.com/48934537/87009116-b1153600-c1ff-11ea-8bb1-a062299ccff8.png)
  ![image](https://user-images.githubusercontent.com/48934537/87009164-c4c09c80-c1ff-11ea-9136-43d6de9e3693.png)
  
  <br>
  
* 설정 - 내 정보 수정, 작성글 확인, 공지사항/업데이트 확인, 소개 확인, 의견 보내기를 이용할 수 있습니다.

  ![image](https://user-images.githubusercontent.com/48934537/87009401-16692700-c200-11ea-80b9-a52f68689a4b.png)
  ![image](https://user-images.githubusercontent.com/48934537/87009471-2bde5100-c200-11ea-9845-7de1fbccd8b6.png)
  ![image](https://user-images.githubusercontent.com/48934537/87009500-34cf2280-c200-11ea-8a6d-d900ef4e620e.png)
  ![image](https://user-images.githubusercontent.com/48934537/87009553-431d3e80-c200-11ea-982f-f48451bd8d0c.png)
  ![image](https://user-images.githubusercontent.com/48934537/87009678-7b248180-c200-11ea-821f-a68fe8c02eb9.png)
  ![image](https://user-images.githubusercontent.com/48934537/87009592-5203f100-c200-11ea-99ba-af1ad2cab292.png)
  ![image](https://user-images.githubusercontent.com/48934537/87009741-92636f00-c200-11ea-94d8-a856bd0aac9c.png)
  ![image](https://user-images.githubusercontent.com/48934537/87009612-59c39580-c200-11ea-98da-aa1c64175294.png)
  ![image](https://user-images.githubusercontent.com/48934537/87009635-66e08480-c200-11ea-9caa-46677d2bac6c.png)
  ![image](https://user-images.githubusercontent.com/48934537/87009880-c2ab0d80-c200-11ea-9ed8-a1411e30d78f.png)

<br>

## 기술 스택

Framework : Spring Boot MVC

Front-end : Html, Javascript, Css, jQuery, Ajax

Back-end : Java, Xml, Ubuntu, Apache Tomcat

DB : MySQL

기타 : Github, Crawling, Kakao API, FullCalendar

<br>

## 프로젝트 진행 과정 기록

### 📅 2020-03-30 ~ 2020-04-10

* [분야 선정]

  * 하이브리드 App

* [아이디어 선정]

  * '군인'들을 위한 프로젝트 구상
  
* [필요한 기술 고찰]

  * Spring Boot
  
  * MVC Design Pattern
  
  * Java, MySQL, WebLanguage
  
  * 프로젝트 구조 이해
  
* [개발 툴 선정]

  * STS, Android Studio, MySQL WorkBench
  
  * FileZilla, PuTTY
  
  * Adobe Xd CC 2020
  
  * GitHub
  
<br>
  
### 📅 2020-04-13 ~ 2020-04-17

* [시장 분석]

  * 타 App 기능 분석
  
  * App의 필요성 분석
  
* [요구사항 분석]

  * 현역 군인들에게 필요한 기능 체크
  
  * 예비군들의 경험을 바탕으로 필요한 기능 체크
  
* [기능 선정]

  * 전역일 계산
  
  * 캘린더
  
  * 타이머
  
  * 운명
  
  * 학업
  
  * 국방소식
  
  * 커뮤니티
  
* [프로토타입]

  * Adobe Xd를 이용하여 프로토타입 완성
  
  * 회의를 통해 도출된 피드백을 바탕으로 프로토타입 재구성
  
  * 홈 - 전역일계산, 학업, 핫이슈, 국방소식 / 탭 - 홈, 타이머, 운명, 캘린더, 커뮤니티
  
<br>  

### 📅 2020-04-20 ~ 2020-04-24

* [캘린더]

  * FullCalendar를 이용하여 기본 View 틀 제작
  
  * CSS 추가
  
  * 구글캘린더API를 이용하여 대한민국 공휴일 표시
  
  * '오늘'로 이동 버튼 추가
  
  * 이벤트 추가 버튼 생성 및 테스트 완료
  
  * Today+7일까지 주간 날씨를 이미지로 셀 내에 표시
  
  * 날짜 셀 클릭 시 해당 날짜와 이벤트를 받아오는 창 생성 완료
  
  * 다중 이벤트, 공휴일 이벤트 조회 완료
  
* [홈]
  
  * 홈 틀 구성
  
  * Html 기본 View 틀 제작
  
  * CSS 추가
  
* [운명]
  
  * 운세 / 명언 틀 구성
  
  * Html 기본 View 틀 제작
  
  * CSS 추가

* [타이머]
  
  * 타이머 기본 틀 구성
  
  * 윗몸 일으키기 / 뜀 걸음 / 팔 굽혀펴기 [탭] 기능 CSS를 이용하여 제작
  
  * 윗몸 일으키기 탭 타이머 텍스트 및 버튼 표시
  
  * 뜀 걸음 탭 타이머 텍스트 및 버튼 표시
  
  * 팔 굽혀펴기 탭 타이머 텍스트 및 버튼 표시
  
  * JS 와 Jquery 를 이용하여 타이머 설계 완료
  
  * 각 탭마다 타이머가 각각 작동하도록 제작

<br>

### 📅 2020-04-27 ~ 2020-05-01

* [캘린더]

  * 이벤트 조회 알고리즘 수정
  
  * 데이터 입력으로 이벤트를 추가할 수 있는 UI완성
  
  * jquery datepicker를 이용하여 이벤트 시작/종료 날짜 선택
  
  * 이벤트 개수 제한 설정
  
  * 기타 코드 수정
  
* [홈]

  * 아이콘 이미지 추가 완료
  
  * 폰트 추가 및 적용 완료
  
* [운명]

  * 각 컨텐츠 글자로 변경 완료
  
  * 폰트 추가 및 적용 완료
  
* [전역일계산기]

  * Html 기본 view 틀 제작
  
  * 폰트 추가 및 적용 완료
  
  * jquery-circle-progress를 이용하여 원 그래프 적용 완료.
  
  * 그래프 숫자 깨짐 현상 수정 완료
  
  * 색상 lime 색으로 변경
  
  * value 값을 통해 게이지 변경 되도록 소스 수정 완료
  
  * 애니메이션 효과 적용 완료
  
  * 이미지 추가 완료
  
* [게시판]

  * Html 기본 view 틀 제작
  
  * 폰트 추가 및 적용 완료
  
<br>

### 📅 2020-05-04 ~ 2020-05-08

* [DB]

  * 설계 예정
  
* [프로젝트 구조도]

  * 제작 예정
  
* [Spring Boot]

  * View 파트 이동 완료
  
  * 코드 공유 및 협업용 Repository 생성 완료
  
* [캘린더]

  * 이벤트 추가 알고리즘 수정
  
  * datepicker css 수정
 
* [게시판]

  * Side Bar 틀 제작 및 추가 완료
  
  * 게시판 테이블 형식으로 소스 수정 완료
  
  * 게시판 검색 View 추가 완료
  
<br>

### 📅 2020-05-11 ~ 2020-05-15

* [DB]

  * 설계 완료

  * 구현 및 연동 예정
  
* [프로젝트 구조도]

  * 유즈케이스 다이어그램 제작 완료
  
* [캘린더]

  * 날씨 및 기온 크롤링 기능 추가

* [전역일계산기]

  * D-Day 계산 알고리즘 추가
  
* [복무지 선택]

  * 날씨 조회를 위한 복무지선택 View추가
  
  * 대한민국 도시 데이터 수집

* [로그인]

  * 카카오 로그인 연동 완료
  
* [게시판]

  * MyBatis로 데이터베이스 연동 완료
  
  * Mysql 설계 및 테이블 추가 완료
  
* [게시판 작성]
  
  * Controller 모델 추가 및 데이터 연결 완료
  
  * 게시판 Service 추가 완료 
  
* [게시판 뷰]
  
  * Controller 모델 추가 및 데이터 연결 완료
  
  * 추천 / 비추천 기능 추가 완료
  
  * Ajax 이용하여 추천했을 때 데이터 전송 완료

<br>

### 📅 2020-05-18 ~ 2020-05-22

* [DB]

  * 기존 DB가 MyISAM방식이어서 임시로 InnoDB방식을 만들어서 이용중 -> 이후 DB이전할 예정

  * 회원, 복무지, 영단어, 명언, 이벤트 테이블 구현 및 연동 완료

* [로그인]

  * 데이터베이스 연동 완료

* [일일 영단어]

  * 1800개 영단어 데이터 수집 및 가공 후 csv파일로 준비 완료
  
* [명언]

  * 명언 데이터 약 440개 수집 및 가공 완료
  
  * 군 관련 명언 추가 수집 예정  

* [게시판 댓글]

  * 댓글 및 대댓글 SQL 설계 및 연동 완료
  
* [게시판]

  * 게시글 날짜 추가 및 비추천 기능 추가 완료
  
  * 댓글 작성 View 변경 완료
  
  * Service 및 Mapper 변경 작업 완료
  
  * 게시글 추천 댓글(count) 연동 완료

<br>

### 📅 2020-05-25 ~ 2020-05-29

* [캘린더]
  
  * 이벤트 CRUD 구현 완료
  
  * 다이어리 CRU 구현 완료
    
* [로그인]

  * 세션을 이용하여 토큰값 송수신
  
  * 자동로그인에 바로 호환될 수 있게 코드 수정

* [명언 및 운세]

  * csv 데이터 DB 삽입 예정
  
<br>

###  📅 2020-06-01 ~ 2020-06-05

* [영단어]

  * csv 데이터 DB삽입 완료
  
  * 스프링 - DB 연동 완료
  
* [명언 및 운세]

  * csv 데이터 DB삽입 완료

  * 스프링 - DB 연동 완료

* [View]

  * 스마트폰 키보드가 View를 가리고 Android 하단바와 호환이 잘 되지 않는 것을 확인
  
  * 웹 자체에서 하단바를 제작하여 Android와 연동 완료

<br>

###  📅 2020-06-08 ~ 2020-06-12

* [전역일 계산]

  * 회원가입 시 입대일과 전역일을 입력하도록 추가
  
  * 입력된 입대일과 전역일을 기준으로 D-day와 군생활 퍼센트 계산
  
* [View]

  * 모바일 화면에서 최적화되지 않던 View 수정
  
* [날짜 선택]

  * jquery datepicker 제거 -> input태그의 date타입을 사용

* [디자인]

  * 전체 1, 2차 디자인 수정 완료
  
* [최적화]

  * 코드 최적화 완료
  
* [버그]

  * 테스트 및 세부 버그 수정 완료
  
* [광고]

  * 카카오 애드핏, 쿠팡 파트너스 광고 삽입 완료
  
* [설정]

  * 제작 완료

* [Android]

  * WebView 제작 후 자동로그인 구현 완료
  
###  📅 2020-06-15 ~ 2020-06-19
  
* [버그]

  * 테스트 및 버그 수정

  * 자동로그인 버그 수정
  
  * 메일 무한 로딩 버그 수정

* [복무지 선택]

  * 디자인 수정
  
* [문서]

  * 최종 프로젝트 문서 제작

### 이후

* [서버]
  
  * cafe24 가상 리눅스 서버 구축 및 테스팅 완료
