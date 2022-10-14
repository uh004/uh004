# Markdown이란?

> 마크다운은 마크업 언어의 일종으로,존 그루브와 아론 스워츠가 만들었다. <br>
> 태그로 범벅된 HTML 문서 등과 달리,읽기도 쓰기도 쉬운 문서 양식을 지향한다.<br>
> 확장자는 .md 또는 .markdown을 쓰지만 전자가 압도적으로 많이 사용한다. <br>

## Markdown태그설명
### 제목(header)
```
<h1> ~ <h6> 까지 제목 표현 방법
# 가나다라마바 1
## 가나다라마바 2
### 가나다라마바 3
#### 가나다라마바 4
##### 가나다라마바 5
###### 가나다라마바 6
```
# 가나다라마바 1
## 가나다라마바 2
### 가나다라마바 3
#### 가나다라마바 4
##### 가나다라마바 5
###### 가나다라마바 6
### 강조(emphasis)
```
*i love you*  이탤릭체
_i love you_ 

**i love you** 강조
__i love you__  

*i **love** you*
```
*i love you*  <br>
_i love you_  <br>

**i love you**  <br>
__i love you__  <br>

*i **love** you* <br>
### 목록(list)
```
순서있는 목록
1. 첫번째
2. 두번째
3. 세번째
```
1. 첫번째
2. 두번째
3. 세번째
```
순서없는 목록
* red
  * green
    * blue

+ red
  + green
    + blue

- red
  - green
    - blue
```
* red
  * green
    * blue

+ red
  + green
    + blue

- red
  - green
    - blue
### 링크(links)
```
[GitHub](http://github.com "깃허브")
[naver](http://naver.com "네이버")
```
[GitHub](http://github.com "깃허브") <br>
[naver](http://naver.com "네이버")

### 이미지(images)
```
마크다운 형식
![다운로드sdfd](https://user-images.githubusercontent.com/105197524/195865824-8d5c57c1-342c-469b-ab44-890d1d2680dc.jpg)
태그 형식
<img src="https://user-images.githubusercontent.com/105197524/195865835-d5d8b25a-374f-43dd-91bf-071aa6efc398.jpg"  width="700" height="370">
```

![다운로드sdfd](https://user-images.githubusercontent.com/105197524/195865824-8d5c57c1-342c-469b-ab44-890d1d2680dc.jpg) <br>

<img src="https://user-images.githubusercontent.com/105197524/195865824-8d5c57c1-342c-469b-ab44-890d1d2680dc.jpg"> <br>

### 테이블(Table)
```
테이블 생성

헤더1|헤더2|헤더3|헤더4
---|---|---|---
셀1|셀2|셀3|셀4
셀5|셀6|셀7|셀8
셀9|셀10|셀11|셀12

테이블 정렬

헤더1|헤더2|헤더3
:---|:---:|---:
Left|Center|Right
1|2|3
4|5|6
7|8|9
```

헤더1|헤더2|헤더3|헤더4
---|---|---|---
셀1|셀2|셀3|셀4
셀5|셀6|셀7|셀8
셀9|셀10|셀11|셀12

헤더1|헤더2|헤더3
:---|:---:|---:
Left|Center|Right
1|2|3
4|5|6
7|8|9

## 인용 상자(Blockquotes)
```
how are you: 
> welcome to github
> right now
```
how are you: 
> welcome to github <br>
> right now

## 체크 박스(check box)
```
- [x] Fly on the Wall (*)
- [ ] Down in the Cockpit
- [x] English Roundabout (*)
- [x] Snowman
```
- [x] Fly on the Wall (*)
- [ ] Down in the Cockpit
- [x] English Roundabout (*)
- [x] Snowman

## 수평선(hr)
```
--- 
*** 
___
```
--- 
*** 
___
