---
layout: post
title:  "css"
categories: coding
---
[Reference](https://www.w3schools.com/cssref/default.asp "CSS reference")

selector  |  example  |  example description
---  |  ---  |  ---
.class  |  .intro  |  Selects all elements with class="intro"
#id  |  # firstname  |  Selects the element with id="firstname"
*  |  *  |  Selects all elements
*element*  |  p  |  Selects all <p> elements
*element, element*  |  div, p  |  Selects all <div> elements and all <p> elements

## external css
``` html
<head>
<link rel = "stylesheet" type = "text/css" href = "/wjekyll/assets/style.css">
</head>
```
## internal css
``` html
<head>
  <style>
	body {
	  background-color: linen;
	}
	
	h1 {
	  color: maroon;
	  margin-left: 40px;
	}
  </style>
</head>
```
## inline css
``` html
<body>
  <h1 style="color:blue;text-align:center;">This is a heading</h1>
  <p style="color:red;">This is a paragraph.</p>
</body>
```
**comments:** `/* This is a single-line comment */`

***

### colors
background-color:DodgerBlue;  
color:Tomato;  
border:2px solid Tomato;
``` html
<h1 style="background-color:rgb(255, 99, 71);">...</h1>
<h1 style="background-color:#ff6347;">...</h1>
<h1 style="background-color:hsl(9, 100%, 64%);">...</h1>
<h1 style="background-color:rgba(255, 99, 71, 0.5);">...</h1>
<h1 style="background-color:hsla(9, 100%, 64%, 0.5);">...</h1>
```
### background
[reference](https://www.w3schools.com/css/css_background_shorthand.asp "background reference")  
opacity: 0.3  
background-image: url("paper.gif");  
background-repeat: repeat; |  repeat-x;  |  repeat-y;  |  no-repeat;  
background-position: right top;
background-attachment: fixed; | scroll;
background-size: 75% 50%;  
shorthand:
``` css
body {
  background: #ffffff url("img_tree.png") no-repeat right top;
}
```
### border
border-style: solid;  
border-radius: 5px;  
border-width: thick;  
border-color: red;  
shorthand:  border: 5px solid red;  

### margins
margin-top: 100px;  
margin-bottom: 100px;  
margin-right: 150px;  
margin-left: 80px;  
shorthand: margin: 25px 50px 75px 100px;  

### paddings
*espacio dentro de los bordes*  
padding-top: 50px;  
padding-right: 30px;  
padding-bottom: 50px;  
padding-left: 80px;  
padding: 25px 50px 75px 100px;  

### height/width
*width and height of the content area*  
height: 200px;  
width: 50%;  

![box model](/wjekyll/assets/images/box-model.png)




