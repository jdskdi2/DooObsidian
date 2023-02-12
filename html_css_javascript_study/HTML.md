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

</header>
<main>
	<article>
	
</main>
<footer>
	<section> </section>
</footer>
```

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
3. 

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


### 링크  


### 테이블  


### 멀티미디어 요소 추가하기  
