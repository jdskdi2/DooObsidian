Hyper Text Markup Language

[VScode](./VScode#VScode-설치)

Chapter 1 기초사항  

크롬의 개발자 도구  

VS code 설치  

VS code로 HTML5 문서 작성하기  

구조화된 HTML5 문서 작성  


## Chapter 2 HTML5 기본 요소 

HTML의 문법은 tag의 사용방법과 같다. tag로 문서의 구조를 만들고, 텍스트의 형태, 멀티미디어 삽입, 표 삽입  등 다양한 동작이 가능하다. 
tag는 "\<tag\>", "\</tag\>" 와 같이 <, > 사용한다.  

### 텍스트 표시  

1. Text Bold
```html
<strong>HTML</strong> is Hyper Text Markup Language
<b>HTML</b> is Hyper Text Markup Language
```
2. Underline
```html
<strong>HTML</strong> is <u>Hyper Text Markup Language</u>
```
3. Italic
em: emphasis, i: italic
```html
<strong><em>HTML</em></strong> is <u><i>Hyper</i> Text Markup Language</u>
```

### 리스트  
리스트는 2가지로

순서 없는 목록은 unordered list tag를 사용한다.
``` html
<ul>
	<li> test 1 </li>
	<li> test 2 </li>
	<li> test 3 </li>
</ul>
```

순서 있는 목록은 ordered list tag를 사용한다.
``` html
<ol>
	<li> test 1 </li>
	<li> test 2 </li>
	<li> test 3 </li>
</ol>
```



### 이미지  
```html
<img src="image file path" alt="text">
```
src 속성은 이미지 파일의 경로를 나타낸다. 
alt 속성은 이미지 파일 경로가 이상할 때 대체할 텍스트를 지정한다.

|속성|description|
|-|-|
|src|이미지 파일의 경로를 나타냄|
|alt|이미지 파일 경로가 잘못된 경우 대체할 텍스트 지정|
|width<br>height|width는 이미지의 너비를, height는 이미지의 높이 지정<br>두개를 모두 사용할 수 있고, 1개만 사용할 수 있음<br>한 개만 사용하는 경우 비율 자동계산됨<br>단위는 px과 %를 사용할 수 있다.|



### 링크  
``` HTML
<a href="링크할 주소"> 텍스트 또는 이미지 </a>
```

\<a\>와 \</a\> 사이에 Text 또는 Image를 넣으면 링크를 만들 수 있다.
``` HTML
<a href="www.google.com"><img src="images.jpg" alt="test"></a>
```

링크 클릭 시 새 탭에서 열기 위해서 target 속성을 지정한다.
``` HTML
<a href="www.google.com" target="_blank">Something</a>
```

### 테이블  
\<table\> \</table\> 태그 안에 \<tr\>, \<td\> 태그가 있어야한다. 
\<tr\> 태그는 행을 만드는 태그다. 
\<td\> 태그는 데이터를 추가하는 태그다. 

``` HTML
<table>
	<caption> Table Title </caption>
	<tr>
		<td> 1행 1열 </td>
		<td> 1행 2열 </td>
	</tr>
	<tr>
		<td> 2행 1열 </td>
		<td> 2행 2열 </td>
	</tr>
</table>
```

\<th\> 태그는 제목 행에 셀을 만드는 태그다.
``` HTML
<table>
	<caption> 선물용과 가정용 상품 구성 </caption>
	<tr>
		<th>용도</th>
		<th>중량</th>
		<th>개수</th>
		<th>가격</th>
	</tr>
	<tr>
		<td>선물용</td>
		<td>3kg</td>
		<td>11 ~ 14</td>
		<td>35,000</td>
	</tr>
	<tr>
		<td>선물용</td>
		<td>2kg</td>
		<td>14 ~ 18</td>
		<td>40,000</td>
	</tr>
</table>
```

### 멀티미디어 요소 추가하기  


### HTML5 문서 구조
``` html
<!-- This is a comment -->
<!DOCTYPE html>  <!-- 현재 문서가 HTML5로 작성했다는 것을 의미함 -->
<html lang="ko"> <!-- 웹 문서의 시작 -->
	<head> <!-- 웹 문서를 해석하는데 필요한 정보 입력 -->
		<meta charset="UTF-8">
		<title> Title </title>
	</head>
	<body> <!-- 실제 웹 문서 내용 -->
		<h1>LG Energy Solution</h1>
		<h2>LG Energy Solution</h2>
		<h3>LG Energy Solution</h3>
		<h4>LG Energy Solution</h4>
		<h5>LG Energy Solution</h5>
		<h6>LG Energy Solution</h6>
	</body>
</html> <!-- 웹 문서의 끝 -->
```

### Semantic Tag
웹 페이지의 Layout을 나타내기 위한 tag들이다. 
``` HTML
<header>
	<nav> </nav>
</header>
<main>
	<aside> </aside>
	<article>
		<section> </section>
	</article>
</main>
<footer>
	<section> </section>
</footer>
```

