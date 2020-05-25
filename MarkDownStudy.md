MarkDown 사용법 공부
=====
- [참고 사이트](https://gist.github.com/ihoneymon/652be052a0727ad59601)
# 1. 마크다운 문법
1.1. 헤더Headers
---------
- 큰제목

    This is an H1
    =========

This is an H1
* 방금 알아낸 것 : # 이렇게 H1 글머리 다음에 ==하면 적용 안됨!
========
- 작은제목

    This is an H2
    -------

This is an H2
-------
- 글머리 : 1~6까지 지원

    # This is an H1
    ## This is an H2
    ###### This is an H3
    알아낸 것 : 글머리 다음에 헤더 ===, ---표시를 하면 안된다. 텍스트 위에만 가능.

1.2. BlockQuote
------
이메일에서 사용하는 > 블럭인용문자

    > This is a first bq.
    >   > This is a second bq.
    >   >   > This is a third bq.

> This is a first bq.
>   > This is a second bq.
>   >   > This is a third bq.
이 안에서 다른 마크다운 요소 포함가능
> ### This is a Header3.
>   > - This is a list.
>   >   >   This is a code.

1.3. 목록
-----
- ### 순서있는 목록(번호)
숫자와 점 사용

    1. 첫번째
    2. 두번째
    3. 세번째

1. 첫번째
2. 두번째
3. 세번째
##### 어떤 번호를 입력해도 내림차순으로 정의됨

    1. 첫번째
    3. 두번째
    2. 세번째

1. 첫번째
3. 두번째
2. 세번째

- ### 순서없는 목록(*, +, - 지원)

    * 1
        * 2
            * 3
    + 1
        + 2
             +3
    - 1
        - 2
            - 3
 * 1
    * 2
         * 3

+ 1
    + 2
         +3
 - 1
     - 2
         - 3  
혼합해서 사용도 가능
여태까지 나는 -가 *인줄 알고 사용하고 있었다...하하..
- 1
    * 2
        + 3    

1.4. 코드
-----
### 1.4.1 들여쓰기
4개 공백 or 탭으로 들여쓰기 하면 들여쓰지 않은 행을 만날 때 까지 코드

    이렇게 코드 적용하면 된다 하네요..
    그런데 한 줄 띄어쓰지 않으면 제대로 인식 안된다 함
    부랴부랴 고쳤다.

### 1.4.2 코드블럭
2가지 방식 있음

- ```<pre><code>{code}</code></pre>```  이용방식

예시

    <pre>
    <code>
    printf("마크다운연습");
    </code>
    </pre>

<pre>
<code>
printf("마크다운 연습);
</code>
</pre>

- 코드블럭코드("```") 이용방식

    ```
    printf("코드블럭연습");
    ```

```
코드블럭연습
```

1.5 수평선 ```<hr/>```
----
아래 줄은 모두 수평선을 만든다. 페이지 나누기 용도러 사용함

```
* * *
***
*****
- - -
---------
```

- 적용 예

* * *
***
*****
- - -

1.6 링크
---
- 참조 링크

```
[Google][googlelink]
[googlelink]: https://google.com "go google"
```
[Google][googlelink]
[googlelink]: https://google.com "go google"

- 외부링크

```
[Google](https://google.com, "google link")
```
[Google](https://google.com, "google link")

- 자동연결

```
일반적인 URL 혹은 이메일주소 링크 형성
* 외부링크: <https://example.com/>
* 이메일링크: <address@example.com>
```

일반적인 URL 혹은 이메일주소 링크 형성
* 외부링크: <https://example.com/>
* 이메일링크: <address@example.com>

1.7 강조
-----

```
*single asterisks*
_single underscores_
**double asterisks**
__double underscores__
~~cancelline~~
```

> 문장 중간에 사용 할 경우 **띄어쓰기** 하는 게 좋음

1.8. 이미지
---

```
![Alt text](/path/to/img.jpg)
```
![Alt text](https://camo.githubusercontent.com/202c9ae1d457d6109be6c4cf13db9cac5fd708a6/687474703a2f2f6366696c65362e75662e746973746f72792e636f6d2f696d6167652f32343236453634363534334339423435333243374230)

되나?