# Lesson 05 - Design Web Pages with CSS

![CSS info](https://media.licdn.com/dms/image/D4D12AQF7lMBGIwHUCw/article-inline_image-shrink_1000_1488/0/1680955326122?e=1701907200&v=beta&t=WhqPzkc3vaJjef17fVfdZLkraHP7x1D73v5rBG-MH4o)
*Image from Media.Licdn.Com*

## What's the Purpose of CSS?

Cascading Style Sheet, or *(CSS)* is what is used in conjunction with HTML to create the visual component of a web page. With CSS, you are now able to determine things like

1. Color
2. Font size
3. Font style
4. Text Position
5. Icons
6. Tables
7. Lists
8. Backgrounds
9. Borders
10. Margins and Padding

## Adding CSS 

CSS can be added in three ways: **Internal Style Sheet**, an **External Style Sheet**, and using **Inline CSS**.

### Internal Style Sheet
With this method, you can add styling to one unique web page. The defining styles are indicated within the < style > element in the < head > section of HTML document.

### External Style Sheet

Using an external style sheet means that a separate css file is created, and all of the styling of a website is drawn from this one file. The HTML page needs to have a way to reference the style sheet, which is found in the head of the document.

#### Example
< head >
< link rel="stylesheet" href="mycoolstyle.css" >
< /head >

### Inline Style Sheet
Allows you to create style for a single element, directly in the HTML document. This is great if you want different styles for various types of elements. Let's say you have 10 h3 elements
on your webpage. For every other h3 element, you want it to be a shade of blue. This can be done by doing an inline style sheet.

#### Example
< h3 style="color:light blue;text-align:right;">This is a kind of cool< /h1 >

## Paint the Town Red

Now that we know the various ways to add style to HTML, let's put it into action. Let's say that we want all < p > *paragraph* elements to display as red text. This would best be written on an ***external style sheet***, so that the rule
can apply to the entire website, without worrying about missing any. To do this, we would need to write the following:

p {  <--Identify the element

  color: red;  <---- Declare the property and value
  
}  <--- Complete the syntax
