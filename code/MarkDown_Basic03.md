---
title: MarkDown_Basic03
date: 2022-10-10 20:55:00
tags: 
  - MarkDown
# top: true
# sticky: 1
description: This is some MarkDown Learning Notes(Third Notes).
top_img: false
cover: https://s2.loli.net/2022/10/10/bGK81uRzdQqWkXw.png
mathjax: true
---

<font size = 6><b>This is a series of codes for learning MarkDown Grammar.</b></font>

## **内嵌 HTML 标签**

```markdown
This **word** is bold. This <em>word</em> is italic.
```

This **word** is bold. This <em>word</em> is italic. 

### **区块标签**

```markdown
This is a regular paragraph.
<table>
    <p>This is a p test.</p>
    <tr>
        <td>Foo</td>
    </tr>
</table>
This is another regular paragraph. 
```

This is a regular paragraph.
<table>
    <p>This is a p test.</p>
    <tr>
        <td>Foo</td>
    </tr>
</table>  
This is another regular paragraph.  

## **表格**

```markdown
|列1|列2|列3|
|:---|:---:|---:|
|Header|Title|Name|
|`halo`|[kitor](https://github.com/)|**ki**|
```

> |列1|列2|列3|
> |:---|:---:|---:|
> |Header|Title|Name|
> |`halo`|[kitor](https://github.com/)|**ki**|

## **脚注**

```markdown
Here's a simple footnote[^footnote], and here's a longer one[^bignote].

[^footnote]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.
```

Here's a simple footnote[^footnote], and here's a longer one[^bignote].

[^footnote]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.
```
Indent paragraphs to include them in the footnote.

`{ my code }`

Add as many paragraphs as you like.
```

## **删除线**

```markdown
~~世界是平坦的。~~ 我们现在知道世界是圆的。
```

~~世界是平坦的。~~ 我们现在知道世界是圆的。

## **任务列表语法**

```markdown
    - [x] Write the press release
    - [ ] update the website
    - [ ] sport
```

- [x] Write the press release
- [ ] update the website
- [ ] sport

## **使用 Emoji 表情**

```markdown
去露营了！ :tent: 很快回来。

真好笑！ :joy:
```

去露营了！ :tent: 很快回来。

真好笑！ :joy:

## **数学公式(需支持mathjax)**

```markdown
$$
\frac{\partial y}{\partial x} = x + 2\sqrt{a}x 
$$
$$\theta=x^2$$
```

$$
\frac{\partial y}{\partial x} = x + 2\sqrt{a}x 
$$
$$\theta=x^2$$

## **文字样式**

```markdown
$H_2O$  
$X^2$  
<mark>HighLight Text</mark>  
<font color = red><b>Red Color Text</b></font>
```

$H_2O$  
$X^2$  
<mark>HighLight Text</mark>  
<font color = red><b>Red Color Text</b></font>

## 使用HTML语言嵌入内容

```html
    <iframe src="//player.bilibili.com/player.html?aid=327623069&bvid=BV1JA411h7Gw&cid=171385214&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
```

<iframe src="//player.bilibili.com/player.html?aid=327623069&bvid=BV1JA411h7Gw&cid=171385214&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>
