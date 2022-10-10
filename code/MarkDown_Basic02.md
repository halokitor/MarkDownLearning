---
title: MarkDown_Basic02
date: 2022-10-10 20:30:00
tags: 
  - MarkDown
# top: true
# sticky: 1
description: This is some MarkDown Learning Notes(Second Notes).
top_img: false
cover: https://s2.loli.net/2022/10/10/bGK81uRzdQqWkXw.png
mathjax: true
---

<font size = 6><b>This is a series of codes for learning MarkDown Grammar.</b></font>

## **CodeGrammar**
## **代码**

```markdown
At the command prompt,type `nano`.  
`` At the command prompt,type `nano` ``.
```

> At the command prompt,type `nano`.  
> `` At the command prompt,type `nano` ``.

### **Code Block**

```markdown
    <html>
    <head>
        <title>Test</title>
    </head>
```

    <html>
    <head>
        <title>Test</title>
    </head>

**or *fenced code blocks*.**

```markdown
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

## **Horizontal Rule**
## **分割线**

```markdown
Try to put a blank line before...

---

...and after a horizontal rule.
```

Try to put a blank line before...

---

...and after a horizontal rule.

## **Link**
## **超链接**

```markdown
This is a ***[GitHub](https://github.com/ "GitHub Offical Website")*** Link.  
```

This is a ***[GitHub](https://github.com/ "GitHub Offical Website")*** Link.  

## **网址URL** 
### **针对链接中有空格应该使用%20代替**

```markdown
> https://www.baidu.com  
> <https://github.com/>  
> [ex. link](https://www.example.com/my%20great%20page)  
> `https://github.com`
```

> https://www.baidu.com  
> <https://github.com/>  
> [ex. link](https://www.example.com/my%20great%20page)  
> `https://github.com`

## **应用类型链接**

```markdown
[hobbit-hole] [10010]  
[10010]:https://github.com/
```

[hobbit-hole] [10010]  
[10010]:https://github.com/  

### **链接到本地目录节点**

```markdown
Link to [Code Grammar](#Code Grammar)
```

> Link to [CodeGrammar](#CodeGrammar).

## **Image**
## **图片**

```markdown
![Markdown](./MarkDown_Basic02/markdown.png "Markdown") 
```

> ![Markdown](./MarkDown_Basic02/markdown.png) 

```markdown
[![Bilibili](./MarkDown_Basic02/bilibili.png)](https://bilibili.com/)
```

> [![Bilibili](./MarkDown_Basic02/bilibili.png) "Bilibili Offical Website"](https://bilibili.com/)


## **转义字符语法**

```markdown
- Without the backslash, this would be a bullet in an unordered list.   
\- Without the backslash, this would be a bullet in an unordered list. 
```

- Without the backslash, this would be a bullet in an unordered list.   
\- Without the backslash, this would be a bullet in an unordered list.  