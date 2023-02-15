# 목표
웹 페이지를 만드는 데 필요한 내용들 학습 (텍스트 표시, 이미지 표시, 하이퍼링크, 테이블 등)

``` html
<!DOCTYPE html>
<!-- 이것은 주석입니다. -->
<html>
 ㄱ
<head>
	<title>My Web Page</title>
	<meta charset="utf-8">
</head>

<body>
	<p>Hello Web Programming World!</p>
</body>

</html>
```

## HTML 문서 구조
-  <!DOCTYPE> 선언
웹 페이지에 사용된 HTML의 종류와 버전을 알고 있다. <!DOCTYPE html>은 HTML5 버전을 의미한다.
- <!-- 이것은 주석입니다. -->
주석이다.
- head와 body
head : 메타데이터를 담는 컨테이너. 메타데이터는 화면에 표시되지 않는다.
메타데이터 : 문서 제목, 문자 집합, CSS 스타일 시트, 자바스크립트를 포함
body : 문서의 내용에 해당하는 부분
- 한글 코드 문제
한글 입력 방식으로 euc-kr과 utf-8이 있는데, 이를 메타데이터에 추가해야한다.
``` html
<meta charset="utf-8"
```
- 요소(element)
tag는 "\<tag\>", "\</tag\>" 와 같이 <, >로 둘러싸인 단어를 의미한다.
tag는 문서의 구조를 나타내는 단어이다. 
시작 tag와 종료 tag가 있는데, 종료 tag가 없는 것도 있다.

> 주의
> 1. 태그 이름은 대소문자를 구별하지 않는다.
> 2. 하나의 요소 안에 다른 요소들이 포함될 수 있다. 
> 3. 시작 태그와 종료 태스 사이의 연속된 공백은 하나의 공백으로 취급한다.

