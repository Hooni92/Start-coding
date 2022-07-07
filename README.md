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
git fetch -> git merge -> :wq(frast forwad경우) 
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
 -문서 객체는 오브젝트와 유사하다.
 -document.querySelector("CSS형식 처럼 요소를 부른다 ex)요소명,#id,.class")
  JS영역에서 HTML 영역에 있는 해당요소를 가져온다.
 -document.querySelectorAll()
  JS영역에서 HTML 영엑에 있는 해당 요소를 배열 형태로 가져온다.
 
 ----------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Code<br>
![image](https://user-images.githubusercontent.com/108508922/177101829-8ed26524-e891-4a62-898d-45c4561926ab.png)<br>
![image](https://user-images.githubusercontent.com/108508922/177232539-d8217aec-8632-4ce4-96f9-b794cafbd84e.png)<br>
![image](https://user-images.githubusercontent.com/108508922/177246547-5c20946c-3184-4e09-8145-263493064b62.png)<br>
- stack & heap 영역<br>
![image](https://user-images.githubusercontent.com/108508922/177442531-2931fdf8-4f5d-46af-a1ce-aec1a61aede3.png)<br>
- 문서 <br> 
![image](https://user-images.githubusercontent.com/108508922/177459454-1a0a42ac-f343-4829-900a-95c9a44044e7.png)<br>
-p의 참조값을 얻어오는 방법 <br>
![image](https://user-images.githubusercontent.com/108508922/177460787-e93b0857-a9ae-427a-8230-525517002474.png)<br>


----------------------------------------------------------------------------------------------------------------------------------------------------------------------
### Step02_event
#### 수업 요약

교육 ing...


