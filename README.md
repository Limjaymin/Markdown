# 1. Markdown이란?<br>
마크다운(Markdown)은 일반 텍스트 기반의 경량 마크업 언어입니다. 일반 텍스로 서식이 있는 문서를 작성하는 데 사용되며, 일반 마크업
언어에 비해 문법이 쉽고 간단한 것이 특징이다. 마크다운을 통해서 설치방법, 소스코드 설명, 이슈 등을 간단하게 기록하고 가독성을 높일 수 있다는 강점이
부각되면서 점점 여러 곳으로 퍼져가게 된다.
<br><hr>
## 1.1 역사<br>
존 그루버는 2004년에 문법 면에서 에런 스워츠와 중대한 협업을 통해 사람들이 읽기 쉽고 쓰기 쉬운 플레인 텍스트 포맷을 사용하면서 쓸 수 있는 언어로 마크다운 언어를 만들었다. 
<br><hr>
## 1.2 마크다운의 장단점
### 1.2.1 장점
    1. 간결하다.
    2. 별도의 도구잆이 작성가능하다.
    3. 다양한 형태로 변환이 가능하다.
    4. 텍스트(Text)로 저장되기 때문에 용량이 적어 보관이 용이하다.
    5. 텍스트파일이기 때문에 버전관리 시스템을 이용하여 변경이력을 관리할 수 있다.
    6. 지원하는 프로그램과 플랫폼이 다양하다.
    
### 1.2.2 단점
    1. 표준이 없다.
    2. 표준이 없기 때문에 도구에 따라서 변환방식이나 생성물이 다르다.
    3. 모든 HTML 마크업을 대신하지 못한다.

****
# 2. 마크다운 사용법(문법)
## 2.1 헤더(Headers)
* 큰제목: 문서 제목
    ```
    This is an H1
    =============
    ```
    This is an H1
    =============

* 작은제목: 문서 부제목
    ```
    This is an H2
    -------------
    ```
    This is an H2
    -------------

* 글머리: 1~6까지만 지원
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
```
# This is a H1
## This is a H2
### This is a H3
#### This is a H4
##### This is a H5
###### This is a H6
####### This is a H7(지원하지 않음)

## 2.2. BlockQuote
이메일에서 사용하는 ```>``` 블럭인용문자를 이용한다.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.
```
> This is a first blockqute.
>	> This is a second blockqute.
>	>	> This is a third blockqute.

이 안에서는 다른 마크다운 요소를 포함할 수 있다.
> ### This is a H3
> * List
>	```
>	code
>	```

**** 
# 3.
