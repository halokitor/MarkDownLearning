# This is a code for learning MarkDown Grammar.
## Title Grammar
## 标题语法
> # Level 1
> ## Level 2
> ### Level 3
> #### Level 4
> ##### Level 5
> ###### Level 6
## Paragapha Grammar
## 段落语法
> Don't put tabs or spaces in front of your  paragraphs.
>
> Keep lines left-aligned like this.
## Line Break
## 换行
> This is the first line.  
> 句尾添加两个空格加回车即可进行换行  
> And this the second line.
## Bold
## 粗体
> This is **Bold**.
## Italic
> This is *Italic*.  
> This is ***Bold Italic***.
## 引用块语法
>  **The quarterly results look great!**
> 
> - Revenue was off the chart.
> - Profits were higher than ever.
> 
>  *Everything* is going according to **plan**.
## 列表语法（有序列表和无序列表）
### 有序列表
1. first item  
2. second item  
    Paragapha *insert*
   > 引用块  
3. third item
### 无序列表
- first item
    
    insert code block

        <html>
            <head>
                <title>Test</title>
            </head>

- second item
    
    > define block
    
    insert image block

    ![image,famer](./../images/farmer.png)

- third item

    list block insert

    - first block
    - second
    - third

## Code Grammar
## 代码语法
At the command prompt,type `nano`.  
`` At the command prompt,type `nano` ``.
## **Code Block**
    <html>
        <head>
            <title>Test</title>
        </head>

**or *fenced code blocks*.**
```json
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
## Horizontal Rule
## 分割线
Try to put a blank line before...

---

...and after a horizontal rule.
## Links Grammar
## 超链接语法
> This is a ***[GitHub](https://github.com/ "GitHub Offical Website")*** Link.  
## 网址URL 
### 针对连接中有空格应该使用%20代替
> https://www.baidu.com  
> <https://github.com/>  
> [link](https://www.example.com/my%20great%20page)  
> `https://github.com`
## 应用类型连接
[hobbit-hole][1]  
[1]: https://en.wikipedia.org/wiki/Hobbit#Lifestyle  
> 连接到[代码语法](#代码语法)
## 图片语法
> ![Farmer](../images/farmer.png) 
    
    图片添加链接

> [![Farmer](../images/farmer.png)](https://github.com/)
## 转义字符语法
* Without the backslash, this would be a bullet in an unordered list.

  \* Without the backslash, this would be a bullet in an unordered list.  
## 内嵌 HTML 标签
This **word** is bold. This <em>word</em> is italic.  
## 区块标签
This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
    </tr>
    <p>This is a p test.</p>
</table>

This is another regular paragraph.  
## 表格
> | 列1 | 列2 | 列3 |
> | :--- | :---: | ---:|
> | Header | Title | Name |
> | `halo` | [kitor](https://github.com/) | **ki** |
## 脚注
Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.
```
Indent paragraphs to include them in the footnote.

`{ my code }`

Add as many paragraphs as you like.
```
## 标题编号连接
### My Great Heading {#代码语法}
## 定义列表
First Term  
: This is the definition of the first term.

Second Term  
: This is one definition of the second term.
: This is another definition of the second term.
## 删除线
~~世界是平坦的。~~ 我们现在知道世界是圆的。
## 任务列表语法
- [x] Write the press release
- [ ] update the website
- [ ] sport
## 使用 Emoji 表情
去露营了！ :tent: 很快回来。

真好笑！ :joy:
## 数学公式
$$
\frac{\partial y}{\partial x} = x + 2\sqrt{a}x 
$$
$$\theta=x^2$$
## 名词符号
$H_2O$  
$X^2$  
<mark>HighLight Text</mark>  
<font color = red>**Color Text**</font>
## 使用HTML语言嵌入内容
<iframe src="//player.bilibili.com/player.html?aid=327623069&bvid=BV1JA411h7Gw&cid=171385214&page=1"></frame>