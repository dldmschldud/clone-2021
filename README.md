# Kokoa Clone 2021

a. 기본구조 단축키

! + enter

b. BEM(Block Element Modifier)

css코드를 쉽게 읽기 위해서 사용

.btn{}
.btn__price{}
.btn--orange{}

c. 아이콘

svg파일 사용하기 - 픽셀이 없는 이미지 파일 형식, 수학으로만 구성된 형식

heroicons - css사용해서 스타일 바꾸기

fontAwesome

d. <script> </script>

body태그를 닫기 직전에 위치

script is used to embed executable code or data, typically used to embed or refer to js code

e. html코드에 css링크 추가 단축키

<head> </head> 사이에 작성

link:css + enter

f. pseudo selectors

.status-bar__column:first-child{} -> .status-bar__column중 첫번째

.status-bar__column:first-child span{} -> 첫번째 status-bar__colum의 span에만 적용

.status-bar__colum span{} -> 모든 span에 적용

g. 폰트 적용


font-family

goole fonts

h. css hack

justify content:space between 대신 justify content:center 사용후 자식들을 widh: x%로 조정

i. 브라우저가 html에 적용시키는 스타일 없애기

@import "reset.css"

j. flex

<body>
  <div></div>
  <div></div>
  <div></div>
  <div></div>
</body>
  
body{ height:100vh; }

