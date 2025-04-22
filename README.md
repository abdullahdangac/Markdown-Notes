# Markdown Notes

## CONTENTS
[TEXT](#text)  
&emsp; [Header](#header)  
&emsp; [Styling Text](#styling-text)  
&emsp; [Quote Text](#quote-text)  
&emsp; [List Text](#list-text)  
[CODE](#code)  
&emsp; [Inline Code](#inline-code)  
&emsp; [Code Block](#code-block)  
[TABLE](#table)  
[LINK](#link)  
&emsp; [Text Link](#text-link)  
&emsp; [Image as Link](#images-as-link)  
&emsp; [Section Link](#section-link)  
[IMAGE](#image)  


<br />
<br />

---------------------------------------------------------

<br />
<br />

# TEXT
## Header
```
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

<br />
<br />

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

<br />
<br />

## Quote Text
```
> This is a quote.
```

> This is a quote.

<br />
<br />

## List Text
### Bullet List
```
- Element 1
- Element 2
  - Sub-element 1
    - Sub-element 1.a
```

- Element 1
- Element 2
  - Sub-element 1
    - Sub-element 1.a

<br />

### Ordered List
```
1. Element 1
2. Element 2
   1. Sub-element 1
      1. Sub-element 1.a
```

1. Element 1
2. Element 2
   1. Sub-element 1
      1. Sub-element 1.a

<br />

### To-do List
```
- [x] Completed
- [ ] Not completed
```

- [x] Completed
- [ ] Not completed

<br />
<br />

---------------------------------------------------------

<br />
<br />

# CODE
## Inline Code
```
`Inline code`
```
`Inline code`

<br />

## Code Block
````
```
Code Block
```
````

```
Code Block
```

<br />
<br />

---------------------------------------------------------

<br />
<br />

# TABLE
```
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

<br />

### Text Alignment
```
| Left-aligned | Center-aligned | Right-aligned |
|:-------------|:--------------:|--------------:|
| Text         | Text           | Text          |
```

| Left-aligned | Center-aligned | Right-aligned |
|:-------------|:--------------:|--------------:|
| Text         | Text           | Text          |

- `:--` means the column is left aligned.
- `--:` means the column is right aligned.
- `:-:` means the column is center aligned.

<br />
<br />

---------------------------------------------------------

<br />
<br />

# LINK
## Text Link
```
[Link Text](URL)
```

#### e.g.
```
[Markdown Notes](https://github.com/abdullahdangac/Markdown-Notes)
```
[Markdown Notes](https://github.com/abdullahdangac/Markdown-Notes)

<br />

## Images as Link
```
[![Image Alt Text](image-url.jpg)](hyperlink-url)
```

#### e.g.
##### with LinkedIn icon
```
[![LinkedIn](https://i.sstatic.net/gVE0j.png)](https://www.linkedin.com/in/abdullahdangac)
```

[![LinkedIn](https://i.sstatic.net/gVE0j.png)](https://www.linkedin.com/in/abdullahdangac)

<br />

##### with LinkedIn badge
```
[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Profile-informational?style=flat&logo=linkedin&logoColor=white&color=0D76A8)](https://www.linkedin.com/in/abdullahdangac/)
```

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-Profile-informational?style=flat&logo=linkedin&logoColor=white&color=0D76A8)](https://www.linkedin.com/in/abdullahdangac/)

<br />

## Section Link
```
# Sample Section

## Sample Subsection

Link to the Sample Section: [Link Text](#sample-section)  
Link to the Sample Subsection: [Link Text](#sample-subsection)


### Non-unique Section

### Non-unique Section

Link to the first Non-unique Section in this file: [Link Text](#non-unique-section-1)  
Link to the second Non-unique Section in this file: [Link Text](#non-unique-section-2)


# This'll be a _Helpful_ Section About the Greek Letter Θ!
A heading containing characters not allowed in fragments, UTF-8 characters, two consecutive spaces
between the first and second words, and formatting.

Link to the helpful section: [Link Text](#thisll-be-a-helpful-section-about-the-greek-letter-Θ).
```
<br />
<br />

---------------------------------------------------------

<br />
<br />

# IMAGE
```
![Alt Text](image-url.jpg "Image Title")
```

#### e.g.
```
![Markdown Mark](https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png)
```
![Markdown Mark](https://github.com/dcurtis/markdown-mark/blob/master/png/208x128.png)
