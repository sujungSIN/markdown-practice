# 제목(Header)

# 제목 1
## 제목 2
### 제목 3
#### 제목 4
##### 제목 5
###### 제목 6

# 문장(Paragraph)

동해물과 백두산이 마르고 닳도록 
하느님이 보우하사 우리나라 만세

# 줄바꿈(Line Breaks)

띄어쓰기를 2번 넣기 or <br태그> 사용

동해물과 백두산이 마르고 닳도록   
하느님이 보우하사 우리나라 만세  
무궁화 삼천리 화려 강산<br/>
대한 사람 대한으로 길이 보전하세

# 강조(Emphasis)

_이탤릭_  
**두껍게**

**_이탤릭 + 두껍게_**  
~~취소선~~   
<u>밑줄</u>

# 목록(List)

1. 순서가 필요한 목록
1. 순서가 필요한 목록
1. 순서가 필요한 목록
    1. 순서가 필요한 목록
    1. 순서가 필요한 목록
1. 순서가 필요한 목록

- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
    - 순서가 필요하지 않은 목록
- 순서가 필요하지 않은 목록

# 링크(Links)

<a href="https://google.com">GOOGLE</a>

[GOOGLE](https://google.com)

<a href="https://naver.com" title="Naver로 이동!" target="_blank">NAVER</a>  
[NAVER](https://naver.com "Naver로 이동!")

# 이미지(Images)
![]()
![HEROPY](https://heropy.blog/css/images/logo.png)

## 이미지에 링크 첨부하기 
[![HEROPY](https://heropy.blog/css/images/logo.png)](https://heropy.blog/css/images/logo.png)

# 인용문(BlockQuote)

> 남의 말이나 글에서 직접 또는 간접으로 따온 문장.  
> (네이버 국어 사전)

> 인용문을 작성하세요!
>> 중첩된 인용문
>>> 중중첩된 인용문 1

# 인라인(inline) 코드 강조

CSS에서 `background` 혹은 `background-image` 속성으로 요소에 배경 이미지를 삽입할 수 있습니다.

# 블록(Block) 코드 강조

```html
<a href="https://google.com" target="_blank">GOOGLE</a>
```

```css
.list > li {
  position: absolute;
  top: 40px;
}
```

```js
function func() {
  var a = 'AAA';
  return a;
}
```

```bash
$git commit -m 'Study Markdown'
```

```plaintext
동해물과 백두산이 마르고 닳도록
하느님이 보우하사 우리나라 만세
```

# 표(Table)

position 속성

값 | 의미 | 기본값
--|:--:|--:
static | 기준없음 | o
relative | 요소 자신 | x
absolute | 위치 상 부모 요소 | x
fixed | 뷰포트 | x

# 원시 HTML(Raw HTML)
마크다운 안에서 실제 HTML 문법을 사용하는 것  
u 태그 : underline 을 의미한다.  
(몇몇 브라우저에서 작성 안될수 있다. 그러면 span태그에 style을 넣어준다)

동해물과 <u>백두산이</u> 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

동해물과 <span style="text-decoration: underline;">백두산이</span> 마르고 닳도록<br/>
하느님이 보우하사 우리나라 만세

<a href="https://naver.com" target="_blank">NAVER</a>
---
<img width="70" src="https://heropy.blog/css/images/logo.png"/>

# 수평선(Horizontal Rule)

---

***

___