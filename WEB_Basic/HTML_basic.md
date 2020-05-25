HTML 기본문법
====
[참고사이트(생활코딩)](https://opentutorials.org/course/1688/9340)

### ex_html1.html

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
  </head>
  <body>
    안녕하세요. <strong>생활코딩</strong>입니다.
  </body>
</html>
```
이게 html 기본 형태임.
- ```<strong>컨텐츠</strong>``` : 강조



### ex_html2.html

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
  </head>
  <body>
    안녕하세요. <a href="http://opentutorials.org/course/1" target="_blank">생활코딩</a>입니다.
  </body>
</html>
```
- ```<a herf="링크">링크텍스트</a>``` 링크
- ```<a herf="링크" target="_blank">링크텍스트</a>``` 새 창에 링크


### ex_html3.html

```
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8" />
  </head>
  <body>
    <ol>
      <li>html</li>
      <li>css</li>
      <li>JavaScript</li>
    </ol>
    <ul>
      <li>최진혁</li>
      <li>최유빈</li>
      <li>한이람</li>
    </ul>
  </body>
</html>
```
- ```<li>컨텐츠</li>``` 리스트
- ```<ul>컨텐츠</ul>``` 순서가 없는 리스트 그룹
- ```<ol>컨텐츠</ol>``` 순서가 있는 리스트 그룹   

* ```<html>여기 안에 있는 언어가 html이다</html>```
- ```<body>본문에 해당되는 태그들</body>```
- ```<head>문서를 설명하는 정보들</head>```
    - ```<title>연 파일의 제목...문서의 제목</title>```
    - ```<meta charset="utf-8">```없으면 한글깨짐