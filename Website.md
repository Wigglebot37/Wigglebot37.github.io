# Website

## Sections
- [Quotes](#quotes)
- [Emphasis](#emphasis)
- [Lists](#lists)
- [Links and Images](#links-and-images)
- [Code](#code)
- [Tables](#tables)

---

## Quotes


Quotes are defined by the  '>' symbol 

> Regular Quote

> ## Header2 Quote 

---

## Emphasis

**Bold**
***Bold and Italic***
*Italic*
~~strikethrough~~

---

## Lists

- Item 1
- Item 2
    - Item 2.5
- Item 3

1. Item 234
2. Item 235
3. Item 236

---

## Links and Images

<http://www.github.com>

[Github Link](http://www.github.com)

[FavLink]: http://www.github.com/

[Github Link 2][FavLink]

<!--
Defining an image is similar to defining a link, except you prefix it with '!'
-->

![Ketchup Pic](https://img.thrivemarket.com/store/full/6/7/671635704498-1.jpg?w=1200) 

---

## Code

```javascript
var num = 0;
var num2 = 0;
```

`function()=true;`

```html 
<div>
    <p>This is an html example</p>
</div>
```

```html
    <style>
        body {
            color:red;
        }
    </style>
```

---

## Tables
Tables are useful for displaying rows and columns of data.  Column headers can be defined in between pipes (|).  Headers are separated from table content with a row of dashes (-) (still separated by pipes), and there must be at least 3 dashes between each header.  The row data follows beneath (still separated by pipes).

| Header 1    | Header 2    | Header 3    |
| ----------- | ----------- | ----------- |
| Row 1 Col 1 | Row 1 Col 2 | Row 1 Col 3 | 

| Header 1 | Header 2 |
| ----| ---|
|Loooooooooooooong item 1 | looooooooooong item 2 | 

| Header 1                | Header 2              |
| ----------------------- | --------------------- |
|Loooooooooooooong item 1 | looooooooooong item 2 |

| Header | Header 1 | Header 2  |
| ------ | :------: | --------: |
| Aligned Left | Aligned Center | Aligned Right |

---