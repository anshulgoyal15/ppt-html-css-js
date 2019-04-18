# Html
Html stands for Hyper text markup language.Html provides structure to our website.

## Content
- HTML tag
- HEAD tag
- BODY tag
- DIV tag
- SPAN tag
- TABLE,TBODY,THEAD,TR,TD tag
- FORM,RADIO,CHECKBOX,INPUT,SELECT tag
- H{1,6} tags
- P tag
- IMG tag
- A tag
- B tag,I tag, BR tag
- List tags
- Arrtibutes

---

# HTML tag
It is used to indicated the start and end of the html document.Every tag is used within html.

---

# HEAD tag
Everything not visible but available is in the head tag. Tags like `title`, `link`, `meta` are mostly placed in the head.

```html

<head>
<title>
My first Page.
</title>
</head>

```
---

# BODY tag
Everything visible is placed in this tag. Body tag enclose many tags including `a`,`img` etc.

---

# DIV tag
It is used to club few elments together and seperate it from other elements on the page. It is block element it takes its own space and other content is on other line.

```html
<div>
<h1>Heading</h1>
<p>
 Hello!
</p>
</div>

```
---

# SPAN tag
It is used to apply property with out adding new line to the content.

```html

<p>
Hi i am the text <span>with span</span>

</p>

```
---

# TABLE tag
Table are very useful means of displaying organised data. Days before flexbox the tables were the only means of the layout in EI9.

## Table has the following tags
1. Thead- the head or the top of the table.
 - th is used of the data in the header.
2. Tbody- the rest od the table.
 - td is used for data in body.
3. Tr- the row of the table.

```html
<table>
<thead>
 <tr><th>name</th><th>class</th></tr>
</thead>

<tbody>
 <tr><td>Anshul Goyal</td><td>CE 2nd Year</td></tr>
</tbody>
</table>

``` 
---
# FORM tag
Form tag is used to submit data to server and other services. We can use it to take input from the user.

## Type of inputs
- Text Field
- Radio button
- checkbox
- select

```html
<form>
<label>Name</label>
<input type="text" >
<label>Radio</label>
<input type="radio">
<label>Checkbox</label>
<input type="checkbox">
<input type="submit">
</form>
```

---

# HEADING tags
These tags are used to create text heading in the document.

## Heading tags
1. h1
2. h2
3. h3
4. h4
5. h5
6. h6

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6<h6>
```
---

# P tags
This tag is used create a paragraph.

```html
<p>Hi my name is p tags</p>
```
---

# IMG tag
This tag is used to display image in the document. The image can be used in any supported format including _jpeg_,_gif_,_png_ etc.

```html
<img src="https://ewedit.files.wordpress.com/2018/06/000223043hr.jpg">

```
---

# A tag
This tag is ued to create link between different pages in html.

```html

<a href="www.google.com">Google</a>
```
---

# B, I, BR tags
These tags are used to create html **bold** _italic_ and line break in th html.
---

# LIST tags
List are very vital component of any document

## Type of list
- ordered list 
- unordered list
---

### orded list 
The `ol` tag is used.
```html
<ol>
<li>order list item</li>
</ol>

``` 
---
### undorder list
The `ul` tag is used.
```html
<ul>
<li>unordered list</li>
</ul>
```
---

# .center[Thank You]

