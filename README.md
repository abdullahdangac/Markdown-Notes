# Markdown Notes

## CONTENTS
[TEXT](#text)  
&emsp; [Header](#header)  
&emsp; [Styling Text](#styling-text)  
&emsp; [Aligning Text](#aligning-text)  
&emsp; [List Text](#list-text)  
&emsp; [Quote Text](#quote-text)  
&emsp; [Collapsed Section](#collapsed-section)  
&emsp; [Alerts](#alerts)  
&emsp; [Hiding Content](#hiding-content)  

[CODE](#code)  
&emsp; [Inline Code](#inline-code)  
&emsp; [Code Block](#code-block)  

[LINK](#link)  
&emsp; [Text Link](#text-link)  
&emsp; [Image as Link](#images-as-link)  
&emsp; [Section Link](#section-link)  
&emsp; [Reference Link](#reference-link)  

[IMAGE](#image)  
&emsp; [Resizing Image](#resizing-image)  
&emsp; [Aligning Image](#aligning-image)  

[TABLE](#table)  
&emsp; [Aligning Text in Table](#aligning-text-in-table)  
&emsp; [Side by Side Tables](#side-by-side-tables)  

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

## Space in Text
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

## Line Break in Text
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

[Some Markdown Badges](https://ileriayo.github.io/markdown-badges/)

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
[CMake] is an open source, cross-platform family of tools designed to build, test, and package software.  
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
| 1x1 | 1x2 | 1x3 |
|--|--|--|
| 2x1 | 2x2 | 2x3 |
| 3x1 | 3x2 | 3x3 |
| 4x1 | 4x2 | 4x3 |
```
| 1x1 | 1x2 | 1x3 |
|--|--|--|
| 2x1 | 2x2 | 2x3 |
| 3x1 | 3x2 | 3x3 |
| 4x1 | 4x2 | 4x3 |

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
