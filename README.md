# 프론트 엔드 기초 수업

## GITHUB 기초 개념

> GITHUB 용어

- stage : commit할 대상을 선택
- commit : 수정한 내용의 스냅샷을 찍음
- push : GITHUB 서버에 업로드
- pull : GITHUB 서버에서 다운로드
- branch : 각각의 개발자가 독립적으로 개발하기 위한 가지
- pull request : 각각의 branch에서 개발한 것을 master branch로 병합하기 위한 요청
- merge : 각각의 branch 에서 개발한 것을 master branch로 병합

> 사이트 링크

마크다운 사용법 : [안내문서](https://gist.github.com/ihoneymon/652be052a0727ad59601)<br/>
HTML, CSS, JS 참고 사이트 : [w3schools](https://www.w3schools.com/)<br/>
온라인 에디터 : [Codepen](https://codepen.io/pen/tour/welcome/start)

## WEB/IT 기초 개념

> 클라이언트-서버 모델 : 사람이 사용하는 기기들이 클라이언트, 아이티 서비스의 내용을 저장하고 있는 컴퓨터가 서버, 물리적으로 연결되어있는 상태
ex)컴퓨터,모바일 등은 클라이언트 본체는 서버
<img src="https://github.com/JOYONGSUN/20210320_start_frontend/blob/main/1200px-Client-server-model.svg.png" width="450px" />

클라이언트-서버 모델에서 클라이언트는 사용자가 사용하는 디바이스(PC, Mobile)를 의미하고, 서버는 클라이언트가 접속 해서 데이터나 파일을 요청했을때 응답하는 시스템

클라이언트와 서버는 네트워크를 통해서 연결됨

<img src="https://s3-ap-northeast-2.amazonaws.com/opentutorials-user-file/course/2614/4971.png" />

클라이언트와 서버 모델은 실제 연결은 아니지만 개념적으로 클라이언트 관점에서 1:1로 연결되었다고 생각할 수 있음

클라이언트 서버 모델에서 이루어지는 동작은 클라이언트의 요청(request)과 서버의 응답(response)의 1 사이클로 구성됨

클라이언트는 클라이언트 디바이스에서 실행되는 웹브라우저, 서버는 서버 디바이스에서 실행되는 서버 소프트웨어가 실제로 사용되는 것임

## HTML(Hyper Text Markup Language)

>[HTML Introdution](https://www.w3schools.com/html/html_intro.asp)
 HTML 요소는 콘텐츠를 표시하는 방법을 브라우저에 알려줍니다.
 마크 업 언어

<!DOCTYPE html>선언이 문서는 HTML5 문서임을 정의
<html>요소는 HTML 페이지의 루트 요소입니다
<head>요소는 HTML 페이지에 대한 메타 정보를 포함
<title>요소는 (브라우저의 제목 표시 줄이나 페이지의 탭에 표시되는) HTML 페이지의 제목을 지정합니다
<body>요소는 문서의 본문을 정의하고, 등 호, 단락, 이미지, 하이퍼 링크, 테이블,리스트, 모든 가시적 인 컨텐츠에 대한 컨테이너이고
<h1>요소는 큰 제목을 정의
<p>요소는 문단을 정의
  
  편집기 코드펜
  https://www.w3schools.com/html/html_basic.asp
  
>[HTML Element](https://www.w3schools.com/html/html_basic.asp)

>[HTML Attributes](https://www.w3schools.com/html/html_attributes.asp)

HTML속성(Attributes)
1)HTML Element에 추가 정보를 제공
2)name="value"형태로 사용

웹 문서에서 표시할 수 있는 콘텐츠
1)텍스트
2)이미지
3)멀티미디어(비디오,오디오)

### 텍스트 콘텐츠 요소()


>[1. HTML Heading 제목태그](https://www.w3schools.com/html/html_headings.asp)<br/>
제목태그
heading -> h
h1~h6

>[2. HTML Paragraphs 단락](https://www.w3schools.com/html/html_paragraphs.asp)<br/>
단락태그
Paragraphs->p
Horizontal Rules->hr(Empty Element빈태그)

>[3. HTML Links 단락](https://www.w3schools.com/html/html_links.asp)<br/>
하이퍼링크
Anchor->a
href : 링크로 연결된 목적지 주소
1)외부링크
 -링크 주소 입력 시 http(https)키워드를 사용
2)내부링크
3)북마크
 -목적지에 id attribute를 사용해서 이름을 정해줌
 -href attribute #를 사용해서 목적지 이름을 입력
 
