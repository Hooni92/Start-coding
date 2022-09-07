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
 git reset --hard 돌아가고싶은 commit 번호or별칭 (commit만 되었으면 언제든지 돌아갈 수 있다)  
 git reflog (HEAD의 과거이력을 전부 표기)
 git log 
 git log --oneline (log 한줄표기)
 
- 커밋없애기
   1)commit 삭제 후 commit
   2)commit 취소
   3)github에 push를 했다면 취소하는 commit를 만드는게 좋다.
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
 - document.querySelector("CSS형식 선택자 ex)요소명,#id,.class,...")
  JS영역에서 HTML 영역에 있는 해당요소를 가져온다.
 - document.querySelectorAll("문자열 CSS 선택자")
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
- 명령 프롬프트
- 관리자로 로그인해서 사용자 계정만들기
   1) CMD 우클릭 속성 
   2) 빠른 편집모드 삽입모드 체크 
   3) sqlplus.exe 
   4) 사용자명:system 비밀번호:oracle 
   5) 사용자 계정 만들기 
   6) CREATE USER 아이디 IDENTIFIED BY 비밀번호; GRANT CONNECT, RESOURCE TO 아이디;(접속과 권한을 acorn에게 주겠다).<br>
   7) 사용자 계정으로 접속하기<br>
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
  1) desc 테이블이름 (테이블 확인하기)
  2) insert into tablename<br>
     (컬럼명, 컬럼명,...)<br>
     values (입력값, 입력값,...);<br>
  3) tip) ed->메모장 수정 후 저장 닫기 -> /엔터
  4) commit 전까지는 임시 수정이다
- 수많은 회원정보중 한사람을 삭제시키려면 primary key값을 삭제 
- dummy라는 컬럼을 가진 table dual을 제공한다. (console.log처럼 입력값을 확인해볼수있음)
- scott 계정만들기
   1) 관리자로 접속 
   2) @scott파일 경로 ex) @C:\oraclexe\app\oracle\product\10.2.0\server\RDBMS\ADMIN
   3) 새 명령프롬프트 -> 아이디 비밀번호 입력후 접속
- (1) Select 
   1) 불러 오고자 하는 Column name을 입력한다
- (2) Where
   1) 값이 ture인 row만 불러온다.
- (3) Order by 
   1) asc(오름차순) or desc(내림차순)
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
## 데이터베이스_02
#### 수업 요약
- join
- ansi join
   1)inner join 
      1) where 절에 join을 하는 복잡한 코드를 적지 않아도 된다.
   2)using
      1) 동일한 컬럼명을 가지고 있을때 사용 가능하다
   2)outer join
      1) row를 받는쪽에 (+)를 붙여준다
      2) row가 추가되는쪽으로 left or right 써주고 (+)는 생략
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
## 데이터베이스_03
#### 수업 요약
- rownum: 행번호을 부여하고 싶을때 쓰는 함수
- 서브쿼리: 하나의 SQL문장절에 포함된 또다른 SELECT문장, 따라서 두번 질의를 한번의 질의로 해결이 가능하다.
   1) Main-Query = Outer Query , Sub-Qury = Inner-Query
   2) 반드시 괄호로 묶어야한다.
   3) 서브쿼리 위치
      1) select / delete / update 문의 from 절과 where 절
      2) select 문의 having절
      3) insert 문의 into 절
      4) update 문의 set절
   4) 종류
      1) 단일행 서브쿼리:서브쿼리의 결과가 하나의 컬럼과 하나의 행만을 리턴해주는 쿼리
      2) 복수행 서브쿼리:서브쿼리의 결과가 하나의 컬럼과 여러개의 행을 리턴해주는 쿼리
   5) 서브쿼리의 결과가 다중행을 가질때 동등연산자 (=)을 사용할 수 없다
   6) 대신 in, all, any, exist 의 다중행 연산자를 사용한다
      1) in: 비교조건이 서브쿼리의 결과중에서 하나라도 일치하면 true
      2) all: 비교조건이 서브쿼리의 결과와 모두 일치하면 true
      3) any: 비교조건이 서브쿼리의 결과와 하나 이상이 일치하면 true
      4) exist: 비교조건이 서브쿼리의 결과중에 하나라도 만족하는 값이 존재하면 true
- 데이터 모델
   1) 계층형
      1) 추후 개인학습
   2) 네트워크형
      1) 추후 개인학습
   3) 관계형
      1) 특징
         1) 행과 열을 가진 2차원 표에 데이터를 저장하는 모델.
         2) 여러가지 표를 조합하여 데이터를 유연하게 대응할 수 있다는 특징이 있다.
         3) 독립적으로 관리가 쉽다
- DML
primary key: 중복과 null 둘다 허용하지 않음
unique: 중복만 허용하지 않음
not null: null만 허용하지않음
references tablename(column name): 제약조건
not null + uniq
- USER_TABLES만들어져 있는 테이블 조회
- USER_SEQUNECES만들어져있는 시퀀스 조회
- USER_CONSTRAINTS제약조건의 정보를 조회  
- create 생성
   1) create user
   2) create table
   3) create sequence
- drop 삭제
   1) drop user
   2) drop table
   3) drop sequence
- alter 개체를 수정(ex)table)
   1) alter modify: 컬럼type 수정
   2) alter rename a to b : column 이름을 a에서 b로 변경
   3) alter drop:컬럼 삭제 
   4) alter add(constraint table수준의 constraint 추가): column에 제약조건 추가하기 
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

- LEAD , LAG , OVER<br>
![image](https://user-images.githubusercontent.com/108508922/179143282-77b65343-06f7-4f70-8925-2b000a7db5fb.png)
- 제약조건 명명하는 2가지 방법<br>
![image](https://user-images.githubusercontent.com/108508922/179178522-84da5ef4-c982-4351-afcb-4fda34319944.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### 데이터베이스04, javascript_ecma6 Step01~02
#### 수업 요약
- data복사
   1) 내용 복사:insert into member2 select * from member;
   2) 테이블 복사:create table member3 as select * from member;
   3) 테이블 구조만 복사:create table emp2 as select * from emp where 1=2;

- 오라클 시작 안될때   
   1) 탐색기
   2) 내PC 우클릭
   3) 관리
   4) 서비스 및 응용프로그램
   5) 서비스
   6) Oracleservice, oraclelistener 실행
   
