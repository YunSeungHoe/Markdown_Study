__<div align="center">기본적인 Markdown 문법 공부</div>__
======

+ ### 제목(Header) 넣기
  - #### code

```
Hello Markdown
======
Hello Markdown
------
```

+ ### 제목(Header) 크기
  - #### code

```
# Hello Markdown
## Hello Markdown
### Hello Markdown
#### Hello Markdown
##### Hello Markdown
###### Hello Markdown
```
------
+ ### 가운데 정렬
  - #### code

``` 
<div align="center"> Center </div>
```
------
+ ### 강조(Emphasis)
  - 강조는 이텔릭체, 볼드체, 취소선, 밑줄을 사용합니다.
  - #### code

```
Italic        : *(content)* or _(content)_
Bold          : **(content)** or __(content)__
strikethrough : ~~(content)~~
underscore    : <u>(content)</u>
```
+ ### 강조(Emphasis)
  - #### result
> *(content)* or _(content)_<br>
  **(content)** or __(content)__<br>
  ~~(content)~~<br>
  <u>(content)</u><br>
------
+ ### 줄바꿈(Line Breaks)
  - 줄바꿈을 하기 위해서는 다음 명령어를 사용합니다.<br>
    Line Breaks : \<br>
  - #### code

```
Hello Markdown Hello Markdown<br>
Hello Markdown<br>Hello Markdown<br><br>
Hello Markdown
```

+ ### 줄바꿈(Line Breaks)
  - #### result
> Hello Markdown Hello Markdown<br>
> Hello Markdown<br>Hello Markdown<br><br>
> Hello Markdown
------

+ ### 목록(List)
  - 목록을 나열하는 방법은 다음과 같습니다.<br>
    순서가 없는 리스트. : *, +, -<br>
    순서가 있는 리스트. : 1, 2, 3 <br>
    순서가 없는 리스트 + 순서가 있는 리스트.<br>
  - #### code

+ 순서가 없는 리스트.
```
* list 1
* list 2
* list 3

* list A
  * list B
  * list C
    * list D

* list a
+ list b
- list c
```
+ 순서가 있는 리스트.
```
1. list 1
2. list 2
3. list 3
```
+ 순서가 없는 리스트와 순서가 있는 리스트를 혼합해서 사용가능합니다.
```
* list 1
  + list 2
  + list 3
    1. liist 4
    2. liist 5
* list 6
```

+ ### 목록(List)
  - #### result
+ 순서가 없는 리스트.
> * list 1
> * list 2
> * list 3

> * list A
>   * list B
>   * list C
>     * list D

> * list a
> + list b
> - list c

+ 순서가 있는 리스트.
> 1. list 1
> 2. list 2
> 3. list 3

+ 순서가 없는 리스트와 순서가 있는 리스트를 혼합해서 사용가능합니다.
> * list 1
> + list 2
> + list 3
>   1. liist 4
>   2. liist 5
> * list 6
------