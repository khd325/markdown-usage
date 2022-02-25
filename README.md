# markdown-usage

참고 블로그

[링크](https://gngsn.tistory.com/44)


# 1. 헤더 

----
```
1 ~ 6 까지 지원
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

---

# 2. 글자 강조

---
## 2-1 Bold 
굵은 글자를 사용하고 싶을 때 단어를 **로 감싼다.
```
**Bold**
```
**Bold**

---
## 2-2 Italic
옆으로 기운 이탤릭체를 사용하고 싶을 때 단어를 *로 감싼다.
```
*Italic*
```
*Italic*

---

## 2-3 인용구
'>' 문자를 사용해서 인용구를 작성한다.
```
> quotient phrase
>   > quotient phrase
>   >   > quotient pharse
```
> quotient phrase
>   > quotient phrase
>   >   > quotient pharse 

---

# 3. 목록

---
## 3-1 순서가 있는 목록
```
1. first
2. second
3. third
4. fourth
```

1. first
2. second
3. third
4. fourth

숫자를 이용한 목록은 오름차순으로 보여짐.
```
1. first
3. second
5. third
2. fourth
```
1. first
3. second
5. third
2. fourth

---

## 3-2 순서가 없는 목록
순서가 없는 목록은 *, +, - 문자를 사용
```
* 빨강
    * 녹색
        * 파랑
        
+ 빨강
    + 녹색
        + 파랑
        
- 빨강
    - 녹색
        - 파랑
```

* 빨강
    * 녹색
        * 파랑

+ 빨강
    + 녹색
        + 파랑

- 빨강
    - 녹색
        - 파랑
---

# 4. 코드 블럭

---
## 4-1 긴 코드 블럭
1. "```"사용
````
``` lang 
    content 
```
   ````

```java
    import java.util.*;
```
2. pre, code 사용
`<pre><code> code </code></pre>`

<pre><code> 
    code
</code></pre>

---
# 4-2 짧은 코드 블럭

```
`<html></html>` 사용
```
`<html></html>`

---

# 5. 구분선

```
* * *
***
- - -
---
```

* * *

***

- - -

---


# 6.표

---

```
| col1 | col2 | col3 |
| ---|---|---|
| v1 | v2 | v3|
```

| col1 | col2 | col3 |
| ---|---|---|
| v1 | v2 | v3|

---

# 7. 링크
```
[title] (link_rui)
[github] (https://github.com/khd325)
```

[github](https://github.com/khd325)
