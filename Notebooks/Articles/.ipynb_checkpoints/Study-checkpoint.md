#  KFH: Markdown Notices
## IBM Markdown for A Junyper Notebook
***
### Headings
Use the number sign (#) followed by a blank space for notebook titles and section headings:
- # for titles
- ## for major headings
- ### for subheadings
- #### for 4th level subheadings

### Emphasis
Use the following code to emphasize text:
- Bold text: __string__ or **string**
- Italic text: _string_ or *string*

### Mathematical Formula
Surround mathematical symbols with a dollar sign.
#### Inline Formula:
This is an example of an
inline equation $z=\sqrt{x^2+y^2}$.
#### Math blocks:
This is an example of a
math block

$$
z=\sqrt{x^2+y^2}
$$
#### Math blocks with labels:
This is an example of a
math block with a label

$$
z=\sqrt{x^2+y^2}
$$(eq.1)
#### Math directives
This is an example of a
math directive with a
label
```{math}
:label: eq-label

z=\sqrt{x^2+y^2}
```

### Monospace Font
Surround text with a grave accent (also called a back single quotation mark):
`string`

### Line breaks
Sometimes markdown doesn’t make line breaks when you want them. To force a linebreak, use the following code: <br> This line should start in next line.

### Horizontal Line
Use three asterisks (***) on the new line.

### Indenting
Use the greater than sign (>) followed by a space, for example:
> Text that will be indented when the Markdown is rendered.
Any subsequent text is indented until the next carriage return. 


```{Note}
Most Python programmers follow the snake_case naming convention, which involves using underscores (_) to separate multiple words. However, the recommended naming convention for Python classes is the PascalCase, where each word is capitalized.
```

No indenting again.
    
### Bullets
To create a circular bullet point, use one of the following methods. Each bullet point must be on its own line.
- A hyphen (-) followed by one or two spaces, for example: - Bulleted item
- A space, a hyphen (-) and a space, for example: - Bulleted item
- An asterisk (*) followed by one or two spaces, for example: * Bulleted item 
<br><br> To create a sub bullet, press Tab before entering the bullet point using one of the methods described above. <br> **For example:**

- __Main bullet point__
     - **Sub bullet point**
     - **Sub bullet point2**
    