>[4. HTML table 테이블](https://www.w3schools.com/html/html_tables.asp)<br/>
 -[table Generator](https://www.tablesgenerator.com/html_tables)
 

>[5. HTMLL List 리스트](https://www.w3schools.com/html/html_lists.asp)<br/>
1)순서없는 목록(ul)
2)순서있는 목록(ol)
3)설명 목록
4)ul,ol목록에서 중첩(rested) 형태로 사용할때 포함 관계를 주의
-포함하는 목록 항목에 작은 목록전체가 
-------------------------------------------------
html,css,js는클라이언트 브라우저가 해석(뿌려준다)랜더링한다
 해석=랜더링,컴파일링,인터프리팅
서버에서 처리하는 언어(처리해서 결과만 화면에):PHP,ASP,JSP

서버=IDC센터 컴퓨터 ex)KT 분당 IDC

라우터,게이트웨이=망구성     스마트폰 기지국

클라이언트 서버모델의 개념

푸쉬 알림/벳지?/칼럼?

메인브런치=마스터브렌치

서버소트웨어=서버

os/IIS설치(asp언어로개발)
리눅스/아파치소프트웨어서버설치(PHP언어,톰켓으로 자바사용)

클라이언트는 클라이언트 하드웨어에서 실행된 웹브라우저
네이버에 설치된 아파치가 서버



-------------------------------------------------

frontend 공부시작

문준석 선생님
ministori@naver.com
1,2.github
web/it 기초내용
html
3,4.css
5,6.js
example
1:20-2:30 -> 3:50
-------------------------------------------------
브라우저:크롬
컨트롤+링크클릭=새탭

<버전관리시스템>
tortoise svn(설치형:비공개작업)-setting
깃&깃허브(+협업)
cvs

<OS>
윈도우 < 맥os(리눅스기반or유닉스 기반) < 서버 리눅스
*리닉스 공부,리눅스 커널 책(리눅스 소스 공개)
*
안드로이드 ios

<cmd,bash>

깃허브에서 레파지토리 만들기
워드프레스-php개발자
서버개발자 php
cms
리모트워크

<프레임웤,애니메이션>
자바스크립트,제이쿼리-리엑트,앵귤러.vue.js

알고리즘

서버공부
아파치서버
아파치톰켓

웹서버
was
왓스-websphere 유지보수 전문인력
톰켓 내부 관련인력

프론트 자동화툴 벌크 인클루드시킨다
gulp.js 웹펙

sass css전처리 언어(css언어 프로그래밍 언어처럼 처리)

프론트 툴 공부

언어를공부할것인가 툴을 공부할것인가

프론트엔드 로드맵
---------------------------
깃허브
버전관리
레파지토리:저장소
커밋:
----------
<버전관리 커밋을 하기위한단계>
컴퓨터내 수정작업->stage:무대위에 올리는거->commit->스냅샷찍기->push 깃허브네트워크 반영
pull:push의 반대로 다운로드를 받는다(협업)
branch/master branch ->pull request 작업이 끝났다는 표시-> merge 합침

깃허브에서 만드는 문서
마크다운문서

마크업언어

약자의 뜻을 알면 이해하기 쉬움

WYSIWYG:워드,한글,파워포인트,포토샵

commit에 메모 이력을 남긴다

커밋 푸쉬 

소스트리 사용

ide 에디터

vscode 깃허브 접속
--------------------------
웹사이트 기술 표준 사이트 w3c

header tag

html 5.1버전

css grid layout

w3schools.com

자바:소프트개발언어

asp

웹기술=프론트엔드

코드펜


--------------
만들겠다하면 몇천 몇만줄이 됩니다~
그렇게 코드영문하고 한글하고 섞이다보니
들여쓰기로 모듈단위로 나누어주고 포함관계 표시
유지보수에 용의하다

가독성이 좋게 어떻게 코딩을할까???????????
작은따옴표,큰따옴표?

지금은 들여쓰기 가독성때문에 잘 지켜주자

그렇게 정리 ㄱ ㄱ 

위키백과 만들어볼거임

html

역사-최초 규격까지~!!!!!

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=<device-width>, initial-scale=1.0">
    <title>2일차</title>
</head>
<body>
    <h1>사전찾기,태그+컨텐츠=엘리먼트</h1>
    <p>
    스타트테그,엔드테그->컨텐츠입력
    *****빈태그,빈요소=시작태그만 있음
    소문자입력원칙
    html attributes : html속성
    css property : css 속성
    HTML 속성 : 시작 태그에 지정,일반적으로 name = "value" 와 같은 이름 / 값 쌍
    ex)<a href=""></a>,<img src=""> 

    웹문서,웹앱(구글 문서)

    서비스사이트

    분활화면

    h1>h6
    </p>
</body>
</html>
