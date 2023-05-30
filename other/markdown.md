# markdown

## 语法基本

I really like using Markdown.

I think I'll use it to format all of my documents from now on.

行间数学公式
$$
f(x)=2x^2+5x+3
$$
行内$\int\sqrt[3]{x}dx$

1. open the file
2. Find the following code block on line 21:

        <html>
          <head>
            <title>Test</title>
          </head>
          <body>
            <h1>代码块</h1>
          </body>
        </html>

3. Update the title to match the name of your website.
4. image
    ![Tux, the Linux mascot](img/Linux.png)

5. You can nest an unordered list in an ordered list, or vice versa.
    - Indented item
    - Indented item
    - Indented item
6. At the command prompt,type `nano` .
7. 如果不想用四个空格或两个制表符来创建代码块，请使用围栏式代码块

    ```
    import pandas as pd
    import numbers as ny
    data=pd.read_csv('read.csv')
    ```

---

这是一个链接语法 [markdown语法](https://markdown.com.cn/)。  

<https://markdown.com.cn/>

**[EFF](https://eff.org)**

插入图片的markdown语法：`![图片alt](图片链接 "图片title")`

![这是图片](https://markdown.com.cn/assets/img/philly-magic-garden.9c0b4415.jpg "Magic Gardens")

链接图片

[![沙漠岩石图片](https://markdown.com.cn/assets/img/shiprock.c3b9a023.jpg "shiprock")](https://markdown.com.cn)

#### 转义字符

\* Without the backslash, this would be a bullet in an unordered list.

AT&amp;T  

AT&T

4&lt;5

#### 内嵌HTML标签

This **word** is bold. This <em>word</em> is italic.

This is a regular paragraph.

<table>
    <tr>
        <th>Foo</th>
        <th>Foo</th>
        <th>Foo</th>
        <th>Foo</th>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
    <tr>
        <td></td>
        <td></td>
        <td></td>
        <td></td>
    </tr>
</table>

This is another regular paragraph.
