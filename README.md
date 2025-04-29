# Markdown Notes

## CONTENTS
[1. TEXT](#text)  
&emsp; [1.1. Header](#header)  
&emsp; [1.2. Space](#header)  
&emsp; [1.3. Line Break](#header)  
&emsp; [1.4. Styling Text](#styling-text)  
&emsp; [1.5. Aligning Text](#aligning-text)  
&emsp; [1.6. List Text](#list-text)  
&emsp; [1.7. Quote Text](#quote-text)  
&emsp; [1.8. Collapsed Section](#collapsed-section)  
&emsp; [1.9. Alerts](#alerts)  
&emsp; [1.10. Hiding Content](#hiding-content)  

[2. CODE](#code)  
&emsp; [2.1. Inline Code](#inline-code)  
&emsp; [2.2. Code Block](#code-block)  

[3. LINK](#link)  
&emsp; [3.1. Text Link](#text-link)  
&emsp; [3.2. Image as Link](#images-as-link)  
&emsp; [3.3. Section Link](#section-link)  
&emsp; [3.4. Reference Link](#reference-link)  

[4. IMAGE](#image)  
&emsp; [4.1. Resizing Image](#resizing-image)  
&emsp; [4.2. Aligning Image](#aligning-image)  

[5. TABLE](#table)  
&emsp; [5.1. Aligning Text in Table](#aligning-text-in-table)  
&emsp; [5.2. Side by Side Tables](#side-by-side-tables)  

[6. MATHEMATICAL EXPRESSION](#mathematical-expression)  

<br/>
<br/>

---------------------------------------------------------

<br/>
<br/>

# TEXT
## Header
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

## Space
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

## Line Break
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

## Styling Text
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

## Aligning Text
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

## List Text
```markdown
- Element

+ Element

* Element
```
- Element
+ Element
* Element

<br/>

### Bullet List
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

### Ordered List
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

### Task List
```markdown
- [x] Completed
- [ ] Not completed
```
- [x] Completed
- [ ] Not completed

<br/>
<br/>

## Quote Text
```markdown
> This is a quote.
```

> This is a quote.

<br/>
<br/>

## Collapsed Section
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

## Alerts
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

## Hiding Content
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

# CODE
## Inline Code
```markdown
This is `inline code` example.
```
This is `inline code` example.

<br/>

## Code Block
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

# LINK
## Text Link
```markdown
[Link Text](URL)
```
##### with title
```markdown
[Link Text](URL "Title")
```

### Example
```markdown
[Markdown Notes](https://github.com/abdullahdangac/Markdown-Notes "Markdown Notes")
```
[Markdown Notes](https://github.com/abdullahdangac/Markdown-Notes "Markdown Notes")

<br/>

## Images as Link
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

## Section Link

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

## Reference Link
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

# IMAGE
```markdown
![Alt Text](image-url.jpg "Image Title")
```

### Example
```markdown
![Markdown Mark](https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png)
```
![Markdown Mark](https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png)

<br/>

## Resizing Image
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

## Aligning Image
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

# TABLE
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

## Aligning Text in Table
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

## Side by Side Tables
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

## MATHEMATICAL EXPRESSION
### Inline Mathematical Expression
```markdown
$\sqrt{3x-1}+(1+x)^2$
```
$\sqrt{3x-1}+(1+x)^2$

<br/>

### Mathematical Expression Block
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

### Mathematical Symbols
#### Arithmetic
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

### Greek Alphabet
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
