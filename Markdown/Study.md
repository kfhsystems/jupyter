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


### Monospace Font
Surround text with a grave accent (also called a back single quotation mark):
`string`

### Line breaks
Sometimes markdown doesn’t make line breaks when you want them. To force a linebreak, use the following code: <br> This line should start in next line.

### Horizontal Line
Use three asterisks (***) on the new line.

### Indenting (or Quote)
Use the greater than sign (>) followed by a space, for example:
> Text that will be indented when the Markdown is rendered.
Any subsequent text is indented until the next carriage return. 

No indenting again.

### Notes

Using the MyST extension will not work here because of the "*.md" extension:
```{note}
Most Python programmers follow the snake_case naming convention, which involves using underscores (_) to separate multiple words. However, the recommended naming convention for Python classes is the PascalCase, where each word is capitalized.
```

    
### Bullets
To create a circular bullet point, use one of the following methods. Each bullet point must be on its own line.
- A hyphen (-) followed by one or two spaces, for example: - Bulleted item
- A space, a hyphen (-) and a space, for example: - Bulleted item
- An asterisk (*) followed by one or two spaces, for example: * Bulleted item 
<br><br> To create a sub bullet, press Tab before entering the bullet point using one of the methods described above. <br> **For example:**

- __Main bullet point__
     - **Sub bullet point**
     - **Sub bullet point2**
    
### Tables
To add a table in Markdown, use the vertical line | to separate each column, and use three or more dahses --- to create each column’s header. A vertical line should also be added at either end of the row.
| Month    | Savings |
|----------|---------|
| January  | 250     |
| February | 80      |
| March    | 420     |

#### Text Alignment in the Tables:
Align text in the columns to the left, right, or center by adding a colon **:** to the left, right, or on both side of the dashes **---** within the header row.
| Item              | In Stock | Price |
| :---------------- | :------: | ----: |
| Python Hat        |   True   | 23.99 |
| SQL Hat           |   True   | 23.99 |
| Codecademy Tee    |  False   | 19.99 |
| Codecademy Hoodie |  False   | 42.99 |

- **:----** means the column is left aligned.
- **----:** means the column is right aligned.
- **:---:** means the column is center aligned.

### Web Link
This is the true news [TrueNews](<https://www.trunews.com>). \
You can also visit at <https://www.trunews.com>


