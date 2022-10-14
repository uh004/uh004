# Markdown이란?

> 마크다운이란 2004년 존그루버가 만든 텍스트 기반의 마크업 언어이다. 
> 쉽게 읽고 쓸 수 있으며 HTML로 변환도 가능해 간편하다. 단 모든 HTML을 지원하지는 않는다.
> 작성법은 특수기호와 문자를 이용하며, 문법이 간단한 편이라 웹에서도 빠르게 컨텐츠를 작성할 수 있고 읽기도 좋다. 마크다운이 많이 쓰이기 시작한 때는 GitHub가 생겨난 후 부터이다. 
> 깃허브의 원격저장소에 관한 정보를 기록하고 알려주는 README는 마크다운 언어로 쓰인다. 이를 기점으로 온라인 게시물에도 마크다운 언어를 많이 사용하기 시작했다.

## Markdown장점
<ol>
  <li>배우기가 정말 쉽고 직관적이다.  <br>
  <li>Text로 저장 후 HTML으로의 변환이 가능하다. 변환을 지원하는 도구나 Eco(생태계)가 매우 많다. <br>
  <li>Text로 저장하기 때문에 Git을 통한 버전관리가 가능하고, 용량이 적어 보관이 용이하다. <br>
  <li>Python의 Jupyter Notebook, R의 R Markdown 등 다른 기술을 익히는데 있어 훌륭한 커뮤니케이션 도구로써 가치가 있다. <br>
</ol>

## Markdown단점
<ol>
  <li>모든 HTML의 문법을 대신하지 못합니다. <br>
  <li>표준이 없기 때문에 도구에 따라 변환방식 또는 생성물이 다릅니다. <br>
  <li>마크다운으로 파일 업로드하는 경우 저장한 다음 파일 경로를 입력해야되는 불편함 <br>
  <li>tistory, naver blog, notion과는 다르게 문법들을 하나하나 입력해야되는 경우가 있어 귀찮음이 조금 있습니다. <br>
</ol>

## Markdown태그설명
### 제목(header)
```
<h1> ~ <h6> 까지 제목 표현 방법
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
```
# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6
### 강조(emphasis)
```
*This text will be italic* 
_This will also be italic_ 

**This text will be bold** 
__This will also be bold__ 

*You **can** combine them*
```
*This text will be italic*  <br>
_This will also be italic_  <br>
 
**This text will be bold**  <br>
__This will also be bold__  <br>

*You **can** combine them* <br>
### 목록(list)
```
<ol>, <ul> 목록 태그로 반환
1. 순서가 필요한 목록
1. 순서가 필요한 목록
  - 순서가 필요하지 않은 목록(서브) 
  - 순서가 필요하지 않은 목록(서브) 
1. 순서가 필요한 목록
  1. 순서가 필요한 목록(서브)
  1. 순서가 필요한 목록(서브)
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록에 사용 가능한 기호
  - 대쉬(hyphen)
  * 별표(asterisks)
  + 더하기(plus sign)
```

### 링크(links)
```
[GOOGLE](https://google.com)
[NAVER](https://naver.com "링크 설명(title)을 작성하세요.")
문서 안에서 [참조 링크]를 그대로 사용할 수도 있습니다.
다음과 같이 문서 내 일반 URL이나 꺾쇠 괄호(`< >`, Angle Brackets)안의 URL은 자동으로 링크를 사용합니다.
구글 홈페이지: https://google.com
네이버 홈페이지: <https://naver.com>
```

### 이미지(images)
```
마트다운 형식
![캡처](/uploads/1848994ad25765da30fa8ef3684c67bc/캡처.PNG)
태그 형식
<img src="/uploads/1848994ad25765da30fa8ef3684c67bc/캡처.PNG"  width="700" height="370">
```
![캡처](/uploads/1848994ad25765da30fa8ef3684c67bc/캡처.PNG)
태그 형식
<img src="/uploads/1848994ad25765da30fa8ef3684c67bc/캡처.PNG"  width="700" height="370">
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
