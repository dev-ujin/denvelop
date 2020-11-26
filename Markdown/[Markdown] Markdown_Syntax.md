*2020-11-22 written by Clo-udye*
# :pencil:Markdown문서 작성법:pencil:

## :bookmark:목차:bookmark:
  1. [제목 (Header)](#1-제목-header)
  1. [줄바꿈 (Line Breaks)](#2-줄바꿈-line-breaks)
  1. [수평선](#3-수평선)
  1. [강조 (Emphasis)](#4-강조-emphasis)
  1. [탈출 문자 (Backslash Escapes)](#5-탈출-문자-backslash-escapes)
  1. [목록 (List)](#6-목록-list)
        - [순서가 있는 리스트](#순서가-있는-리스트)
        - [순서가 없는 리스트](#순서가-없는-리스트)
            * [순서가 없는 리스트에 사용가능한 기호](#순서가-없는-리스트에-사용가능한-기호)
  1. [코드 강조](#7-코드-강조)  
        - [인라인 코드 (Inline code)](#인라인-코드-inline-code)  
        - [코드 블록 (Code Blocks)](#코드-블록-code-blocks)
  1. [인용문 (Blockquotes)](#8-인용문-blockquotes)
  1. [체크박스 (Task Lists)](#9-체크박스-task-lists)
  1. [표 (Tables)](#10-표-tables)
  1. [링크 (Links)](#11-링크-links)
  1. [이미지 (Images)](#12-이미지-images)
  1. [이모지 (EMOJI)](#13-이모지-emoji)
  1. [뱃지 (Badge)](#14-뱃지-badge)
  1. [주석](#15-주석)
  1. [목차](#16-목차)
  1. [HTML](#17-html)
  1. [참고 자료](#참고-자료)
    
## 1. 제목 (Header)
제목 글자의 크기는 가장 앞 #을 붙인다.  
 #의 갯수로 `<h1>` ~ `<h6>`태그의 표현이 가능하다.  

# 헤더크기 (h1)
## 헤더크기 (h2)
### 헤더크기 (h3)
#### 헤더크기 (h4)
##### 헤더크기 (h5)
###### 헤더크기 (h6)

    # 헤더크기 (h1)
    ## 헤더크기 (h2)
    ### 헤더크기 (h3)
    #### 헤더크기 (h4)
    ##### 헤더크기 (h5)
    ###### 헤더크기 (h6)


h1의 다른 표현
=====
h2의 다른 표현
-----

    h1의 다른 표현
    ===
    h2의 다른 표현
    ---

*****

## 2. 줄바꿈 (Line Breaks) 
문단을 구분하려면 한 개 이상의 빈 줄을 문단 사이에 삽입하거나 줄의 마지막에 [Space Bar]를 두 번 이상 눌러 띄어쓰기를 한다. 또는 `<br>`태그를 입력한다

문장을 작성한다. (공백이 없을 경우)
빈 줄이 없으면 자동적으로 앞의 문장에 붙는다. (공백이 두 개 이상일 경우)  
위문장에서 마지막에 두 칸의 공백을 입력하여 줄바꿈 할 수 있다.<br>`<br>`태그를 넣는 것도 가능하다.

    문장을 작성한다. (공백이 없을 경우)
    빈 줄이 없으면 자동적으로 앞의 문장에 붙는다. (공백이 두 개 이상일 경우)  
    위문장에서 마지막에 두 칸의 공백을 입력하여 줄바꿈 할 수 있다.<br>`<br>`태그를 넣는 것도 가능하다.

*****

## 3. 수평선
`<hr>` 태그로 변환 가능하다. 별표(*), 언더바(_), 하이픈(-)을 세번 이상 입력한다. 
***
___
---
<hr>

    ***
    ___
    ---
    <hr>

*****

## 4. 강조 (Emphasis)
`<em>`, `<strong>`, `<del>` 태그로 변환 가능하다.
### _이탤릭체_
_기울여서 강조하기1_  
*기울여서 강조하기2*  
<em>기울여서 강조하기3</em>  

    _기울여서 강조하기1_  
    *기울여서 강조하기2*  
    <em>기울여서 강조하기3</em>  

### __볼드체__
**두껍게 쓰기1**  
__두껍게 쓰기2__  
<strong>두껍게 쓰기3</strong>  

    **두껍게 쓰기1**  
    __두껍게 쓰기2__  
    <strong>두껍게 쓰기3</strong>  

\_\_언더바\_\_ 와 \*\*별표\*\*의 차이  
__언더바__ 는 다음 글자와 사이에 공백이 한칸 있어야한다. **별표**는 공백이 없어도 표현된다.   
_이탤릭체_ 도 *위*와 같다.  

    \_\_언더바\_\_ 과 \*\*별표\*\*의 차이는   
    __언더바__ 는 다음 글자와 사이에 공백이 한칸 있어야한다.  
    **별표**는 공백이 없어도 표현된다.  
    _이탤릭체_ 도 *위*와 같다.   

### 취소선
~~취소선 넣기1~~  
<del>취소선 넣기2</del>  

    ~~취소선 넣기1~~
    <del>취소선 넣기2</del>

### 밑줄
<u>밑줄 넣기</u>  

    <u>밑줄 넣기</u>


### 섞어서 쓰기
밑의 예제와 같이 섞어서 쓰는 것도 가능하다.  

**굵은 글씨에서 *기울이기*를 사용**  
_기울어진 글씨에서 ~~취소선~~을 넣기_  
__전부 ~~섞어서~~ *쓰기도*__ *가능하다*  

    **굵은 글씨에서 *기울이기*를 사용**
    _기울어진 글씨에서 ~~취소선~~을 넣기_
    __전부 ~~섞어서~~ *쓰기도*__ *가능하다* 

 *****   

## 5. 탈출 문자 (Backslash Escapes)
강조에서 쓰이는 별표(\*)나 언더바(\_)를 그대로 쓰이도록 하고 싶다면 역슬래시(\\)를 앞에 붙이면 된다.

\*강조가 아니라 별표\*  
\_강조가 아니라 언더바\_   

    \*강조가 아니라 별표\*
    \_강조가 아니라 언더바\_ 

*****
## 6. 목록 (List)
#### 순서가 있는 리스트 
`<ol>`태그로 변환 가능하다
1. 순서가 있는 리스트
1. 순서가 있는 리스트
1. 순서가 있는 리스트
    1. 순서가 있는 리스트
        1. 순서가 있는 리스트
        1. 순서가 있는 리스트
    1. 순서가 있는 리스트
        - 순서가 있는 리스트
        - 순서가 있는 리스트

<ol>
<li>순서가</li>
<li>있는</li>
<li>리스트</li>
</ol>   

```HTML
    1. 순서가 있는 리스트
    1. 순서가 있는 리스트
    1. 순서가 있는 리스트
       1. 순서가 있는 리스트
            1. 순서가 있는 리스트
            1. 순서가 있는 리스트
        1. 순서가 있는 리스트
            - 순서가 있는 리스트
            - 순서가 있는 리스트
```
    <ol>
        <li>순서가</li>
        <li>있는</li>
        <li>리스트</li>
    </ol> 
#### 순서가 없는 리스트
`<ul>`태그로 변환 가능하다
- 순서가 없는 리스트
- 순서가 없는 리스트
    - 순서가 없는 리스트
        - 순서가 없는 리스트
        - 순서가 없는 리스트
    - 순서가 없는 리스트
        1. 순서가 없는 리스트
        1. 순서가 없는 리스트

```HTML
- 순서가 없는 리스트
    - 순서가 없는 리스트
        - 순서가 없는 리스트
        - 순서가 없는 리스트
    - 순서가 없는 리스트
        1. 순서가 없는 리스트
        1. 순서가 없는 리스트
```
##### 순서가 없는 리스트에 사용가능한 기호
- 하이픈(-)
* 별표(*)
+ 더하기(+)

```HTML
##### 순서가 없는 리스트에 사용가능한 기호
- 하이픈(-)
* 별표(*)
+ 더하기(+)        
```
<ul>
    <li>순서가</li>
    <li>없는</li>
    <li>리스트</li>
</ul>

    <ul>
        <li>순서가</li>
        <li>없는</li>
        <li>리스트</li>
    </ul>

*****

## 7. 코드 강조
#### 인라인 코드 (Inline code)
숫자 1번 키 왼쪽에 있는 \`(Grave)를 입력한다.
문단의 중간에 `Code`를 넣을 수 있다. 예를 들어 `printf("Hello Denvelop");` 이렇게 할 수 있다.

    문단의 중간에 `Code`를 넣을 수 있다. 예를 들어 `printf("Hello Denvelop");` 이렇게 할 수 있다.

#### 코드 블록 (Code Blocks)
\`(Grave)를 세번이상 입력하고 코드의 종류를 적는다.
```html
<h1>html을 이용한 코드블록 예제<h1>
<div>
    Hello Denvelop
</div>
```
```java
System.out.println("Java를 이용한 코드블록 예제");
String str = "Hello Denvelop";
```
    ```html
    <h1>html을 이용한 코드블록 예제<h1>
    <div>
        Hello Denvelop
    </div>
    ```
    ```java
    System.out.println("Java를 이용한 코드블록 예제");
    String str = "Hello Denvelop";
    ```
*****

## 8. 인용문 (Blockquotes)
`<blockquote>` 태그로 변환 가능하다. 인용문옆에 오른쪽 꺽쇠 괄호(>)를 적는다.

인용문
> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> _(네이버 국어 사전)_

    
    > 남의 말이나 글에서 직접 또는 간접으로 따온 문장.
    > _(네이버 국어 사전)_

중첩된 인용문
> 중첩된 인용문
>> 중첩된 인용문
>> 중첩된 인용문
>>> 중첩된 인용문

    
    > 중첩된 인용문
    >> 중첩된 인용문
    >> 중첩된 인용문
    >>> 중첩된 인용문
*****
## 9. 체크박스 (Task Lists)
\- [x] : 선택된 체크박스  
\- [ ] : 선택되지 않은 체크박스

- [x] 체크 박스
- [ ] 체크 박스
- [x] 체크 박스
- [x] 체크 박스

```HTML
- [x] 체크 박스  
- [ ] 체크 박스
- [x] 체크 박스
- [x] 체크 박스
```

*****

## 10. 표 (Tables)
`<table>`태그로 변환 가능하다.  
헤더 셀을 구분할 때 3개 이상의 -(hyphen/dash) 기호가 필요하다.   
헤더 셀을 구분하면서 :(Colons) 기호로 셀(열/칸) 안에 내용을 정렬할 수 있다.   
가장 좌측과 가장 우측에 있는 |(vertical bar) 기호는 생략 가능하다.  

첫번째 헤더|두번째 헤더|세번째 헤더
---|---:|:---:
 내용|내용|내용
 내용|내용|내용

    첫번째 헤더|두번째 헤더|세번째 헤더
    ---|---:|:---:
    내용|내용|내용
    내용|내용|내용

*****

## 11. 링크 (Links)
`<a>`태그로 변환 가능하다.
##### \[화면에 표시될 글자]( 이동할 url 혹은 상대적참조 "마우스를 올려두면 보이는 링크설명(title)" )

[Github](https://github.com "깃허브로 가기")  
[상대적참조](../)  
    
    [Github](https://github.com "깃허브로 가기")
    [상대적참조](../)
##### 문서내의 일반 url이나 꺽쇠괄호(\<>)안의 url은 자동으로 링크를 생성한다.

구글 바로가기 : https://google.com  
네이버 바로가기 : <https://naver.com>  

    구글 바로가기 : https://google.com
    네이버 바로가기 : <https://naver.com>

##### 문서 안에서 참조 링크를 그대로 사용할 수도 있다 : \[화면에 표시될 글자]\[1],  \[1]:url "링크설명(title)" 

[참조 링크]  
[Dribbble][Dribbble link]  
[GitHub][1]  

[Dribbble link]: https://dribbble.com
[1]: https://github.com
[참조 링크]: https://naver.com "네이버로 이동"

    [참조 링크]
    [Dribbble][Dribbble link]
    [GitHub][1]

    [Dribbble link]: https://dribbble.com
    [1]: https://github.com
    [참조 링크]: https://naver.com "네이버로 이동"


*****
## 12. 이미지 (Images)
`<img>`태그로 변환 가능하다. 링크와 비슷하지만 앞에 느낌표(!)가 붙는다.   
깃허브에서 이미지를 사용하려만 레파지토리에 이미지파일을 업로드 되어있어야한다. url링크는 상대경로와 절대경로 둘다 사용 가능하다 

##### 첫번째 방법 : ![이미지 alt명](url 링크) 
![독일여행](../resources/Regensburg.jpg) 
    
    ![독일여행](../resources/Regensburg.jpg) 

##### 두번째 방법 : `<img>` 태그 사용 
<img src="../resources/happybirthday.jpg" width="400px" alt="Happy Birthday">

    <img src="../resources/happybirthday.jpg" width="400px" alt="Happy Birthday">

##### 이미지에 링크를 걸기 : 마크다운 이미지 코드를 링크 코드로 묶어준다.
[![Github](../resources/octocat.png)](https://github.com)

    [![Github](../resources/octocat.png)](https://github.com)

*****    
## 13. 이모지 (EMOJI)
 콜론사이에 해당 이모지의 이름을 넣어준다. 이모지사이트에서 종류를 볼수있다.    
 EMOJI 사이트 : http://emoji-cheat-sheet.com  
 :heart::heart_eyes::+1::cactus:  

    :heart::heart_eyes::+1::cactus:

*****
## 14. 뱃지 (Badge)
- 뱃지(badge) 만들기 : 사이트 참고  
https://shields.io  
https://hits.seeyoufarm.com/  
![Relative date](https://img.shields.io/date/841158000?style=flat-square)  
[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FClo-udhye&count_bg=%233DC8C5&title_bg=%23555555&icon=reverbnation.svg&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://hits.seeyoufarm.com)

*****
## 15. 주석
\<!-- 사이에 주석을 쓴다.-->
```HTML
    <!-- Comment -->
```
*****    
## 16. 목차
##### 첫번째 방법
`[TOC]`를 입력하면 문서 내 헤딩 태그들을 이용하여 목차가 자동 생성된다. 
##### 두번째 방법 : \[목차텍스트](#링크가-걸리는-텍스트)
링크가 걸리는 텍스트의 띄어쓰기는 "-"로 명시, 혹은 글자수+띄어쓰기수만큼 "-"를 쓴다. 영어는 모두 소문자로 쓰며 "."이나 "()"등의 문자는 모두 생략한다. 
  
목차 자동 생성 사이트 : https://ecotrust-canada.github.io/markdown-toc/  
사이트로 생성후에 링크를 이름과 "-" 로 명시해주는 것이 좋다.

*****
## 17. HTML
마크다운 문법이 아닌 HTML 문법을 사용할 수 있다. 마크다운에서 지원하지 않는 기능을 사용할 때 유용하며 대부분 잘 동작한다.

*****

#### 참고 자료
https://heropy.blog/2017/09/30/markdown/  
https://post.naver.com/viewer/postView.nhn?volumeNo=24627214  
https://youtube.com/watch?v=dUbp9wAy178&feature=youtu.be  
https://poetic-code.tistory.com/51  

