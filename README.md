# 국비 훈련 시작
## 서론 
- 나만의 웹/앱을 만들고 싶다는 생각으로 코딩을 시작하게 되었다. 유튜브, 생활코딩을 시작으로 HTML. CSS, JAVA를 배우며 흥미를 느꼈고 혼자 공부하는데 어려움을 가지게 되어 국비 교육을 신청하게 되었다. 이 교육과정동안 예습/복습, 그리고 부족한 부분을 스스로 학습하여 교육과정이 끝날때는 부족함없는 주니어 개발자로 성장하고자 한다.
- 국비 훈련 진도순서
1. HTML, CSS, Javascript.
2. Oracl, Data base.
3. Jsp
5. Spring Framework
6. Vue
## 본론
### Step01_Hello
#### 수업 요약
- HTML(골격),CSS(디자인),Javascript(동작)의 정의와 각각의 영역에 대해 배우고 주석에 대하여 배웠다.
- 웹페이지에서 볼 수 있는 제목<h1~6>태그와 이미지, 하이퍼링크, 알림창, 글씨의 디자인에 대하여 간단하게 알아보았다.
- Chrom 브라우저에서 우클릭을 '소스보기'를 통하여 페이지의 코드 확인가능, 우클릭 '검사'를 통하여 Element, Consol, Style, 등 정보를 확인하고 수정해볼 수 있다.
- HTML은 요소(Element)로 골격을 이루고 있고 각 요소는 속성(Attribute)을 가지며 요소에 대한 추가 정보를 제공 할 수 있다.
- <script></script>=JS영역으로 페이지 로딩시에 웹브라우저가 해석하며, function을 활용하여 사용자가 원할때 기능을 실행할 수 있게한다.<br>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- HTML영역<br>
![image](https://user-images.githubusercontent.com/108508922/177001038-5c10bee3-33e4-491a-bd90-28efa3f5202a.png)
- CSS영역<br>
![image](https://user-images.githubusercontent.com/108508922/177000879-dc75ccdf-096f-47af-9b65-45fd31f35a6a.png)
- javascript영역<br>
![image](https://user-images.githubusercontent.com/108508922/177001061-40280261-85fb-4fea-a774-71d813f8a99f.png)
- 알림창<br>
![image](https://user-images.githubusercontent.com/108508922/177001535-7e6c94c9-c210-4ccf-a011-197b87dc03da.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Step02_img
#### 수업 요약
- img요소의 속성인 src(이미지 파일 경로),alt(이미지가 로딩되지 않을시 나타내는 문구) 알아보았다.
- div(문단), h1~6(제목), p(단락) br(강제 개행)에 대해 알아보았다.
- id 속성은 특정 요소를 유일하게 식별하고자 할때 사용하는 속성이다.
- class 속성은 특정 요소들을 같은 그룹으로 구성하고자 할때 사용하는 속성이다.
- Block 요소는 폭을 100% 활용하여 block 처럼 쌓이는 구조를 가진다. inline요소는 필요한 만큼의 폭을 사용한다.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Code<br>
![image](https://user-images.githubusercontent.com/108508922/177002605-590057c2-8c79-45f2-bbe3-6f156011d0db.png)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Step03,04_blockElement,inlineElement
#### 수업 요약
- Block 요소는 폭을 100% 활용하여 block 처럼 쌓이는 구조를 가진다. inline요소는 필요한 만큼의 폭을 사용한다.
- Ex)div, h1~h2, p 등,,
- inline요소는 필요한 만큼의 폭을 사용한다.
- Ex)img, span, b, strong, i, em 등,, (span은 style에 있어 자유도가 높다)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Code<br>
![image](https://user-images.githubusercontent.com/108508922/177036765-2f5ad0e6-d869-4585-82dc-2f2eb1eaf024.png)<br>
![image](https://user-images.githubusercontent.com/108508922/177036786-32424e1f-1548-4018-9db5-15af50714938.png)<br>
![image](https://user-images.githubusercontent.com/108508922/177036806-4280da9c-93d2-45e5-804f-1cd29a67e4b0.png)<br>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Step05,06,07_ul,ol,dl
#### 수업 요약
- ul(unordered list) 리스트 항목들을 기호로 구분한다. 
- ol(ordered list) 리스트 항목들을 숫자 또는 순서를 붙여 구분한다.
- dl(description list) 리스트의 제목과 설명을 붙여 구분한다.
- li 리스트 내부의 항목들을 나열하는 태그
- dt dl리스트 항목의 제목을 나타낸다, dd 정의된 제목의 대하여 설명한다.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Code<br>
![image](https://user-images.githubusercontent.com/108508922/177037013-5c8affc6-4e7e-45e4-a9cf-ed33af507f8d.png)<br>
![image](https://user-images.githubusercontent.com/108508922/177037020-e48aab32-f073-4fde-b76b-95dc3a48f986.png)<br>
![image](https://user-images.githubusercontent.com/108508922/177037036-2950cda3-6b4f-4c85-b8d7-958eeb500de9.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Step08_table
#### 수업 요약
- table의 정식형식이 있지만 약식으로도 사용할 수 있다.(Code참조)
- tr은 행요소.th or td 열요소.
- tfoot을 쓰는 이유는 tbody의 많은 데이터를 생략하고 중요한 값을 앞으로 도출하는 효과가 있다. 
- colspan, rowspan으로 행 또는 열 병합 가능, colgroup을 통하여 각 col 넓이 조절가능하다.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Code<br>
![image](https://user-images.githubusercontent.com/108508922/177042083-091d64bc-5dfb-4eb6-84d5-f1f9e703865a.png)<br>
![image](https://user-images.githubusercontent.com/108508922/177042109-7a680568-d48d-41c0-b590-1bdbc8d7e6f1.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Git 사용법
#### 수업 요약
- git명령어: init(특정 폴더를  gir local repository 생성.), add(commit 전 stage영역에 올리는 역할), commit(사진을 찍는다.), branch(새로운 branch 생성),checkout(Head를 옮김),rest(이전단계로 되돌림),merge(병합)..
- untracked files(저장되지 않은 파일), gui (관리창을 띄움), gui & (독립적인 관리창을 띄움)
- frast-forward 방식의 merge (master branch 부분의 수정이 없어 다른 branch point와 간단하게 병합하는 방식)
- 병합 후 branch 삭제:git branch -d "branch name"
- Remote repository 생성하기 : Github 가입 -> New repository 생성 -> Rocal repository 만든다 -> Git hub 저장소를 만든다 (git remote add origin '주소') -> git push -u origin 'branch name' -> Git hub에서 확인한다.
- Remote repository로 Push하면 remote repository를 트레킹 하는 origin/master branch가 local repository 자동 생성된다.
- 회사 -> 깃허브 <br>
git add . -> git commit -m "text" -> git push origin master.
- 깃허브 -> 집 <br>
git clone (최초), git fetch (최초 이후) -> git merge origin/master.
- 회사에서도 update commit이 있고 집에서도 update commit있을시 회사에서 update하기<br>
   1) git fetch -> git merge -> :wq(frast forwad경우) 
- 변경사항 취소하기 (add전)
   1) git restore .
   2) git clean -fd
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Git Process<br>
![image](https://user-images.githubusercontent.com/108508922/177064701-5b385954-4abd-47cc-a30b-64a574f14f08.png)<br>
- master branch와 작업중인 branch 간의 병합중 충돌이 일어났을때, 작업자가 직접 수정을 해주어야 한다.<br>
![image](https://user-images.githubusercontent.com/108508922/177068895-15d04cdc-17be-4a35-9a72-eead0e39dc95.png)<br>
- origin/master<br>
![image](https://user-images.githubusercontent.com/108508922/177089533-2758e6ae-2354-4806-b2ef-f9561ddf8bc3.png)<br>
- clone
![image](https://user-images.githubusercontent.com/108508922/177090931-a4a6d94a-2951-4d9e-a8ea-2fccd893efab.png)<br>
![image](https://user-images.githubusercontent.com/108508922/177092097-c6200ecc-6b59-49af-8c2d-834b8d07ac8b.png)<br>
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Step01_javascript
#### 수업 요약
- 어떤 변수에다가 값을 기억시켜놓고 변수에 들어있는 값을 활용하여 어떤 결과를 도출한다.
- 변수를 만들때는 미리 약속된 예약어 let 을 사용한다.
- let 다음에는 변수의 이름을 정한다, 
- 변수 <br>
   값을 저장할 수 있는 이름이 지어진 기억 공간이다.<br>
   값을 필요한 시점에 바꿀수 있다.<br>
   한번 선언한 변수는 다시 선언하면 안된다.<br>
- global variable:모듈의 어디서든 호출가능, local variable: 현재 함수에서만 유효(지역변수 호출 우선순위가 높다.)
- = 의 우측에 있는 값이 = 의 좌측에 들어간다.(대입된다)
- 한줄의 끝에는 ;을 작성한다.
- object type
 object type이 필요한 이유는? 여러개의 데이터를 하나의 묶음으로 관리하고자 할때 사용한다. {key:value, key2:value2, ...}
 object type은 순서가 중요하지 않다.
- array type
 array type은 순서대로 index가 자동으로 부여된다.(array type은 objevt type의 부분집합이다.)
 ex)let foods=["삼겹살", "치킨", "김치찌게", "냉면", "햄버거"];, foods[0]=삼겹살
 array type:.length(size확인), .push(추가), .splice(2,1)(2번쨰 인덱스로부터 1개 삭제)
- function typ
 fuction type 의 중괄호는 원하는 시점에 작용할 javascript를 미리 준비해놓는 영역이다.ex) let f=function(){javascript area}<br>
 ()=함수를 call한다, call뿐만 아니라 참조도 할 수 있다.
 - 숫자+숫자의 +는 산술연살자 "문자"+1의 +는 연결연산자.
 - heap 영역
 objec type, array type, fuction type의 데이터가 heap영역에 들어간다, heap영역에 들어가면 value가 아닌 key값(참조값)으로 대체된다.
 - stack 영억
 number type, string type, boolean type, referance data(참조값)이 들어있다.
 - 문서 객체는 오브젝트와 유사하고 사물함에 보관되어 참조값을 가진다. 문서의 각 요소의 참조 값을 가져오기 위해선 document가 필요하다.
 -document.querySelector("CSS형식 선택자 ex)요소명,#id,.class,...")
  JS영역에서 HTML 영역에 있는 해당요소를 가져온다.
 -document.querySelectorAll("문자열 CSS 선택자")
  JS영역에서 HTML 영엑에 있는 해당 요소를 배열 형태로 가져온다.
 - innerText를 활용하면 요소의 innerText를 변경 및 수정 가능하다
 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Code<br>
![image](https://user-images.githubusercontent.com/108508922/177101829-8ed26524-e891-4a62-898d-45c4561926ab.png)<br>
![image](https://user-images.githubusercontent.com/108508922/177232539-d8217aec-8632-4ce4-96f9-b794cafbd84e.png)<br>
![image](https://user-images.githubusercontent.com/108508922/177246547-5c20946c-3184-4e09-8145-263493064b62.png)<br>
- stack & heap 영역<br>
![image](https://user-images.githubusercontent.com/108508922/177442531-2931fdf8-4f5d-46af-a1ce-aec1a61aede3.png)<br>
- 문서 <br> 
![image](https://user-images.githubusercontent.com/108508922/177459454-1a0a42ac-f343-4829-900a-95c9a44044e7.png)<br>
- p의 참조값을 얻어오는 방법 <br>
![image](https://user-images.githubusercontent.com/108508922/177460787-e93b0857-a9ae-427a-8230-525517002474.png)<br>
- document.querySelector() & documnet.querySelectorAll() 
![image](https://user-images.githubusercontent.com/108508922/177894897-1a6e1005-a277-47e4-90f9-d1985a7bcf73.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Step02_event
#### 수업 요약
- .addEvemtListener( , )
 참조값을 가져온 요소에만 동작하는 event를 만들고 싶을때 사용한다
 2개의 값을 가진다 ("evnet name" , function(){javascript area});
 callback 함수: 전달만 해놓으면 나중에 알아서 작동하는 함수.
- global 영역에 함수를 만들면 다수와 작업시 겹칠 수 있고 바람직하지 않다.
- web page가 작동하지 않으면 cosole창을 우선적으로 확인하여 오류를 해결한다.
- Inline CSS는 내부CSS보다 우선순위이다. <style>내부CSS</stye>, <요소 styele="Inline CSS"></요소>
- javascript로 Inline CSS를 작성할수 있다.
  document.querySelector("선택자").style.backgrounColor="red"; (CSS "-" 은 첫글자를 대문자(camel case)로 작성)
  선택한 요소에 Inline CSS가 작성된다.
- fucntion(){}의 call은 함수 호출 뿐만아니라 실행되는 object값을 가진다. 필요없을시에 공백이지만 사용시 매개변수를 활용한다.  
- 반복문: for(let i=0; i<20; i++){} , i가 20보다 작으면 영역을 반복한다.
 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- javascript로 작성한 Inline CSS<br>
![image](https://user-images.githubusercontent.com/108508922/177896788-aff70a54-03a1-4c26-b859-398951751f53.png)<br>
- 좌표 출력 evnet.(매개변수를 이용하여 object를 담아 활용)<br>
![image](https://user-images.githubusercontent.com/108508922/177897612-8606fc62-67b1-43be-9e06-863f66de9961.png)
- example.counte code<br>
![image](https://user-images.githubusercontent.com/108508922/177899099-ea7bba87-d756-4dd0-8586-9ef20fdfc30d.png)
- example.이미지 움직이기<br>
![image](https://user-images.githubusercontent.com/108508922/177899466-d8a4598d-9021-497d-b8fb-0598eb42535f.png)
- example.반복문활용<br>
![image](https://user-images.githubusercontent.com/108508922/177901453-dd24a37e-119c-40de-9ccc-1b5a10de3d92.png)
- function 함수
![image](https://user-images.githubusercontent.com/108508922/177906143-279cacd4-562b-4171-9254-f90a31b8cb4c.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Step03_
#### 수업 요약
Thread 페이지 로딩시점에 순서대로 작업하는것.필요시 나타나기도 한다.
var은 지역변수로 사용해도 전역변수로 된다.좋을거 없다. 
++num, num++ 증가시키고 대입, 대입하고 증가시키고
xxx.addEventListener{}안의this는 이벤트가 일어나는 그요소.(xxx=this)
비동기처리,
동기처리,
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/108508922/178169269-79f33229-c84c-4da4-9528-258cc2a90148.png)
![image](https://user-images.githubusercontent.com/108508922/178200670-0fd157cc-4a08-4fd8-9b86-9b8b5864cb2a.png)
![image](https://user-images.githubusercontent.com/108508922/178204608-7520a177-cefc-4d49-a558-b4a444f012f6.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Step03_
#### 수업 요약
svg-폰트,백터

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/108508922/178404127-09657893-e138-489b-9244-f715b1885a03.png)
### Step03_
#### 수업 요약
- flex-direction 축방향은 item이 쌓이는 방향 즉 colume이면 세로 row면 가로 축이 생기고, column이면 좌측이 start 우측이 end
row면 위쪽이 start 아래쪽이 end.
- flex-wrap 부모 div가 자식 div를 감쌀지 선택, revers는 거꾸로 감싼다
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- flex-direction 
![image](https://user-images.githubusercontent.com/108508922/178624453-a98258ff-c4b6-4200-833e-429554544b23.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 데이터베이스01
#### 수업 요약
- 명령 프롬프트<br>
- 관리자로 로그인해서 사용자 계정만들기<br>
   1) CMD 우클릭 속성 → 빠른 편집모드 삽입모드 체크 → sqlplus.exe → 사용자명:system → 비밀번호:oracle → 사용자 계정 만들기 → CREATE USER 아이디 IDENTIFIED BY 비밀번호; GRANT CONNECT, RESOURCE TO 아이디;(접속과 권한을 acorn에게 주겠다).<br>
- 사용자 계정으로 접속하기<br>
   1) CMD → sqlplus.exe → 아이디,비밀번호 입력<br>
- Mariadb 무료<br>
- DB에 저장하는 정보는 숫자,문자,날짜이며 table 형식으로 저장한다. 
   1) 숫자(number), 
   2) 문자(varchar2(), 
   3) 날짜(sysdate)
- 테이블 만들기
   1) create table 이름;
   2) (숫자type column명 number, 문자type column명 varchar2(영문자 기준 글자수), 문자type column varchare2(20-영문자 기준으로 글자수));
- 테이블 데이터 넣기
  desc 테이블이름 (테이블 확인하기)
   ed->메모장 수정 후 저장 닫기 -> 엔터
  commit 전까지는 임시 수정
  수많은 회원정보중 한사람을 삭제시키려면 primary key값을 삭제 
- dummy라는 컬럼을 가진 table dual을 제공한다.
-scott 계정만들기
관리자로 접속 @scott파일 경로
C:\oraclexe\app\oracle\product\10.2.0\server\RDBMS\ADMIN
아이디 비밀번호 입력후 접속
- (1) Select 
- 만들어져 있는 emp 테이블로 퀴즈풀기 (퀴즈 사진첨부)
- 정렬 order by asc(오름차순) or desc(내림차순)
- (2) Where
- 값이 ture인 row만 불러온다.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- 데이터베이스 S/W<br>
![image](https://user-images.githubusercontent.com/108508922/178633513-4912e24a-7391-47b9-a4f2-5e2f618eda9b.png)<br>
- 데이더베이스 저장정보<br>
![image](https://user-images.githubusercontent.com/108508922/178635330-2e1fdd43-63f3-424f-a33d-2c3dc3ee678f.png)<br>
- Client to DB to Client<br>
![image](https://user-images.githubusercontent.com/108508922/178636215-d8ada0e9-2494-4dbf-bd9a-5030e35d7161.png)<br>
- table 만들기<br>
![image](https://user-images.githubusercontent.com/108508922/178637287-b9995244-fea7-4576-b607-5618af2166cb.png)<br>
- table data 넣기<br>
![image](https://user-images.githubusercontent.com/108508922/178638979-0b01ff62-1432-4cc5-84e6-fa5ed2e5f555.png)<br>
- 넣은 data 확인하기<br>
![image](https://user-images.githubusercontent.com/108508922/178639345-0ec697aa-ef18-406d-8127-121b67f20335.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178639590-0aaf996f-a715-410c-bc0d-588c6cc25882.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178640178-9e6fdbee-94b4-44ab-844a-21ac705e11f5.png)<br>
- data 변경하기<br>
![image](https://user-images.githubusercontent.com/108508922/178641248-5d3480d2-38f7-4b41-84de-7bb7a2a9fcbd.png)<br>
- data 삭제하기<br>
![image](https://user-images.githubusercontent.com/108508922/178642400-f177fbaf-c4df-415c-8e56-66a8e904171e.png)<br>
- table 행 선택 삭제하기<br>
![image](https://user-images.githubusercontent.com/108508922/178642445-23b77312-5a30-4c21-abcc-f04d682a6947.png)<br>
- table 삭제, 롤백<br>
![image](https://user-images.githubusercontent.com/108508922/178659664-2a926558-afd1-4170-a785-a27bb597f555.png)
- dual table<br>
![image](https://user-images.githubusercontent.com/108508922/178661727-f42056fb-afdf-4ad2-8d24-51b46e6bdc87.png)
-순차적으로 순차적으로 반환해주는 seq<br>
![image](https://user-images.githubusercontent.com/108508922/178662232-13e0e556-5551-4939-8ee7-536a0938a308.png)
-관용적 약어표현<br>
![image](https://user-images.githubusercontent.com/108508922/178664518-e947b1d0-ecae-4f72-ba73-bb4427237830.png)
- 선택자 퀴즈<br>
- 예제1~4)<br>
![image](https://user-images.githubusercontent.com/108508922/178670997-d6d28c39-9aaa-4a11-b788-e6c4aabcdbe2.png)<br>
- 해설1~4)<br>
![image](https://user-images.githubusercontent.com/108508922/178671124-59cd9f49-f694-492b-ace7-2ec22360dce6.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178671192-6984bf18-22be-4d54-9fbb-2e6e45e40b71.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178671258-4e2e551f-e42f-4192-98ad-e85aefa560d3.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178671330-a4661aaa-dd43-447b-a98d-70d7e9eec901.png)<br>
- where절 퀴즈<br>
- 예제1~2)<br>
![image](https://user-images.githubusercontent.com/108508922/178673478-acdd8972-0b1e-4d89-a129-4ed0dd278165.png)<br>
- 해설1~2)<br>
![image](https://user-images.githubusercontent.com/108508922/178673564-642b77fd-a73f-4eae-a84a-a7c5d2776693.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178673614-613753c4-d2ea-4d0b-affb-c7697e0fbef0.png)<br>
- 예제3~4<br>
![image](https://user-images.githubusercontent.com/108508922/178676580-47c3eaf5-2d8a-49e9-9bc4-c6a36e84e642.png)<br>
- 해설3~4<br>
![image](https://user-images.githubusercontent.com/108508922/178676642-43f5464d-98d3-4e63-bdf7-a0f09b3a4319.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178676731-351faab9-0ead-4142-a2b5-6fb676cd3338.png)<br>
- select from where 실행순서<br>
![image](https://user-images.githubusercontent.com/108508922/178672283-1390d1f1-ae4d-4b1a-a56a-509448e12e1a.png)<br>
- 기본형식 실행순서<br>
![image](https://user-images.githubusercontent.com/108508922/178672489-af07a157-cea2-433c-83d5-ef5c14072bef.png)<br>
- ALIAS 사용하기<br>
- 예제1)<br>
![image](https://user-images.githubusercontent.com/108508922/178677939-95c1090d-f8e3-4abc-9235-64e863194871.png)<br>
- 해설1)<br>
![image](https://user-images.githubusercontent.com/108508922/178677601-f21f45ff-1214-4b2e-9c02-0b075963963d.png)<br>
- 연산자<br>
- 예제1)<br>
![image](https://user-images.githubusercontent.com/108508922/178678114-71de74ee-c02a-49e8-b68d-c965cc34cef4.png)<br>
- 해설1<br>
![image](https://user-images.githubusercontent.com/108508922/178678477-a3bd3f44-53d7-474d-96c7-c8e289c64bad.png)<br>
- 예제2~3)<br>
![image](https://user-images.githubusercontent.com/108508922/178693095-5e8b0810-512b-4b5f-95dd-782722f1d928.png)<br>
- 해설2~3)<br>
![image](https://user-images.githubusercontent.com/108508922/178693520-483bf3dd-e4ab-4474-b20a-169102b65ad7.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178693661-ba95db1d-5876-49f1-af8e-dfe38749b3cf.png)<br>
- 예제4~5)<br>
![image](https://user-images.githubusercontent.com/108508922/178693810-03fdbd84-ff07-4232-9dee-5d7345a75394.png)<br>
- 해설4~5)<br>
![image](https://user-images.githubusercontent.com/108508922/178693983-e950ff8f-7008-4900-991b-778f82a5d6a5.png)<br>
- 예제6)<br>
![image](https://user-images.githubusercontent.com/108508922/178694077-df977e8a-15b4-439f-bbef-b469be5c340b.png)<br>
- 해설6)<br>
![image](https://user-images.githubusercontent.com/108508922/178694250-d3bb87c7-16c8-4bf2-ba75-b312bb4284a9.png)<br>
- 예제7~8)<br>
![image](https://user-images.githubusercontent.com/108508922/178694384-9b2eb263-7da3-4629-9582-d9e47749cbb6.png)<br> 
- 해설7~8)<br>
![image](https://user-images.githubusercontent.com/108508922/178694508-805c7ab1-fcd7-4c60-95e8-63688d6ba2b9.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178694609-102513e8-9d87-474e-aa00-7643ae07e9f7.png)<br>
- 예제9~10)<br>
![image](https://user-images.githubusercontent.com/108508922/178694878-689f3551-a3df-47ac-bcd0-b3c4bffc2d31.png)<br>
- 해설9~10)<br>
![image](https://user-images.githubusercontent.com/108508922/178695000-143d16ab-f787-418a-a083-a23d7b467c1b.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178695050-0fbe6272-e569-486d-a8d0-c9ffaca3488b.png)<br>
- 예제11~12)<br>
![image](https://user-images.githubusercontent.com/108508922/178695188-257d416f-cbb5-4f70-a182-4b376f44fc37.png)<br>
- 해설11~12)<br>
![image](https://user-images.githubusercontent.com/108508922/178695264-cabbb0c7-0153-4697-9e2e-b158698e55e9.png)<br>
- 예제13)<br>
![image](https://user-images.githubusercontent.com/108508922/178695342-a5872908-1089-491d-8ec7-1aeb53bbaef4.png)<br>
- 해설13)<br>
![image](https://user-images.githubusercontent.com/108508922/178695449-0a79677c-3908-43ec-8440-c9a711f9ae7f.png)<br>
- 예제14~15)<br>
![image](https://user-images.githubusercontent.com/108508922/178695582-86c86fc5-d08a-4c02-a972-c11f0d8418c5.png)<br>
- 해설14~15)<br>
![image](https://user-images.githubusercontent.com/108508922/178695692-de7bb79f-7442-486d-965a-355cb85678eb.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178696075-82df725a-ed81-4d94-b662-3baf78a79dc7.png)<br>
- 예제16~18)<br>
![image](https://user-images.githubusercontent.com/108508922/178696371-278e543d-0a58-4a28-a4d7-ea735428ad4e.png)<br>
- 해설16~18)<br>
![image](https://user-images.githubusercontent.com/108508922/178696754-d305684a-ffb2-4c87-8a45-f1912819b1b1.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178697041-d15b83d0-9ac3-4b8f-8736-624592e4b28a.png)<br>
![image](https://user-images.githubusercontent.com/108508922/178697105-ebfb2a90-04a1-4aa5-b64b-073668cdea90.png)<br>
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
##데이터베이스_02
- join
- ansi join
   1)inner join 
      1)where 절에 join을 하는 복잡한 코드를 적지 않아도 된다.
   2)using
      1) 동일한 컬럼명을 가지고 있을때 사용 가능하다
   2)outer join
      1) 행이 추가되는쪽에 (+)를 붙여준다
      2) (+)가 붙는쪽으로 left or right 써주고 (+)는 생략
- self join
   1) 테이블의 별칭을 지어주고 조인시킨다.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- join 기본 표현방식<br>
![image](https://user-images.githubusercontent.com/108508922/179124935-65b52c12-d0bd-45f9-b337-9afa123eb7d3.png)
- ansi join using()<br>
![image](https://user-images.githubusercontent.com/108508922/179125013-b5aa5101-3993-4f39-86d6-7eb1b4d7d8e0.png)
- self joing<br>
![image](https://user-images.githubusercontent.com/108508922/179126709-024d3834-f98f-4cb9-bc16-d41e2d12c821.png)
- outter join<br>
![image](https://user-images.githubusercontent.com/108508922/179126997-c583b8e5-3479-465a-81cc-542275eb988a.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
##데이터베이스_03
- rownum: 행번호을 부여하고 싶을때 쓰는 함수
- 서브쿼리의 결과가 다중행을 가질때 동등연산자 (=)을 사용할 수 없다,대신 in, all, any, exist 의 다중행 연산자를 사용한다
   1) in:같은지 비교하고 싶을떄
- 관계형 데이터베이스
- DML
primary key: 중복과 null 둘다 허용하지 않음
unique: 중복만 허용하지 않음
not null: null만 허용하지않음
references tablename(column name): 제약조건
not null + uniq
- USER_TABLES만들어져 있는 테이블 조회
- USER_SEQUNECES만들어져있는 시퀀스 조회
- USER_CONSTRAINTS제약조건의 정보를 조회  
create 생성
drop 삭제
alter 개체를 수정(ex)table)
   modify 컬럼type 수정
   rename a to b : column 이름을 a에서 b로 변경
   drop:컬럼 삭제 
   add(constraint table수준의 constraint 추가): column에 제약조건 추가하기 
modify : 컬럼을 수정
update : ?

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

- LEAD , LAG , OVER<br>
![image](https://user-images.githubusercontent.com/108508922/179143282-77b65343-06f7-4f70-8925-2b000a7db5fb.png)
- 제약조건 명명하는 2가지 방법<br>
![image](https://user-images.githubusercontent.com/108508922/179178522-84da5ef4-c982-4351-afcb-4fda34319944.png)


교육 ing...


