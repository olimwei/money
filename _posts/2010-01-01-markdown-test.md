# 大标题 大小有6个级别的标题
## 中标题
### 字体变化

**加粗字体**， *斜字体*， ***加粗斜字体***， ~~化掉字体~~

### 列表

1. 有序列表1
2. 有序列表2
3. 有序列表3

- 无序列表1
- 无序列表2
- 无序列表3

1. 列表1
    - 列表嵌套1
    - 列表嵌套2
2. 列表2
3. 列表3

- [x] ~~完成的任务1~~
- [x] ~~完成的任务2~~
- [ ] 未完成的任务1
- [ ] 未完成的任务2

### 代码

`<p>This is the first item</p>`

`python3 -m install numpy`

```
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```

### 链接

[文字链接1](http://olim.ca)
[文字链接]: http://google.com
[文字链接2-谷歌][文字链接]

图片链接和文字链接不同的是前面有个感叹号。可以加鼠标移动到图片时显示的文字。

![走势图](http://money.olim.ca/assets/images/2024/2024-05-31-DXY.jpg "hover me")

[图片链接]: http://money.olim.ca/assets/images/2024/2024-05-31-DXY-fl.jpg "hover me"
![12345][图片链接]

![测试图片](../assets/images/2024/2024-05-31-DXY-fl.jpg)

> 疑问：如何限制图片显示的尺寸？

### 引用 用>符号

> 这是引用的内容。
> 1. 引用内容里包括的列表1
> 2. 引用内容里包括的列表2

### 表格的制作
| Syntax Expression | Long Description | Other Notes Included |
|:-----------|:-----------:|-----------:|
| Header | Title | Items |
| Paragraph | Text | Note |

| Rank | THING-TO-RANK |
|-----:|:--------------|
|     1|     第一个     |
|     2|     第二个     |
|     3|     第三个     |


### 水平线制作 用三个“-”"*""_"符号都可以

第一种水平线(三个破折号，建议使用)

---

第二种水平线（三个星号，有时候有问题）

******

第三种水平线（三个下划线，有时候有问题）
___

### 脚注
这句话包括一个脚注明。[^1]
[^1]: 第一个脚注。

### 高亮选择的段落 （检查是否正确显示）
1. 用“==”在所选段落的前后
2. 用<mark></mark>语言

I need to highlight these ==very important words==.
我需要高亮==这段重要的话。==

我需要<mark>高亮这几个字</mark>。

### 用HTML代码
```
<h1>This is a heading</h1>
<p>Paragraph...</p>

<hr />

<img src="auto-generated-path-to-file-when-you-upload-image" width="200">
<a href="https://github.com/im-luka">Follow me on GitHub</a>

<br />
<br />

<p>Quick hack for <strong><em>centering image</em></strong>?</p>
<p align="center"><img src="auto-generated-path-to-file-when-you-upload-image" /></p>

<details>
  <summary>One more quick hack? 🎭</summary>
  
  → Easy  
  → And simple
</details>
``` 
### 其它
$H_2$ O, $X^2$, $Y^3$

$H_2$ O; $3^4$; 5<sup>2</sup>; H<sub>2</sub>O

$\alpha$ $\beta$ $\delta$ $\gamma$ $\epsilon$ $\zeta$ $\eta$ $\theta$ $\iota$ $\kappa$ $\lambda$ $\mu$ $\nu$ $\xi$ $\pi$ $\rho$ $\sigma$ $\tau$ $\upsilon$ $\phi$ $\chi$ $\psi$ $\omega$

$\infty$; $+\infty$; $-\infty$

$\frac{3+8a}{5b+6}$

$\sum{3x^n}$

$\sum_{n=1}^N{3x^n}$

$\prod{3x^n}$

$\prod_{n=1}^N{3x^n}$

$\sqrt[5]{100}$

$\int^5_1{f(x)}{\rm d}x$

$\iint^5_1{f(x)}{\rm d}x$

$\iiint^5_1{f(x)}{\rm d}x$

$\lim_{n\rightarrow+\infty} n$

$\geq$; $\leq$; $\subset$; $\supset$; $\in$; $\pm$; $\cdot$ $\times$ $\div$ $\not=$ $\not<$ $\not\supset$ $\log$ $\ln$ $\bot$ $\angle$ $30^\circ$ $\sin$ $\cos$ $\tan$ $\leftarrow$ $\rightarrow$ $\uparrow$ $\downarrow$ $\longrightarrow$ 

$\log_2{18}$ 

$
  \begin{matrix}
   1 & 2 & 3 \\\
   4 & 5 & 6 \\\
   7 & 8 & 9
  \end{matrix}
$

$
 \begin{Bmatrix}
   1 & 2 & 3 \\\
   4 & 5 & 6 \\\
   7 & 8 & 9
  \end{Bmatrix}
$

$
 \begin{bmatrix}
   1 & 2 & 3 \\\
   4 & 5 & 6 \\\
   7 & 8 & 9
  \end{bmatrix}
$

$
\left[
\begin{matrix}
 1      & 2      & \cdots & 4      \\\
 7      & 6      & \cdots & 5      \\\
 \vdots & \vdots & \ddots & \vdots \\\
 8      & 9      & \cdots & 0      \\\
\end{matrix}
\right]
$

$\begin{bmatrix}
{a_{11}}&{a_{12}}&{\cdots}&{a_{1n}}\\\
{a_{21}}&{a_{22}}&{\cdots}&{a_{2n}}\\\
{\vdots}&{\vdots}&{\ddots}&{\vdots}\\\
{a_{m1}}&{a_{m2}}&{\cdots}&{a_{mn}}\\\
\end{bmatrix}$

$\begin{cases}
a_1x+b_1y+c_1z=d_1\\\
a_2x+b_2y+c_2z=d_2\\\
a_3x+b_3y+c_3z=d_3\\\
\end{cases}
$