- arrow function
   1) fucntion(){} = ()=>{}
   2) 주의사항 
      1) const divs=document.querySelectorAll(".box");<br>
           for(let i=0; i<divs.length; i++){<br>
              divs[i].addEventListener("click", ()=>{<br>
                  console.log(this);<br>
              })<br>
          }<br>
      2) 화살표 함수 안에서 this는 이벤트가 일어난 바로 그요소를 가르키지 못한다
        
- 람다함수
   1) 함수안에 복잡한 javascript가 없을때 한줄로 표현할 수 있다.
   2) let 변수명 = (num1, num2) => 리턴값;

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- 내용복사 
![image](https://user-images.githubusercontent.com/108508922/179457009-68412bf7-ee0f-46f0-b6cd-ab6b11adce13.png)
- 테이블복사
![image](https://user-images.githubusercontent.com/108508922/179457180-0a30448d-9292-47ee-922c-4bd0308e1136.png)
- 테이블 구조만 복사<br>
![image](https://user-images.githubusercontent.com/108508922/179456734-42910426-42a5-41ee-8b34-8cab86bbd821.png)
- 오라클실행오류
![image](https://user-images.githubusercontent.com/108508922/179460050-e506436b-577f-41b9-adca-d0fe946bf40c.png)
-
![image](https://user-images.githubusercontent.com/108508922/179461990-b5f4fd3a-4e9c-44ae-a7ea-7f7a936abefb.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### javascript_ecma6 Step03~09
#### 수업 요약
- array
   1. map 함수
      1. 배열은 map() 함수를 원래 가지고 있다.
      2. map() 함수를 호출하면서 함수를 전달 해야한다.
      3. 전달하는 함수는 배열의 size 만큼 즉시 반복 호출된다.
      4. 반복호출 되면서 그함수에 배열에 저장된 item을 순서대로 전달 해준다.
      5. 함수안에서 리턴해주는 값을 순서대로 모아서 새로운 배열을 map() 함수를 리턴해준다. 
      
  2. filter 함수
      1. 배열의 filter() 함수는 조건에 맞는 item으로 새롭게 구성된 배열을 리턴한다. 
      2. true가 리턴된 index 의 item 으로만 구성된 배열이다.
   
- object
   1. 객체를 분해해서 할당하기
      1. let mem={num:1, name:"김구라", addr:"노량진"};
      2. let {num, name}=mem;
      
   2. value를 변수 선언 후 object에 할당하기
      1. let num=1;<br>
         let name="구라 킴";<br>
         let isMan=true;<br>
      2. let mem2={num, name, isMan, sing(){}};
      
   3. key값을 변수 선언 후 object에 할당하기
      1. let a="num";<br>
         let b="name";<br>
         let c="isMan";<br>
      2. let mem3={[a]:2, [b]:"해골", [c]:false};

-function 
         
- templateString
- for
- promise
비동기 작업
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- array map함수<br>
![image](https://user-images.githubusercontent.com/108508922/179891963-61188c87-a857-4842-927b-f381fd0e3de3.png)
- filter 함수<br>
![image](https://user-images.githubusercontent.com/108508922/179891880-b78afa7c-9505-481a-a03e-2e28cc0ced45.png)
- 객체를 분해해서 할당하기<br>
![image](https://user-images.githubusercontent.com/108508922/179894786-f2d2a878-27d8-458c-a72e-ce4e1e77777c.png)
- value를 변수 선언 후 object에 할당하기<br>
![image](https://user-images.githubusercontent.com/108508922/179895408-535e0fc4-17c0-40f9-8118-5d78572d806e.png)
- key값을 변수 선언 후 object에 할당하기<br>
![image](https://user-images.githubusercontent.com/108508922/179895466-5b5565f6-178d-4d6b-9319-3239b2f1d60b.png)

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### javascript_ecma6 
#### 수업 요약
javascript closure
JavaScript Object Notation(JSON) 문자열
XML
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### java 1
#### 수업 요약
- 이클립스설치
   1. 이클립스 설치 후 실행하여 work_space 설정 
   2. 설정은 window preference
   3. encording 설정 preference -> encording검색-> workspace ->text file encording ->other-> UTF-8
   4. font설정 preference->font설정 ->basic -> 맨밑 text font -> 더블클릭후 설정
   
- package
   1. src우클릭->new->package->test.main
   2. scr/test/main 이라는 폴더가 생성된다

- 예약어
   1. JAVA에서 예약된 예약어는 eclipse에서 빨간색으로 나타낸다
   2. 중복사용 불가
- class
- method

- java변수선언
   1. java에서는 변수 type을 확정하여 정해야한다.
   2. java는 정적언어 javascript는 동적언어라 한다.
   4. data type은 사용저가 만들수 있어 무한대 이지만 기본 data type은 정해져있다.
   3. ex)정수 = int num1=10;
   4. 실수 = double num2=10.4;
   5. 블리언type = boolean isRun=true;
   6. stringtyep = String myName="김구라"; (String은 예약어가 아니다)

- 디버깅
   1. breakpoint 설정후 풍뎅이 아이콘 debug as
   2. F6키로 실행 순서 대로 실행.
   3. variable 창에서 변수들 확인.

- 환경리셋
   1. window
   2. perspective
   3. rest perspective
 
- 기본 데이터 타입(java primitive data type)
   1. 숫자
      1.정수
         1. byte
         2. short
         3. int
         4. long
      2.실수
         1. float
         2. double
   
   2. 논리
      1. boolean
      
   3. 문자
      1. char

- object(객체)
   1. 참조 data 안에 들어있다
   2. 저장소 (어떤 값) - field
   3. 기능 (어떤 동작) - method
   4. 참조값에 .을 찍으면 저장소나 기능을 이용하겠다라는 뜻이다.
   
- 지역변수
   1. java는 전역변수가 없다 지역변수 아니면 field
   2. method 안에서 만들어지는 지역변수는 stack 영역에 만들어진다.
   3. 지역변수는 메소드가 실행중에 만들어졌다가 해당 메소드가 종료(리턴)되면 사라진다.
   4. public static void main(String[] args) {//지역변수 영역}
   5. 변수를 선언하고 값을 넣지않으면 만들어지지 않는다.(javascript는 undefined값이 들어간다)
   6. 값을 넣는 시점에 변수가 만들어진다. 
   7. 지역변수를 미리 만들고 필요한 값을 나중에 넣고 싶으면 초기값을 대입하는게 좋다
   8. 숫자type=0; , 참조type=null;

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- workspace <br>
![image](https://user-images.githubusercontent.com/108508922/180112900-2e6f6fd1-df1d-4b60-b7f5-b9ff8763083a.png)
- java 변수선언<br>
![image](https://user-images.githubusercontent.com/108508922/180126937-11dee6f3-453d-4730-8d2c-debe1fca438c.png)<br>
![image](https://user-images.githubusercontent.com/108508922/180121789-c767f01e-ade4-47fa-bf84-834c45a25556.png)
- 디버깅<br>
![image](https://user-images.githubusercontent.com/108508922/180126785-3fc34b61-0d7a-49fc-b4ec-4fb8613e2ec2.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### java 2 
#### 수업 요약

- thread

- 3항 연산자: type result = boolean ? value1 : value2
   1. true면 value 1, false면 value2
   2. : 의 양쪽 data type이 같아야한다.
   
- class
   1. class의 역할
      1. 객체의 설계도 역할: 해당 클래스로 객체를 만들었을때(new) 어떤 field 와 어떤 method를 가지게 할지 설계 할 수 있다.
      2. data type 역할: 
         1. 지역변수나 필드를 만들떄 선언하는 data type의 역할을 할 수 있다. 
         2. 변수나 필드에 저장된 값의 사용 설명서에 해당된다.
      3. static필드나 static 메소드를 포함하는 역할: 필요에 따라서 객체에 필드나 메소드를 만들지 않고 클래스 자체에 만들어 놓을 수도 있다.

- static, stack, heap
   1. static : class
   2. stack : local variable
   3. heap : object

- 가상의 Calculator 만들기
   1. 다른 package의 Calculator class를 사용하기 위하여 수입하여야 한다.(import)
   2. 객체를 생성: new Calculator() -> heap 영역에 사물함에 객체가 만들어지고 참조값이 return 된다.
   3. 참조값을 지역변수에 넣기 위하여 class명이 type인 변수를 만든다.ex)Calculator cal = new Calculator
   4. public String brand="샤오미"; (필드값)
         
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- 참조값의 method 활용법<br>
![image](https://user-images.githubusercontent.com/108508922/180351211-c8a3ded2-7510-4d46-afb5-2b34f4a33d59.png)
- Calculator class class<br>
![image](https://user-images.githubusercontent.com/108508922/180385546-a50f02d4-234d-4fd1-a3d9-d4361333ba9c.png)
- main class<br>
![image](https://user-images.githubusercontent.com/108508922/180385705-87b17c23-eafd-4e7a-8bc6-2937b6282fec.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### java 3
#### 수업 요약

- 접근지정자
   1. Public (공개)
   2. default (같은 Package에서만 사용)
   
- void 
   1. 어떤 값도 돌려주지 않겠다.
   2. 따라서 변수 type을 정해서 담을 수 없다.
   
- this는 객체 자신의 참조값을 가르키는 예약어

- 우리가 앞으로 사용할 클래스는 모두 직접 만들어야 하나?
   1. java 에서 기본으로 제공 되는 클래스는 import 해서 사용하거나
   2. 추가로 필요한 유틸리티를 인터넷에서 다운 받아서 import 후 사용하거나
   3. 우리가 직접 만들어서 사용하기도 한다.
   
- java로 프로그래밍을 하는 방법
   1. heap 영역에 있는 객체의필드나 메소드를 활용해서 원하는 동작을 하거나
   2. static 영역에 있는 클래스의 static 필드나 static 메소드를 활용해서 원하는 동작을 한다.
   3. 특정 작업을 할 때 어떤 type 객체가 필요한지를 학습해야 한다.
   4. 어떤 type 객체의 참조값을 어떻게 얻어내는지를 학습해야하 한다.
      1. 필요한 객체를 직접 new 하거나,
      2. 이미 생성된 객체를 참조하거나
      3. 메소드를 호출해서 리턴되는 객체를 주로 활용한다.
   5. ex) [랜덤한 정수를 하나 얻어내서 콘솔창에 출력하는 프로그래밍을 하고 싶다]
      1. 필요한 객체
         1. 랜덤한 정수를 만들어주는 객체 (new Random();)
         2. 콘솔창에 문자열을 출력해주는 객체 (system.out)
   6. ex) [키보드로 부터 문자열을 입력 받아서 콘솔창에 출력하는 프로그래밍을 하고 싶다]
      1. 필요한 객체
         1. 키보드로 부터 문자열을 입력 받는 기능을 가지고 있는 객체 (new Scanner();)
         2. 콘솔창에 문자열을 출력해주는 객체 (system.out)
        

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- System.out.println()구조<br>
![image](https://user-images.githubusercontent.com/108508922/180914420-abd218bc-8961-4892-a8ee-b759cdd6708a.png)
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
### java 4
#### 수업 요약

- [생성장]
  1. 클래스명과 동일하다.
  2. 메소드 모양과 유사 하지만 리턴 type이 없다.
  3. 객체를 생성할때(new 할때) 호출된다.
  4. 객체를 생성하는 시점에 무언가 준비 작업을 할떄 유용하다.
  5. 생성자를 명시적으로 정의 하지 않아도 기본 생성자는 있다고 간주된다.

- wrapper class
 1.[기본 data type 의 참조 data type]
    1. byte   :Byte
    2. short  :Short
    3. int    :Integer
    4. long   :Long 
    5. float  :Float
    6. double :Double
    7. char   :Character
    8. boolean:Boolean
      1. 때로는 기본 데이터 type 의 참조데이터 type이 필요할 떄가 있다.
      2. 기본데이터 type 을 객체에 포장(boxing)하는 형태이다
      3. boxing 과 unboxing은 자동으로 되기 때문에 프로그래머가 신경을 쓸 필요는 없다.
      
- arry(배열)
   1. 중괄호 안에 배열을 정의한다.{item, item2, ... }
   2. 참조 data type, 하지만 class는 없다.
   
----------------------------------------------------------------------------------------------------------------------------------------------------------------------- 
### java 5
#### 수업 요약

- 접근지정자
   1. 기본 접근지정자
      1. public : 어디에서나 접근 가능 
      2. protected : 동일한 package 혹은 상속관계에서 자식에서 접근 가능 
      3. default : 동일안 package 안에서만 접근 가능
      4. private : 동일한 클래스 혹은 동일한 객체 안에서만 접근가능 
   2. class의 접근지정자
      1. public
      2. default
   3. 생성자의 접근지정자.
      1. public
      2. default (new를 할 수 없다.)
      3. priveate (new를 해당class 안에서만 가능하다)
   4. 위치 
      1. 클래스를 선언 할때
      2. 생성자
      3. 필드
      4. 메소드 

- over loading
   1. 생성자가 여러개, 다중 생성자.
   
- DTO(Data Transfer Object) 클래스 만들기
  1. 필드의 접근 지정자를 private 로 설정한다.
  2. default 생성자가 있어야한다.
  3. 필드에 저장할 모든 값을 전달 받는 생성자가 있어야 한다.
  4. 필드의 값을 접근 할 수 있는 getter, setter 메소드가 표준에 맞게 작성되어야 한다.

- extends
   1. a extends b : b를 상속받은 a
   2. 어떤 클래스도 상속 받지 않으면 자동으로 extends Object된다.
   3. 다형성:여러가지 형태를 가질 수 있는 능력, 조상 타입 참조 변수로 자손 타입 객체를 다루는 것
   4. 부모 class에 default 생성자가 없어지면 문제가 생길수 있다.
   
- super
   1. this가 자신의 참조값을 가르키는 예약어이고, super는 부모를 가르키는 예약어.
   2. super()=부모생성자를 호출하는 것을 의미
   

----------------------------------------------------------------------------------------------------------------------------------------------------------------------- 
- extends<br>
![image](https://user-images.githubusercontent.com/108508922/181431719-c9dc3bc4-e247-4a3f-a4ba-6b07bd0a8c50.png)
- 예약어 super<br>
![image](https://user-images.githubusercontent.com/108508922/181450674-c4796cd0-cbdd-43a3-9044-ca145cf8ca7c.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------- 
### java 6
#### 수업 요약

- abstract 
   1. abst
   2. abstract 클래스는 객체를 생성할 수 없다.
   3. 따라서 자식 클래스를 생성하여 상속한뒤 abstract 메소드를 Override 한다.
교육 ing...

- interface
   1. 생성자가 없다 (단독 객체 생성 불가)
   2. 구현된 메소드는 가질수 없다 ( 추상 메소드만 가질수 있다 )
   3. final
      1. 값이 변하지 않는 상수를 지정할 때 쓰이는 예약어.ex)javascript에서 const와 같다.
   4. 필드는 static final 상수만 가질수 있다.
   5. data type  의 역활을 할수 있다.
   6. interface type 의 참조값이 필요하면 구현(implements) 클래스를 만들어서
   7. 객체를 생성해야 한다.
   8. 클래스 상속은 단일 상속이지만, 인터페이스는 다중 구현이 가능하다
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### java 7
#### 수업 요약

- @FunctionalInterface
  1. 함수 모양으로 사용 할 인터페이스에 붙이는 어노테이션
  2. 추상메소드가 1개인 인터페이스다.
  3. 추상 메소드의 갯수가 1개로 강제된다.
  4. 추상메소드가 1개인 인터페이스는 javascript의 arrow function과 같이 override를 표현 할 수 있다.
 
- GenericClass 
   1. 클래스명<T> T로 임시적인 type을 정해주고 나중에 전달받을 type을 T에 넣어준다.
   2. 객체를 생성할때 Generic 클래의 type은 생략가능하다.ex) 클래스명<Apple>generic= new 클래스명<>

- ArrayList
   1. javascript의 배열[index[0],index[1],...] 생성과 비슷하다.
   2. .add(배열에 추가), .get(배열값 indext번호로 불러오기), .remove(인덱스값의 내용삭제), .clear();전체삭제
   3. List interface에 대부분의 기능이 실려있어서 List type으로 가져와도 활용가능하다.
   4. 기본 데이터 type은 저장할 수 없으므로 저장 하고 싶으면 Wrapper Class를 활용한다.

- Scanner
   1. Scanner(System.in) 객체를 생성하여 .nextLine();으로 문자열을 입력받고, 출력할수 있다.
   
- for(type 변수명:배열명)
   1. 배열의 값을 하나씩 가져온다.
 
- HashMap 
   1. javascript의 객체{key1:value1, key2:value2,...} 생성과 비슷하다.
   2. value 값을 Object로 설정하면 int type, String type 상관없이 넣을 수 있지만. 넣은 값을 사용할땐 casting 해주어야한다.

- hashSet 
   1. Set 인터페이스를 구현한 클래스 이다. 
   2. 순서가 없다.
   3. key 값도 없다.
   4. 중복을 허용하지 않는다.
   5. 어떤 data 를 묶음(집합) 으로 관리하고자 할때 사용한다.
   
 - while
   1. (true)면 {}실행하는건 for문과 동일하다.
   2. for문은 반복횟수가 정해져있을때, while문은 반복횟수를 알 수 없을때.
   3. break : 인접한 블럭(반복문)탈출
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- array순서대로 하나씩 값을 가져올때<br>
![image](https://user-images.githubusercontent.com/108508922/182062184-0ac33c5f-b518-4085-939f-c1213a45af6b.png)
- Generic Class 
![image](https://user-images.githubusercontent.com/108508922/182110958-d382a0b3-7b0e-49bb-af53-97a1ed2f64d7.png)<br>
- Generic Class Main Class
![image](https://user-images.githubusercontent.com/108508922/182111434-fddd35bf-699a-44c1-86d1-02b864761005.png)

- javascript vs java<br>
![image](https://user-images.githubusercontent.com/108508922/182083581-77841309-3007-4d91-b17b-9fdc4a5bcde0.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### java 8
#### 수업 요약

- Iterator
   1. 컨테이너, 리스트를 순회하게 만들어 주는 객체
   2. 컬렉션에 요소를 제어한다.
   3. next(), previous() 로 앞 뒤로 이동 가능
   4. .hasNext()다음 칸에 데이터의 유무를 boolean type으로 리턴.
 
- Random 
   1. random한 숫자를 얻어내는 random객체

- Exception
   1. 모든사용자가 기능에 알맞게 사용하지 않으므로 예외상황을 생각해주어야한다.
   2. try{예외가 발생할 수 있는 상황}catch(NumberFormatException nfe){예외발생시 실행}
 
- throw
   1.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Iterator<br>
![image](https://user-images.githubusercontent.com/108508922/182273728-352ec3fe-9228-437c-b25a-d613d768367f.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### java 9
#### 수업 요약

- thread
   1. 하나의 thread는 하나의 order를 받으면 완료될때까지 다음 order를 받지 않는다.
   2. 여러개의 thread는 작업을 준비할때 여러개의 thread가 생겨 1번과 같은 작업을 한다.

- 새로운 스레드 만드는 방법1
   1. Thread 클래스를 상속 받은 클래스를 정의한다.
   2. run()메소드를 오버라이드 한다.
   3. run()메소드 안에서 새로운 스레드에서 해야 할 작업을 코딩한다.
   4. 만든 클래스로 객체를 생성하고 해당 객체의 start()메소드를 호출하면 새로운 스레드가 시작된다.
  
- 새로운 스레드 만드는 방법 2
  
   1.Runnalbe 인터페이스를 구현한 클래스를 정의한다.
   2.run()메소드를 강제 오버라이드 한다.
   3.Thread 클래스를 객체로 생성하면서 해당 클레스로 만든 객체를 생성자의 인자로 전달한다.
   4.Thread 클래스로 만든 객체의start()메소드를 호출해서 스레드를 시작시킨다.
 
- javascript vs java
   1. Javascript
   한명의 작업자가(하나의 스레드) A조금 B조금, C조금 일을 처리한다.
   그러다가 특정 작업이 종료가 되면 해당 작업이 종료된 후에 호출하기로 한 함수를 호출 하면서
   작엄의 결과를 함수에 전달해준다
   2. Java
   A,B,C 세개의 작업을 동시에 처리 한다고 가정하면
   3명의 작업자(3개의 스레드)가 각각 A작업,B작업,C작업을 처리한다
   1명의 작업자가 일을 할때는 다른 2명의 작업자는 얼어 버린다.
   3 명의 작업자가 아주 빠른 주기로 일하다 얼었다를 반복하면서 일을 처리한다.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- WebServer Client요청 처리방법<br>
![image](https://user-images.githubusercontent.com/108508922/182555998-7202d20d-8eb8-4116-85d8-44594f04c444.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### java 10
#### 수업 요약
- InputStream : 1byte 문자를 int type으로 받는 객체
- InputStreamReader: 2byte 문자를 int type으로 받는 객체
- BufferdReader: 문자열 1줄씩 입력받을 수 있는 객체
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
= 1byte , 2byte 문자 처리<br>
![image](https://user-images.githubusercontent.com/108508922/182745173-1e18b1e9-e19e-45e0-9d10-76f02531a734.png)
![image](https://user-images.githubusercontent.com/108508922/182747523-240d3c3a-0c52-42c1-87f8-b09c6624576a.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### java 11
#### 수업 요약
- ojdbc6.jar file 적용시키기
   1. src 폴더 우클릭.
   2. bulid path 
   3. Configure bulid path
   4. Libraries tab
   5. Modulepath 클릭
   6. add External JARs

- executedUpdate
   1. insert, update, delete 문에 사용
   2. int type return:변경된 row의 갯수
   3. autocommit 기능이있다.
   4. autocommit 기능을 하지 않으려면 setAutocommit(false); 후 -> commit();할 수 있다
   
- executeQuery()
   1. select 문에 활용
   2. ResultSet return: select문을 수행한 결과
      1. .next() cursor를 내린다.
      2. .getString(칼럼명), .getInt(칼럴명) cursor가 위치한 colum 정보를 가져온다.
   
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- resultSet cursor<br>
![image](https://user-images.githubusercontent.com/108508922/183319312-e7039142-9750-4354-ac4f-3c58c3a78906.png)
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### java 12
#### 수업 요약
- Q&A
   1. 확장 for문:순서대로 불러오고 싶을때 사용한다.for(변수타입 변수명:반복대상){실행문} 반복대상=>배열이나 컬렉션
   2. Static Method: new로 호출하지 않고 클래스명.(점)을찍어 호출한다.
   3. InnerClass: Class안의 Class를 정의, Method 안의 Class 정의
   4. array: 생성시점에 방의 갯수가 정해진다. (index관리)
   5. List: add하거나 지울때 방의 갯수가 유동적여진다. (index관리)
   6. Map: 순서가 중요치 않은 값을 관리하고 싶을때 사용한다 (key:value관리)
   7. interface: abstract method만 정의할 수 있다. static final필드만 가질 수 있다.<br>
      클래스가 만들어야 하는 메소드의 형식을 강제 하는 역할,<br>
      즉 어떤 클래스를 만드는 프로그래머가 메소드의 모양을 <br>
      자기 마음대로 만드는게 아니고 인터페이스에 정의된 모양대로 만들 수 있도록 한다.
   8. Thread: 스레드는 눈에 보이지 않는 어떤 실행의 흐름(작업단위)이다.<br>
      어떤 application이 시작 되었다는 것은 <br>
      누군가가 미리 준비된 java code를 순서대로 실행한 것이다.<br>
      누가 순서대로 실행을 했나? 그게 바로 스레드이다.<br>
      main 메소드에서 시작된 실행의 흐름을 main 스레드 라고한다.
   9. try{<br>
      여기에서 발생할 가능성이 있는Exception type을 <br>
      }catch(여기에 type을 선언하고){<br>
      해당Exception가(이) 발생했을때 원하는 작업을 여기서 한다.
      }<br>
      try안의 발생하는 Exception 여러개면 catch에서 세부적으로<br>
      exception 종류별로 만들어 처리할 수 있다.
   10. generic: class 설계 단계에서 type을 유동적으로 전달받을 수 있다.<br>
       클래스 정의할때 Type을 <T>로 정의하면, <br>
       필드. 메소드 type을 T로 유동적으로 정할 수 있다. <br>
       추후 main class에서 타입을 전달해준다."
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Web Programing 1
#### 수업 요약
- web server연걸
   1. 이클립스 work_space를 설정하면 encording을 우선적으로해준다.
   2. server -> 우클릭 ->new server
   3. apach -> tomcat 8.5 -> 브라우저 설정으로 위치지정
   4. server.xml -> source -> 63번줄 port설정(기본값 8080은 오라클과 연결되어있다)   

- 동일컴퓨터ip localhost=127.0.0.1
- servlet은 html 코드를 짜기 힘들다 그래서 jsp를 사용하여 자바 코드와 html 도 쉽게한다.
-----------------------------------------------------------------------------------------------------------------------------------------------------------------------
 - encording 해주기<br>
 ![image](https://user-images.githubusercontent.com/108508922/183786708-85dd5dc8-0ff9-4692-b938-11d452208dbe.png)
 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Web Programing 2
#### 수업 요약

- jsp
   1. <% 자바영역 %> + HTML
   2. 자바영역은 client에게 보여주지 않는다.
   3. 자바영역 주석 // , /* */, HTML 주석 <!-- --> , jsp주석 <%-- --%>
   4. jsp주석은 클라이언트에게도 공개되지 않는다.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- /fortune과 /fortune.html 응답 
![image](https://user-images.githubusercontent.com/108508922/184051761-39905f07-9813-46fc-9bb0-d1c73df4959c.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Web Programing 3~4
#### 수업 요약

- DB연결.
   1. 프로젝트 만들기: Dynamic Web Project
   2. jsp 파일 만들기: src-> main->webapp->jsp파일만들기
   3. ojdbc6.jar 파일 넣기: webapp/WEB-INF/lib폴더 클릭하고 ctrl+V
   4. xml 파일 불러오기: 프로젝트 폴더 우클릭-> java EE Tools -> Generate Deployment Descriptor Stub
   5. DB연동하기
      1. https://tomcat.apache.org/ -> tomcat 8.5 -> Apache Tomcat User Guide 섹션에 JDBC Data Source ->Oracle 8i, 9i & 10g
      2. Context configuration: 프로젝트의 -> Servers-> context.xml -> <Context>ctrl+v</Context> -> (url oracle명 수정) 
      3. web.xml configuration: 포로젝트의 -> 새로만든 프로젝트 -> src -> main->web.xml -> <web-app>ctrl+v</web-app>
      4. Code example: connection할 java DbcpBean class 생성 -> 필드, 생성자, 메소드 생성후 생성자안에 ctrl+V -> try&catch->ds.getConnection(); 지역변수 만드는거 수정해주기
      5. index.jsp에서 콜해서 연동확인하기.
   6 . 주의사항
      1. sever.xml 63line port번호 수정하기
      2. 

- ApacheTomcat은 context.xml, server.xml, web.xml 을 읽는다.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Web Programing 6
#### 수업 요약
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- context path 경로는 수정 혹은 지워진다.<br>
![image](https://user-images.githubusercontent.com/108508922/186043800-2f71b58e-8c1b-4c7c-889f-60f345e1844d.png)
- context path 얻어내는 두가지<br>
![image](https://user-images.githubusercontent.com/108508922/186043945-3200ca9b-cd0a-41a6-9c54-56afa09bd7b1.png)


----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Web Programing 7
#### 수업 요약

- setAttribute, getAtrribute, forward
   1. 최초의 요청을 서블릿에 하고 서블릿에서 로직을 수행하고 응답을 forward로 jsp에 넘겨주면 jsp에서 응답을 수행한다.
   2. req.setAttribute("key",value)
   3. RequestDispatchar rd=req.getRequestDispatcher("webapp 폴더의 파일경로")
   4. rd.forward(req, resp);

- request scope , session scope
   1. 웹 서버는 동시에 불특정 다수의 요청을 받고 응답하는 application 이다.
   2. servlet에서 req.getSession()으로 
   3. WEB-INF는 클라이언트에게 보여지지 않는 보안이 되어있따. forward를 통해 특정 jsp는 불러올수있다.
   
- jstl-1.2
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- setAttribute, getAtrribute, forward<br>
![image](https://user-images.githubusercontent.com/108508922/185524005-f0c4fcea-bc68-41ba-a561-eb61841a2b01.png)
- request scope , session scope<br>
![image](https://user-images.githubusercontent.com/108508922/185535049-f2ae4450-d021-40f1-b3fd-11b4650a7a56.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Web Programing 8
#### 수업 요약

- 이클립스에서 DB접속하는 플러그인설치
   1. http://quantum.sourceforge.net/
   2. 밑에 point eclipse at: 
   3. http://quantum.sourceforge.net/update-site 복사
   4. 이클립스 help
   5. install new software
   6. work with: 붙여넣기 enter
   7. 이클립스 재접속 후 QuantumDB환경들어가기
   8. new bookmark 아이콘클릭
   9. jar파일 찾아주기
   10. oracle.jdbc.driver.OracleDriver
   11. 아이디, 비번 입력후 이름 xe해주고 next
   
   


----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- js로 연결시켜주기<br>
![image](https://user-images.githubusercontent.com/108508922/185825855-34282479-c3ce-49bb-882a-73334085419c.png)
- 외부 파일 업로드<br>
![image](https://user-images.githubusercontent.com/108508922/185855834-37f12856-3d1b-4de3-a4a9-aefc09fdab98.png)
- 파일 데이타 형태
![image](https://user-images.githubusercontent.com/108508922/186046356-f0094221-cf12-4ae5-9788-9b659774e2a6.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Web Programing 9
#### 수업 요약

- 페이징 처리하는법
   1. 정렬하기
   2. 행번호 붙이기
   3. 원하는 범위의 행번호만 select 하기
   4. Dao에 적용하기 (단 ?에 들어갈 수열은 미리 만들어야한다)

#### Javascript 정규식
- 정규 표현식
   1. 정규표현식을 이해하면 정규표현식 객체를 활용해서 아래와 같은 작업을 할 수 있다.
      1. 어떤 문자열에 특정 pattern 의 문자 혹은 문자열이 있는지 여부를 알 수가 있다.  
      2. 어떤 문자열에서 특정 pattern의 문자 혹은 문자열을 추출 할 수가 있다.
      3. 어떤 문자열에서 특정 pattern과 정확히 일치하는지 여부를 알 수 가 있다.
   2. 예)
      1. 어떤 문자열에 특수문자가 포함되어 있는지 여부
      2. 어떤 문자열이 이메일 형식과 일치하는지 여부
      3. 어떤 문자열이 전화번호 형식과 일치하는지 여부
      4. 어떤 문자열이 영문자 대소문자와 숫자로만 이루어져 있는지 여부, 등등..

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- 행번호 붙이기<br>
![image](https://user-images.githubusercontent.com/108508922/186052365-3888f470-072e-4bf4-a8f4-7c2f450b5044.png)
- 원하는 범위의 행본호만 select 하기 <br>
![image](https://user-images.githubusercontent.com/108508922/186052709-24eae967-b4b7-46d8-bbd2-812da0e65c54.png)
- Dao select문에 적용 <br>
![image](https://user-images.githubusercontent.com/108508922/186052946-9c2c4558-f79f-48c0-a564-fe192f4b2f23.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Vue js
#### 수업 요약
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Spring 설치
#### 수업 요약

- java 설치
   1. 명령프롬프트에 java 를 치면 실행할수 없다고 나온다.
   2. https://jdk.java.net/java-se-ri/11 -> windows-64 jdk설치 -> 압축풀기
   3. jdk 경로 복사-> 윈도우 검색에 '환경'-> 시스템 환경 변수 편집 ->고급탭->환경변수->새로만들기 ->변수이름->변수값'자바경로 붙여넣기'
   4. path선택->편집->새로만들기->
   5. https://maven.apache.org/ -> download ->
   
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Spring 1
#### 수업 요약

- MVC (model, view , controller)
   1. 스프링 프레임워크에서 Model은 data
   2. View는 /WEB-INF/views/폴더안에 있는 jsp 페이지이고 
   3. Controller는 HomeController, AController.. 등 @Controller 어노테이션으로 만든 객체를 의미한다
- com.gura.myapp(마지막 문자열이 context path가 된다)
- 프로젝트의 M이란? Maven 프로젝트
   1. pom.xml 문서가 존재한다.
   2. pom.xml 에는 프로젝트의 설정, 주로 의존 라이브러리의 목록이 들어 있다.
   3. 필요한 읜존 라이브러리가 있다면, pom.xml에 <dependency></dependency> 안에 설정을 추가하 하는것 만으로 자동 다운로드 되고 사용할 준비가 된다.
   4. Maven 프로젝트를 만들기 위해서는 Maven을 다운로드해서 설치 해야한다. https://maven.apache.org 에서 다운로드 후 cmd에서 mvn입력하면 확인 할 수있다.
   5. pom.xml 에 dependency 설정을 할 문자열을 어떻게 얻어내야하는가?   
   6. https://mvnrepository.com/에서 필요한 설정을 검색해서 maven 코드를 복사하여 붙여넣기하면 된다.
   7. Libraries 의 Maven Dependencies 에서 설정한 목록을 확인할 수 있다.
   
- 왜 root요청에 대하여 webapp에 views 폴더의 home.jsp에서 응답을 했을까에 대하여 알아보자
   1. 시작점 web.xml 의 servlet설정으로 인하여 경로설정이 정해진다.
   
- DispatcherServlet은 미리 만들어 놓은 Servlet인데 만일 우리가 해당 서블릿의 동작을 바꾸고 싶으면 어떻게 해야할까?
   1. 미리 만들어진 Apache Tomcat 서버의 설정은 web.xml로 할 수 있듯이 DispatcherServlet의 동작도 xml 문서로 설정할 수 있다.
   2. Servle-context.xml 문서에 설정을 하면 된다.

- Servlet-context.xml 에는 스프링 프레임 워크가 작동하는데 있어서 필요한 설정을 하는 곳이다.

1. WebBrowser의 요청을 Tomcat Webserver의 DispatcherServlet에서 최초로 받고해당 요청을 처리할 Controller를 찾는다.
3. controller 영역에서는 응답할 필요할 data를 request영역에 저장하여 jsp페이지에 foroward한다.
2. /WEB-INF/views/ 안의 xxx.jsp로 응답을 위임시켜 jsp에서 response 한다.

- 왜 사용할까?
   1. 개발 단계에서는 까다롭고 코딩양이 증가하지만 한번 개발해 놓으면 유지 보수가 용의하다.
- 왜 유지보수가 용이할까?
   1. 객체들간의 의존관계가 느슨해 져서 용의하다 
- 어떻게 하면 객체들간의 의존관계를 느슨하게 할 수 있을까?
   1. 필요한 핵심의존 객체의 생성과 관리를 프레임 워크에게 맡긴다.
   2. interface type을 적극 활용한다.
  
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
![image](https://user-images.githubusercontent.com/108508922/187323731-536207f8-2533-437f-8345-4c95e26a996b.png)
- root요청 시작점 web.xml의 상속받은 요청 전달자 Servlet<br>
![image](https://user-images.githubusercontent.com/108508922/187326599-3277d1a5-09ee-4345-a49b-843d8d86f466.png)
- 접두어, 접미어 설정 <br>
![image](https://user-images.githubusercontent.com/108508922/187329072-75881ed5-1a92-4214-9dcd-1967073ec52d.png)<br>
![image](https://user-images.githubusercontent.com/108508922/187329302-da08c10b-4754-4d58-aed9-c53a414ad7bb.png)
- 응답경로<br> 
![image](https://user-images.githubusercontent.com/108508922/187330317-5bf2e94f-3494-4b70-a24d-9578fb50b07d.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Spring 2
#### 수업 요약
@Controller
@Repository
@RequestMapping
@Autowired
@Component
@Around("aspectj expression") : 어떤 메소드 주위에서 동작을 할지 
@Aspect
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

- 메소드명은 auth로 시작하고 리턴type은 ModelAndView,  (..)->메소드에 전달되는 인자와 타입은 자유이다. 인자중 하나는 반드시 HttpSevletRequest 인자가 있어야한다.
![image](https://user-images.githubusercontent.com/108508922/188351149-b86fcf9c-5aa2-4df9-aabe-c63284f73e31.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Spring 3
#### 수업 요약

ModelAndView
Service
<a href="/member/list.do">xxx</a> 에 대한 요청 처리
1. 해당 요청을 처리할 Controller 에 메소드 추가
2. Controller 에서 사용하는 Service에 메소드 추가
3. Service에서 사용하는 Service 메소드 추가
4. Mybatis를 사용하기 떄문에 Dao에서 사용하는 Mapper xml 에 sql 문 추가
5. forward이동될 jsp 페이지 추가
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- 요청에 따른 경로<br>
![image](https://user-images.githubusercontent.com/108508922/187848616-1fcc8a8a-1fbc-487d-8d32-255a40b02708.png)
- 의존관계<br>
![image](https://user-images.githubusercontent.com/108508922/187850348-e76b7648-d3c9-47d3-a5ad-d425505004fc.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Spring 4
#### 수업 요약

- 스프링 프레임 워크의 3대 핵심개념
   1. DI(Dependency Injection)
      1. 필요한 핵심 의존 객체를 주입 받아서 사용하는 구조

   2. IOC(Inversion Of Controller)
      1. 객체의 생성과 조립(DI 등등) 관리를 스프링이 실행될때 알아서 동작하는 구조
      
   3. AOP(Aspect Oriented Programming) 관점지향 프로그래밍
      1. 핵심비즈니스 로직과는 상관없는 횡단관심사를 따로 작성해 놓고 원하는 위치에 따로 작성된 로직을 설정을 통해서 적용 시키는 구조 이다.
      2. 주로 로그 기록이나, 테스트, 인증(auth) 등의 작업을 할 때 사용한다.
      3. ex) 수십개의 혹은 수백개의 메소드에 핵심 비즈니스 로직과는 상관없는 무언가 같은 작업을 해야 한다면 해당 작업을 따로 만들어 놓고 원하는 메소드에 설정만으로 적용시킬 수 있다면 편리하지 않을까?
      4. 횡단관심사(CrossCutting Concerns) 중요 비즈니스 로직과는 동떨어진 로직
 - Asepct가 어떻게 적용이 될까?
 1. spring AOP처리중 하나로 메소드 실행 직전 및 실행 직후 개입하여 정보를 조건부로 리턴한다.
 3. aspectj expression이 적용될 메수드에 부합이 되어야한다.
 4. aspect 객체는 spring bean 컨테이너에서 관리가 되어야 한다.
 5. 적용할 메소드를 가지고 있는 객체도 역시 spring bean 컨테이너에서 관리되는 객체여야한다.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- AOP code
![image](https://user-images.githubusercontent.com/108508922/188045404-807edd7d-308d-4c06-afbd-acab80c00c97.png)
- Aspectj 로그인 여부 경로 빨간색:로그인안되있을시 초록색:로그인 되어있을시 (joinPoint.Proceed()는 obj를 리턴하는데 obj=mView이다)<br> 
![image](https://user-images.githubusercontent.com/108508922/188351774-ee00b56a-3229-4e59-b584-aea0d930568e.png)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Spring 5
#### 수업 요약

- Tomcat Web Server App은 web.xml, server.xml, context.xml 등 과 같은 xml문서를 읽어 동작을 준비한다. 따라서 서버 설정을 하려면 web.xml, server.xml, context.xml을 설정한다.
- DispatcherServlet이 servlet-context.xml을 읽어 온다 따라서 spring설정을 하고 싶으면 sevlet-context.xml을 설정하면 된다.
- Client가 xxx.do로 끝나는 요청을하면 DispaterServlet이 어떤 controller로 처리할지 분배를 해준다.
- Dao를 Bean으로 만들기 위해서 component-scan이 이루어 져야하고 적절한@(어노테이션)이 붙어 있어한다.
- ModelAndVie 객체에 대한 이해
   1. 컨트롤러에서 리턴 rtpe으로 지정할 수 있는 객체이다.
   2. Model과 View page 정보를 같이 담을 수 있는 객체이다.
   3. Model은 view page에 전달할 데이터 이다.
   4. 경우에 따라서는 redirect 이동할 경로도 담을 수 있다.
   5. ModelAndView 객체에 addObject()메소드를 통해서 담은 데이터는 spring 프레임워크가 동작하면서 자동으로 HttpSevletRequest 객체에 담긴다.

- Controller는 어떤 service를 통해서 비즈니스 로직을 처리하고 view페이지를 어디로 보낼지만 결정한다.<br>

[spring frame work 에서 json 문자열을 응답하는 방법도 알고 있어야 한다.]
- 필요한 이유: ajax 요청에 대한 응답으로 json문자열 응답을 많이한다.

- File System
   1. file은 MultipartFile type으로 받아야 한다.
   2. 기능 : MultiPartFile, getOriginalFilename(), getSize()
   3. 임시폴더에 저장된 파일을 원하는 경로로 이동시켜줘야 한다는 점이 있다.(transferTo(new File(savePath)) -> savePath-realPath+File.separator(구분자)+saveFileName;
   4. separator: 리눅스 = / 윈도우 = \
   
- myBatis를 활용하면 Dynamic Query 작성에 유용한다.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- DB Connection 하기위해 다음의 이름이 같아야 한다.<br>
![image](https://user-images.githubusercontent.com/108508922/188341284-19941cfa-4e99-408e-ad9c-723c9ae30b0f.png)
- sqlSession 객체를 DI 받는 구조<br>
![image](https://user-images.githubusercontent.com/108508922/188342063-1620be3e-ceda-4a6b-8415-e4cb8a4d98a3.png)
- Dao class가 bean이 되는 구조<br>
1. ![image](https://user-images.githubusercontent.com/108508922/188342311-de517595-d048-4023-87b1-7b78286e1c73.png)<br>
2. ![image](https://user-images.githubusercontent.com/108508922/188342425-a3d09c6f-2206-44aa-8e81-744945063c19.png)<br>
- savpath<br>
![image](https://user-images.githubusercontent.com/108508922/188354448-467d2908-d5a2-428a-8548-184799dba70b.png)
- 비밀번호 암호화<br>
![image](https://user-images.githubusercontent.com/108508922/188384934-e7723bf6-3485-4a7f-853d-dcb1057808ae.png)
- 검색기능을 추가한 Dynamic Query 작성예시<br>
![image](https://user-images.githubusercontent.com/108508922/188416658-919d1661-46a7-4694-987a-9f5d08e04eb2.png)
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Spring 6
#### 수업 요약
댓글수업
- mapper.xml => myBatise가 로딩하고 myBatise가 정해놓은 형식대로 작동한다.
----------------------------------------------------------------------------------------------------------------------------------------------------------------------
----------------------------------------------------------------------------------------------------------------------------------------------------------------------

### Spring 7
#### 수업 요약
댓글수업+
![image](https://user-images.githubusercontent.com/108508922/188811107-7d9824a2-0d5c-48ad-87f2-cdbed9de718b.png)
- ajaxFormPromise response object로 변환 
![image](https://user-images.githubusercontent.com/108508922/188812106-72c46d38-6e97-4dfb-bc2a-534094799ba7.png)
   

----------------------------------------------------------------------------------------------------------------------------------------------------------------------


