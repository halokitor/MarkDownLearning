---
title: MarkDown_Basic01
date: 2022-10-08 17:51:57
tags: 
  - MarkDown
# top: true
# sticky: 1
description: This is some MarkDown Learning Notes(First Notes).
top_img: false
cover: https://s2.loli.net/2022/10/10/bGK81uRzdQqWkXw.png
mathjax: true
---

<font size = 6><b>This is a series of codes for learning MarkDown Grammar.</b></font>

## **Title Grammar**
## **标题**

```markdown
# Level 1
## Level 2
### Level 3
#### Level 4
##### Level 5
###### Level 6
```

## **Paragapha Grammar**
## **段落**

```markdown
Don't put tabs or spaces in front of your  paragraphs.  
Keep lines left-aligned like this.
```

Don't put tabs or spaces in front of your  paragraphs.  
Keep lines left-aligned like this.

## **Line Break**
## **换行**

```markdown
This is the first line.  
句尾添加两个空格加回车即可进行换行  
And this the second line.
```

This is the first line.  
句尾添加两个空格加回车即可进行换行  
And this the second line.

## **Bold && Italic**
## **粗体** *斜体*

```markdown
This is **Bold** *Italic* && ***BlodItalic***.
```

This is ***Bold Italic*** && ***BlodItalic***.

## **引用块语法**

```markdown
**The quarterly results look great!**  

- Revenue was off the chart.  
- Profits were higher than ever.  

*Everything* is going according to **plan**.
```

>  **The quarterly results look great!**
> 
> - Revenue was off the chart.
> - Profits were higher than ever.
> 
>  *Everything* is going according to **plan**.

## **列表语法（有序列表和无序列表）**
### **有序列表**

```markdown
1. first item  
2. second item  
    Paragapha insert
    - 引用块  
3. third item
```

1. first item  
2. second item  
    Paragapha insert
   > 引用块  
3. third item

### **无序列表**

```markdown
    - first item(insert code block)

            <html>
            <head>
                <title>Test</title>
            </head>

    - second item(insert image block)

        ![image,famer](./MarkDownLearning/farmer.png)

    - third item(insert list block)

        - first block
        - second
        - third
```

- first item(insert code block)

    ```
        <html>
        <head>
            <title>Test</title>
        </head>
    ```

- second item(insert image block)

    ![image,famer](./MarkDown_Basic01/farmer.png)

- third item(insert list block)

    - first block
    - second
    - third