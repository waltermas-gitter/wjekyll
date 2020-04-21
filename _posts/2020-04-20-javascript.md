---
layout: post
title:  "javascript"
categories: coding
---
[Reference](https://www.w3schools.com/jsref/default.asp "javascript reference")  
document.getElementById('demo').innerHTML = 'Hello JavaScript';  
document.getElementById("demo").style.fontSize = "35px";  
document.getElementById("demo").style.display = "none";  
document.getElementById("demo").style.display = "block";  

scripts in:
* head
* body
* external file `<script src="myScript1.js"></script>`  

basic template:  
``` html
<!DOCTYPE html>
<html>
<body>

<h1>A Web Page</h1>
<p id="demo">A Paragraph</p>
<button type="button" onclick="myFunction()">Try it</button>

<script>
function myFunction() {
 document.getElementById("demo").innerHTML = "Paragraph changed.";
}
</script>

</body>
</html>
```

## output
document.getElementById("demo").innerHTML = 5 + 6;  
document.write(5 + 6);  
`<button type="button" onclick="document.write(5 + 6)">Try it</button>`  
window.alert(5 + 6);  
console.log(5 + 6);  

## syntax
``` JavaScript
var x, y, z;       // How to declare variables
/*
multi line
comments
*/
```

## events
[reference](https://www.w3schools.com/jsref/dom_obj_event.asp "events reference")  
* onchange
* onclick
* onmouseover
* onmouseout
* onkeydown
* onload
