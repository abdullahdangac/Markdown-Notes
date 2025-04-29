# Markdown Notes

## CONTENTS
[1. TEXT](#1-text)  
&emsp; [1.1. Header](#11-header)  
&emsp; [1.2. Space](#12-space)  
&emsp; [1.3. Line Break](#13-line-break)  
&emsp; [1.4. Styling Text](#14-styling-text)  
&emsp; [1.5. Aligning Text](#15-aligning-text)  
&emsp; [1.6. List Text](#16-list-text)  
&emsp; [1.7. Quote Text](#17-quote-text)  
&emsp; [1.8. Collapsed Section](#18-collapsed-section)  
&emsp; [1.9. Alerts](#19-alerts)  
&emsp; [1.10. Hiding Content](#110-hiding-content)  

[2. CODE](#2-code)  
&emsp; [2.1. Inline Code](#21-inline-code)  
&emsp; [2.2. Code Block](#22-code-block)  

[3. LINK](#3-link)  
&emsp; [3.1. Text Link](#31-text-link)  
&emsp; [3.2. Image as Link](#32-images-as-link)  
&emsp; [3.3. Section Link](#33-section-link)  
&emsp; [3.4. Reference Link](#34-reference-link)  

[4. IMAGE](#4-image)  
&emsp; [4.1. Resizing Image](#41-resizing-image)  
&emsp; [4.2. Aligning Image](#42-aligning-image)  

[5. TABLE](#5-table)  
&emsp; [5.1. Aligning Text in Table](#51-aligning-text-in-table)  
&emsp; [5.2. Side by Side Tables](#52-side-by-side-tables)  

[6. MATHEMATICAL EXPRESSION](#6-mathematical-expression)  
&emsp; [6.1. Inline Mathematical Expression](#61-inline-mathematical-expression)  
&emsp; [6.2. Mathematical Expression Block](#62-mathematical-expression-block)  
&emsp; [6.3. Arithmetic Expressions](#63-arithmetic-expressions)  
&emsp; [6.4. Equality Expressions](#64-equality-expressions)  
&emsp; [6.5. Comparison Expressions](#65-comparison-expressions)  
&emsp; [6.6. Algebra Expressions](#66-algebra-expressions)  
&emsp; [6.7. Angle Expressions](#67-angle-expressions)  
&emsp; [6.8. Probability & Statistics](#68-probability--statistics)  
&emsp; [6.9. Complex Numbers](#69-complex-numbers)  
&emsp; [6.10. Linear Algebra: Vectors](#610-linear-algebra-vectors)  
&emsp; [6.11. Linear Algebra: Matrices](#611-linear-algebra-matrices)  
&emsp; [6.12. Calculus Expressions](#612-calculus-expressions)  
&emsp; [6.13. Greek Alphabet](#613-greek-alphabet)  

<br/>
<br/>

---------------------------------------------------------

<br/>
<br/>

# 1. TEXT
## 1.1. Header
```markdown
# H1 (Biggest)
## H2 
### H3 
#### H4 
##### H5 
###### H6 (Smallest)
```
# H1 (Biggest)
## H2 
### H3 
#### H4 
##### H5 
###### H6 (Smallest)

<br/>
<br/>

## 1.2. Space
```markdown
&nbsp;  to add a single space.
&ensp;  to add 2 spaces.
&emsp;  to add 4 spaces.
```

### Example
```markdown
No space  
&nbsp;1 space  
&ensp;2 spaces  
&emsp;4 spaces
```
No space  
&nbsp;1 space  
&ensp;2 spaces  
&emsp;4 spaces  

<br/>
<br/>

## 1.3. Line Break
An `.md` file, would render on one line without a line break.
```markdown
Markdown
Notes
```
Markdown
Notes

<br/>

To create a line break in an `.md` file, you will need to include one of the following:

- Include two spaces at the end of the first line.
  ```markdown
  Markdown<space><space>
  Notes
  ```
  Markdown  
  Notes

- Include a backslash at the end of the first line.
  ```markdown
  Markdown\
  Notes
  ```
  Markdown\
  Notes

- Include an HTML single line break tag at the end of the first line.
  ```markdown
  Markdown<br/>
  Notes
  ```
  Markdown<br/>
  Notes

If you leave a blank line between two lines, both `.md` files and Markdown will render the two lines separated by the blank line:
```markdown
Markdown

Notes
```
Markdown

Notes

<br/>
<br/>

## 1.4. Styling Text
| Style           | Syntax             | Example                         | Output                        |
|-----------------|--------------------|---------------------------------|-------------------------------|
| Bold            | `** **` or `__ __` | `**Bold**`                      | **Bold**                      |
| Italic          | `* *` or `_ _`     | `_Italic_`                      | _Italic_                      |
| Strike-through  | `~~ ~~` or `~ ~`   | `~Strike-through~`              | ~Strike-through~              |
| Bold and Italic | `*** ***`          | `***Bold and Italic***`         | ***Bold and Italic***         |
| Underline       | `<ins> </ins>`     | `<ins>Underline</ins>`          | <ins>Underline</ins>          |
| Subscript       | `<sub> </sub>`     | `A <sub>subscript</sub> text`   | A <sub>subscript</sub> text   |
| Superscript     | `<sup> </sup>`     | `A <sup>superscript</sup> text` | A <sup>superscript</sup> text |

<br/>
<br/>

## 1.5. Aligning Text
```markdown
<p align="left">Left-aligned text</p>  
<p align="center">Center-aligned text</p>  
<p align="right">Right-aligned text</p>
```
<p align="left">Left-aligned text</p>  
<p align="center">Center-aligned text</p>  
<p align="right">Right-aligned text</p>  

<br/>
<br/>

## 1.6. List Text
```markdown
- Element

+ Element

* Element
```
- Element
+ Element
* Element

<br/>

### 1.6.1. Bullet List
```markdown
- Element 1
- Element 2
  - Sub-element 1
    - Sub-element 1.a
```
- Element 1
- Element 2
  - Element 2.1
    - Element 2.1.a

<br/>

### 1.6.2. Ordered List
```markdown
1. Element 1
2. Element 2
   1. Sub-element 1
      1. Sub-element 1.a
```
1. Element 1
2. Element 2
   1. Element 2.1
      1. Element 2.1.a

<br/>

### 1.6.3. Task List
```markdown
- [x] Completed
- [ ] Not completed
```
- [x] Completed
- [ ] Not completed

<br/>
<br/>

## 1.7. Quote Text
```markdown
> This is a quote.
```

> This is a quote.

<br/>
<br/>

## 1.8. Collapsed Section
```markdown
<details>
<summary>Collapsed section</summary>

Text in collapsed section.

</details>
```
<details>
<summary>Collapsed section</summary>
  
Text in collapsed section.

</details>

<br/>
<br/>

## 1.9. Alerts
```markdown
> :memo: **NOTE**: Useful information that users should know, even when skimming content.

> :bulb: **TIP**: Helpful advice for doing things better or more easily.

> :warning: **WARNING**: Urgent info that needs immediate user attention to avoid problems.

> :heavy_check_mark: **CHECK MARK**: can be used to indicate when an action is complete or that something is correct.
```
> :memo: **NOTE**: Useful information that users should know, even when skimming content.

> :bulb: **TIP**: Helpful advice for doing things better or more easily.

> :warning: **WARNING**: Urgent info that needs immediate user attention to avoid problems.

> :heavy_check_mark: **CHECK MARK**: can be used to indicate when an action is complete or that something is correct.

<br/>

There is another use for GitHub:  
```markdown
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```
> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.

<br/>
<br/>

## 1.10. Hiding Content
```markdown
This content will appear in the rendered Markdown
<!-- This content will not appear in the rendered Markdown -->
```
this content will appear in the rendered Markdown
<!-- This content will not appear in the rendered Markdown -->

<br/>
<br/>

---------------------------------------------------------

<br/>
<br/>

# 2. CODE
## 2.1. Inline Code
```markdown
This is `inline code` example.
```
This is `inline code` example.

<br/>

## 2.2. Code Block
````markdown
```code-language
Code Block
```
````

### Example
#### Markdown text
````markdown
```cpp
#include <iostream>

int main()
{
  // some code
  return 0;
}
```
````

#### Output
```cpp
#include <iostream>

int main()
{
  // some code
  return 0;
}
```


<br/>
<br/>

---------------------------------------------------------

<br/>
<br/>

# 3. LINK
## 3.1. Text Link
```markdown
[Link Text](URL "Title")
```

### Example
```markdown
[Markdown Notes](https://github.com/abdullahdangac/Markdown-Notes "Markdown Notes")
```
[Markdown Notes](https://github.com/abdullahdangac/Markdown-Notes "Markdown Notes")

<br/>

## 3.2. Images as Link
```
[![Image Alt Text](image-url.jpg)](hyperlink-url)
```

### Example
#### Icon
```markdown
[![LinkedIn](https://i.sstatic.net/gVE0j.png)](https://www.linkedin.com/in/abdullahdangac "LinkedIn Profile")
```

[![LinkedIn](https://i.sstatic.net/gVE0j.png)](https://www.linkedin.com/in/abdullahdangac "LinkedIn Profile")  

<br/>

#### Badge
```markdown
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdullahdangac/)  
```
[![LinkedIn](https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdullahdangac/)  

<br/>

> [!TIP]
> You can find [some Markdown badges](https://ileriayo.github.io/markdown-badges/) here.

<br/>

## 3.3. Section Link

```markdown
### Sample Section

#### Sample Subsection

Link to the Sample Section: [Link Text](#sample-section)  
Link to the Sample Subsection: [Link Text](#sample-subsection)


### This'll be a _Helpful_ Section About the Greek Letter (e.g. β)!
A heading containing characters not allowed in fragments, UTF-8 characters, two
consecutive spaces between the first and second words, and formatting.

Link to the helpful section: [Link Text](#thisll-be-a-helpful-section-about-the-greek-letter-e.g.-β).
```

### Sample Section

#### Sample Subsection

Link to the Sample Section: [Link Text](#sample-section)  
Link to the Sample Subsection: [Link Text](#sample-subsection)

<br/>

### This'll be a _Helpful_ Section About the Greek Letter β!
A heading containing characters not allowed in fragments, UTF-8 characters, two
consecutive spaces between the first and second words, and formatting.

Link to the helpful section: [Link Text](#thisll-be-a-helpful-section-about-the-greek-letter-β)

<br/>

## 3.4. Reference Link
```markdown
Use link as [reference-style][reference link text] with new link title.  
Or leave title empty and use the [reference link text] itself.

[reference link text]: https://www.somewebsite.org
```
Use link as [reference-style][reference link text] with new link title.  
Or leave title empty and use the [reference link text] itself.

[reference link text]: https://www.somewebsite.org

### Example
```markdown
[CMake] :  an open source, cross-platform family of tools designed to build, test, and package software.  
[C++ Reference][cppreference.com] :  a reference guide for C++ programming language.
  
[CMake]: https://cmake.org/
[cppreference.com]: https://en.cppreference.com  
```
[CMake] is an open source tool designed to build, test and package software.  
[C++ Reference][cppreference.com] is a reference guide for C++ programming language.
  
[CMake]: https://cmake.org/
[cppreference.com]: https://en.cppreference.com  

<br/>
<br/>

---------------------------------------------------------

<br/>
<br/>

# 4. IMAGE
```markdown
![Alt Text](image-url.jpg "Image Title")
```

### Example
```markdown
![Markdown Mark](https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png)
```
![Markdown Mark](https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png)

<br/>

## 4.1. Resizing Image
#### Resize with pixel
```markdown
<img src="image_name.png" alt="Alt Text" width=300 height=450 title="Image Title"/>
```

#### Resize with scaling percent
```markdown
<img src="image_name.png" alt="Alt Text" width="50%" height="50%" title="Image Title"/>
```

### Example
```markdown
<img src="https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png" width=104 height=64/>
```
<img src="https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png" width=104 height=64/>

```markdown
<img src="https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png" width=10.5% height=10.5%/>
```
<img src="https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png" width=10.5% height=10.5%/>

<br/>

## 4.2. Aligning Image
```markdown
<p align="align-type">
  <img src="image_name.png" alt="Alt Text" width="50%" height="50%" title="Image Title"/>
</p>
```

### Example
```markdown
<p align="left">
  <img src="https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png" width=10.5% height=10.5%/>
</p>

<p align="center">
  <img src="https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png" width=10.5% height=10.5%/>
</p>

<p align="right">
  <img src="https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png" width=10.5% height=10.5%/>
</p>
```
<p align="left">
  <img src="https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png" width=10.5% height=10.5%/>
</p>

<p align="center">
  <img src="https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png" width=10.5% height=10.5%/>
</p>

<p align="right">
  <img src="https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png" width=10.5% height=10.5%/>
</p>

<br/>
<br/>

---------------------------------------------------------

<br/>
<br/>

# 5. TABLE
```markdown
|A |B |C |
|--|--|--|
|1 |2 |3 |
|4 |5 |6 |
|7 |8 |9 |
```
|A |B |C |
|--|--|--|
|1 |2 |3 |
|4 |5 |6 |
|7 |8 |9 |

<br/>

## 5.1. Aligning Text in Table
```markdown
| Left-aligned | Center-aligned | Right-aligned |
|:-------------|:--------------:|--------------:|
| Text         | Text           | Text          |
| Text         | Text           | Text          |
```

| Left-aligned | Center-aligned | Right-aligned |
|:-------------|:--------------:|--------------:|
| Text         | Text           | Text          |
| Text         | Text           | Text          |

- `:--` means the column is left aligned.
- `--:` means the column is right aligned.
- `:-:` means the column is center aligned.

<br/>

## 5.2. Side by Side Tables
```markdown
<table>
<tr><th>First Table</th><th>Second Table</th></tr>
<tr><td>

|A    |B    |C    |D    |
|:---:|:---:|:---:|:---:|
|0    |1    |2    |3    |
|7    |8    |9    |10   |

</td><td>
  
|E    |F    |G    |
|:---:|:---:|:---:|
|4    |5    |6    |
|11   |12   |13   |

</td></tr>
</table>
```
<table>
<tr><th>First Table</th><th>Second Table</th></tr>
<tr><td>

|A    |B    |C    |D    |
|:---:|:---:|:---:|:---:|
|0    |1    |2    |3    |
|7    |8    |9    |10   |

</td><td>
  
|E    |F    |G    |
|:---:|:---:|:---:|
|4    |5    |6    |
|11   |12   |13   |

</td></tr>
</table>

<br/>
<br/>

---------------------------------------------------------

<br/>
<br/>

# 6. MATHEMATICAL EXPRESSION
## 6.1. Inline Mathematical Expression
```markdown
$\sqrt{3x-1}+(1+x)^2$
```
$\sqrt{3x-1}+(1+x)^2$

<br/>

## 6.2. Mathematical Expression Block
```markdown
$$
\sqrt{3x-1}+(1+x)^2
$$
```
$$
\sqrt{3x-1}+(1+x)^2
$$

````
```math
\sqrt{3x-1}+(1+x)^2
```
````
```math
\sqrt{3x-1}+(1+x)^2
```

<br/>

## 6.3. Arithmetic Expressions
|Notation |Example |Markdown Format |
|:---|:---:|:---:|
|Addition                                   | $x+y$                                                           |  `$x+y$`  |
|Subtraction                                | $x-y$                                                           |  `$x-y`  |
|Multiplication                             | $x \times y$ <br/> $x \ast y$ <br/> $x \cdot y$                 |  `$x \times y$` <br/> `$x \ast y$` <br/> `$x \cdot y$`  |
|Division                                   | $x \colon y$ <br/> $x / y$ <br/> $x \div y$ <br/> $\frac{x}{y}$ |  `$x \colon y$` <br/> `$x / y$` <br/> `$x \div y$` <br/> `$\frac{x}{y}$`  |
|Remainder / Modulo                         | $x \mod y$                                                      |  `$x \mod y$`  |
|Negative Value	                            | $-x$                                                            |  `$-x$`  |
|Plus or Minus <br/> Minus or Plus          | $\pm x$ <br/> $\mp x$                                           |  `$\pm x$` <br/> `$\mp x$`  |
|Squared <br/> Cubed <br/> nth-Power        | $x^2$ <br/> $x^3$ <br/> $x^n$                                   |  `$x^2$` <br/> `$x^3$` <br/> `$x^n$`  |
|Square Root <br/> Cube Root <br/> nth-Root | $\sqrt{x}$ <br/> $\sqrt[3]{x}$ <br/> $\sqrt[n]{x}$              |  `$\sqrt{x}$` <br/> `$\sqrt[3]{x}$` <br/> `$\sqrt[n]{x}`  |

<br/>

## 6.4. Equality Expressions
|Notation |Example |Markdown Format |
|:---|:---:|:---:|
|Equals                    | $x=y$         |  `$x=y$`  |
|Not Equals	               | $x \neq y$    |  `$x \neq y$`  |
|Identical / Equivalent To | $x \equiv y$  |  `$x \equiv y$`  |
|Proportional To           | $x \propto y$ |  `$x \propto y$`  |
|Approximately Equal To	   | $x \approx y$ |  `$x \approx y$`  |

<br/>

## 6.5. Comparison Expressions
|Notation |Example |Markdown Format |
|:---|:---:|:---:|
|Less Than <br/> Greater Than                   | $a<b$ <br/> $a>b$           |  `$a<b$` <br/> `$a>b$`  |
|Less Than or Equal <br/> Greater Than or Equal | $a \leq b$ <br/> $a \geq b$ |  `$a \leq b$` <br/> `$a \geq b$`  |
|Much Smaller Than <br/> Much Larger Than       | $a \ll b$ <br/> $a \gg b$   |  `$a \ll b$` <br/> `$a \gg b$`  |

<br/>

## 6.6. Algebra Expressions
|Notation |Example |Markdown Format |
|:---|:---:|:---:|
|Factorial                  | $x!$                           |  `$x!$`  |
|Absolute Value             | $\|-x\|$                       |  `$\|-x\|$`  |
|Function                   | $f(x)$                         |  `$f(x)$`  |
|Change or Difference       | $\Delta x = x_1 - x_0$         |  `$\Delta x = x_1 - x_0$`  |
|Pi                         | $\pi = 3.14159 \ldots$         |  `$\pi = 3.14159...$`  |
|Euler’s Constant           | $e = 2.71828 \ldots$           |  `$e = 2.71828...$`  |
|Sum                        | $\displaystyle\sum_{k=0}^n k$  |  `$\displaystyle\sum_{k=0}^n k$`  |
|Series Product             | $\displaystyle\prod_{x=0}^n x$ |  `$\displaystyle\prod_{x=0}^n x$`  |
|Brackets <br/> Parentheses | $[\ldots]$ <br/> $(\ldots)$    |  `$[...]$` <br/> `$(...)$`  |

<br/>

## 6.7. Angle Expressions
|Notation |Example |Markdown Format |
|:---|:---:|:---:|
|Angle                    | $\angle$             |  `$\angle$`  |
|Degree, Arc Min, Arc Sec | $30\degree 45' 30''$ |  `$30\degree 40\rq 50\rq\rq$`  |
|Radians                  | $2\pi rad$           |  `$2\pi rad$`  |

<br/>

## 6.8. Probability & Statistics
|Notation |Example |Markdown Format |
|:---|:---:|:---:|
|Probability of Event A         | $P(A)$ or $\Pr(A)$                                   |  `$P(A)$ or $\Pr(A)$`  |
|Intersection Prob. of A & B    | $P(A \cap B)$                                        |  `$P(A \cap B)$`  |
|Union Prob. of A or B          | $P(A \cup B)$                                        |  `$P(A \cup B)$`  |
|Conditional Prob. of A Given B | $P(A\|B)$                                            |  `$P(A\|B)$`  |
|Median                         | $\tilde{x}$                                          |  `$\tilde{x}$`  |
|Population Mean                | $\mu$ <br/> $\overline{x}$ <br/> $\langle x \rangle$ |  `$\mu$` <br/> `$\overline{x}$` <br/> `$\langle x \rangle$`  |
|Standard Deviation             | $\sigma$                                             |  `$\sigma$`  |
|Varience                       | $\sigma^2$                                           |  `$\sigma^2$`  |

<br/>

## 6.9. Complex Numbers
|Notation |Example |Markdown Format |
|:---|:---:|:---:|
|Imaginary Unit `i`	              | $z = a + bi$        |  `$z = a + bi$`  |
|Real Part Of Complex Number      | $\text{Re}(z)=a$    |  `$\text{Re}(z) = a$`  |
|Imaginary Part Of Complex Number | $\text{Im}(z)=b$    |  `$\text{Im}(z) = b$`  |
|Complex Conjugate                | $\bar{z}=z^*=a-bi$  |  `$\bar{z} = z^* = a - bi$`  |

<br/>

## 6.10. Linear Algebra: Vectors
#### Row Vector
```markdown
$$
v = \begin{pmatrix}
1 & 2 & 3
\end{pmatrix}
$$
```
$$
v = \begin{pmatrix}
1 & 2 & 3
\end{pmatrix}
$$

#### Column Vector
|Notation |Example |Markdown Format |
|:---|:---:|:---:|
|Vectors	     | $\mathbf{v}$ <br/> $\overline{v}$ <br/> $\vec{v}$                       |  `$\mathbf{v}$` <br/> `$\overline{v}$` <br/> `$\vec{v}$`  |
|Dot Product   | $\mathbf{v} \cdot \mathbf{w}$ <br/> $(v,w)$ <br/> $\left<v \| w\right>$ |  `$\mathbf{v} \cdot \mathbf{w}$` <br/> `$(v,w)$` <br/> `$\left< v \| w \right>$ `  |
|Cross Product | $v \times w$                                                            |  `$v \times w$`  |
|Length of v   | $\|v\|$                                                                 |  `$\|v\|$`  |
|Norm of v     | $\|\|v\|\|$                                                             |  `$\|\|v\|\|$`  |

```markdown
$$
w = \begin{pmatrix}
4 \\
5 \\
6 \\
\end{pmatrix}
$$
```
$$
w = \begin{pmatrix}
4 \\
5 \\
6 \\
\end{pmatrix}
$$

<br/>

## 6.11. Linear Algebra: Matrices
|Notation |Example |Markdown Format |
|:---|:---:|:---:|
|Product	           | $A \cdot B$   |  `$A \cdot B$`  |
|Hadamard Product    | $A \circ B$   |  `$A \circ B$`  |
|Kronecker Product   | $A \otimes B$ |  `$A \otimes B$`  |
|Transposed Matrix   | $A^T$         |  `$A^T$`  |
|Conjugate Transpose | $A^\ast$      |  `$A^\ast$`  |
|Inverse Matrix      | $A^{-1}$      |  `$A^{-1}$`  |
|Determinant         | $\|A\|$       |  `$\|A\|$`  |
|Norm                | $\|\|A\|\|$   |  `$\|\|A\|\|$`  |

#### Matrix
```markdown
$$
A = \begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6
\end{bmatrix}
$$
```
$$
A = \begin{bmatrix}
1 & 2 & 3 \\
4 & 5 & 6
\end{bmatrix}
$$

<br/>

## 6.12. Calculus Expressions
### 6.12.1. Partial Function	
```markdown
$$
f(x) = \begin{cases}
x & \text{if } a>b \\
y & \text{if } c>d
\end{cases}
$$
```
$$
f(x) = \begin{cases}
x & \text{if } a>b \\
y & \text{if } c>d
\end{cases}
$$

### 6.12.2. Integration
```markdown
$$
\int_{a}^{b} dx
$$
```
$$
\int_{a}^{b} dx
$$

### 6.12.3. Differentiation	
#### First Derivative
```markdown
$$
\frac{df}{dx}
$$
```
$$
\frac{df}{dx}
$$

#### Partial Derivative
```markdown
$$
\frac{\partial f}{\partial x}
$$
```
$$
\frac{\partial f}{\partial x}
$$

#### First and Second Derivative of Function
```markdown
$$
f\rq
f\rq\rq
$$
```
$$
f' \ \ \ \ f''
$$

#### First and Second Derivative With Respect To Time
```markdown
$$
\dot f
\ddot f
$$
```
$$
\dot f \ \ \ \ \ddot f
$$

<br/>

## 6.13. Greek Alphabet
|Letter |Lower |Markdown Format |Upper |Markdown Format |
|:---|:---:|:---:|:---:|:---:|
|Alpha |$\alpha$ |  `$\alpha$`  |$\text{A}$ |  `$\Alpha$`  |
|Beta |$\beta$ |  `$\beta$`  |$\text{B}$ |  `$\Beta$`  |
|Gamma |$\gamma$ |  `$\gamma$`  |$\Gamma$ |  `$\Gamma$`  |
|Delta |$\delta$ |  `$\delta$`  |$\Delta$ |  `$\Delta$`  |
|Epsilon |$\epsilon$ |  `$\epsilon$`  |$\text{E}$ |  `$\Epsilon$`  |
|Zeta |$\zeta$ | `$\zeta$`  |$\text{Z}$ |  `$\Zeta$`  |
|Eta |$\eta$ |  `$\eta$`  |$\text{H}$ |  `$\Eta$`  |
|Theta |$\theta$ |  `$\theta$`  |$\Theta$ |  `$\Theta$`  |
|Iota |$\iota$ |  `$\iota$`  |$\text{I}$ |  `$\Iota$`  |
|Kappa |$\kappa$ |  `$\kappa$`  |$\text{K}$ |  `$\Kappa$`  |
|Lambda |$\lambda$ |  `$\lambda$`  |$\Lambda$ |  `$\Lambda$`  |
|Mu |$\mu$ |  `$\mu$`  |$\text{M}$ |  `$\Mu$`  |
|Nu |$\nu$ |  `$\nu$`  |$\text{N}$ |  `$\Nu$`  |
|Xi |$\xi$ |  `$\xi$`  |$\Xi$ |  `$\Xi$`  |
|Omicron |$\omicron$ |  `$\omicron$`  |$\text{O}$ |  `$\Omicron$`  |
|Pi |$\pi$ |  `$\pi$`  |$\Pi$ |  `$\Pi$`  |
|Rho |$\rho$ |  `$\rho$`  |$\text{P}$ |  `$\Rho$`  |
|Sigma |$\sigma$ |  `$\sigma$`  |$\Sigma$ |  `$\Sigma$`  |
|Tau |$\tau$ |  `$\tau$`  |$\text{T}$ |  `$\Tau$`  |
|Upsilon |$\upsilon$ |  `$\upsilon$`  |$\Upsilon$ |  `$\Upsilon$`  |
|Phi |$\phi$ |  `$\phi$`  |$\Phi$ |  `$\Phi$`  |
|Chi |$\chi$ |  `$\chi$`  |$\text{X}$ |  `$\Chi$`  |
|Psi |$\psi$ |  `$\psi$`  |$\Psi$ |  `$\Psi$`  |
|Omega |$\omega$ |  `$\omega$`  |$\Omega$ |  `$\Omega$`  |
