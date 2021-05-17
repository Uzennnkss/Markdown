# Markdown
---
마크다운(Markdown)이란?
1. 일반 텍스트 기반의 마크업 언어
2. README.md 파일 or 옹ㄴ라인 문서 or 일반 텍스트 편집기로 문서 양식을 편집할 때 유용 
3. HTML  파일 변환 가능 

<!--Code-->
---
## 코드 작성
```
1. `를 통해 inline 형식으로 코드 표시 
2. ```언어 ```를 통해 코드 블록 표시 
```

* To print message in the console, use `console.log('yourmessage')`

* 코드 블록

```js
console.log('your message')
```
---
<!-- Heading -->
## 헤딩
```
# Heading 1 
## Heading 2 
### Heading 3 
#### Heading 4 
##### Heading 5 
###### Heading 6 
```
# Heading 1 
## Heading 2 
### Heading 3 
#### Heading 4 
##### Heading 5 
###### Heading 6 

<!-- Line-->
---
## Line 
' - ' 3개 입력시 line 생성 
```
---
```

<!--Text attributes-->
---
## Bold, Italic, Strikethrough
Bold : 앞뒤로 **
italic : 앞뒤로 *
strikethrough : 앞뒤로 ~~
```
This is the **bold** txt
this is the *italic* txt
and let's do ~~strikethrough~~.
```

This is the **bold** txt and this is the *italic* txt and let's do ~~strikethrough~~. 

---
<!--Quote-->
## 인용구
'>' 작성 후 인용구 입력
```
> Quote
```

> Quote

---
<!--Bullet list-->
## 리스트
목록을 만들 때는 ' * ' 또는 ' - '를 사용한다.
```
Fruits:
* 사과
  * 사과 2

- 망고
  - 망고2
```
Fruits:
* 사과
  * 사과 2

- 망고
  - 망고2

<!--Number list-->
---
## 숫자 리스트
앞에 숫자를 붙인다. 
```
Numbers: 
1. first
2. second
3. third
```
Numbers: 
1. first
2. second
3. third

<!--Link-->
---
## 하이퍼링크 
```
Click [here](http://링크)
```
Click [here](http://링크)


<!--Image-->
---
## 이미지 삽입
```
![image description](링크)
```
![image description](링크)

<!--Table-->
---
## 표
| 로 텍스트를 감싼다.
|:--:|로 텍스트 정렬 

```
|Header|Description|
|:--:|--:|
|Cell1|Cell2|
```
|Header|Description|
|:--:|--:|
|Cell1|Cell2|

<!--Emoji-->
## 이모지 아이콘
깃허브에서 이미지 아이콘 제공 

깃허브 이모지 링크 : [Click](https://gist.github.com/rxaviers/7360908)
```
:+1: :rocket: :smile: 
```
:+1: :rocket: :smile: 
