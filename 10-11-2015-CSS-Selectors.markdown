---
Layout: default
Title: CSS Selectors
Cover: false
Author: Ali Khakwani
---

<!DOCTYPE html>
<html>
<body>
<p> CSS selectors are basically CSS rules that selects the HTML elements you want to style. After selecting you can apply any type of styles like text-color and background on those HTML elements. Let us look at different CSS selectors available.</p>

<p> To apply CSS style on all HTML elements you need to write </p>
<code>
* { 
color: green;
font-size: 20px;
line-height: 25px;
}
</code>

<p> That style will be applied on all HTML elements in a page. To apply CSS style on all elements with same tag name you need to write 
</p>

<code>
p {
color: green;
font-size: 20px;
line-height: 25px;
}
</code>
<p> Here "P" is tag name </p>

<p> In that code "P" is tag name, it can be any other tag name. Using that type of CSS selection you can apply CSS style on all DIV tags, Table tags, or any other HTML tag.</p>
<h1> Now, how to Select HTML element using its attribute name </h1>
<p> Mostly we used to select "Input" tags with their attribute name. </p>

<code>
input[type='text'] {
   	color: green;
font-size: 20px;
line-height: 25px;
}
</code>
<p> In that code we are selecting input tags which have attribute named "text" and attribute value is "text". To select input tags with type submit we need to write
</p>

<code>
input[type='submit'] { 
color: green;
font-size: 20px;
line-height: 25px;
}
</code>

<h1> ID and Class Selectors </h1>
<p> 
What are ID's and Classes. ID is HTML tag attribute, its like identity of HTML tag in whole page and main thing is it should be unique. Class is an HTML tag attribute, and more then one tag class can be same. Example of ID is like </p>
<code>
<div id="container"></div>
</code>
<p> An example of class is like </p>
<code>
<div class="box"></div>
</code>
<p> To assign CSS style to class "box" </p>
<code>
.box {
   	padding: 20px;
 	margin: 10px;
	width: 240px;
	}
</code>
<p> and To assign CSS style to id "container" </p>
<code> 
#container {
   	padding: 20px;
   	margin: 10px;
   	width: 240px;
	}
</code>
<p> If you want to apply CSS to a class or tag or id inside a class or id, then CSS gives you a solution for that. Consider HTML is like </p>
<code>
#container .box-2 {
	color: #000;
	font-size: 10px;
	background: url(any-image.png);
	}
</code>
<h1> Adjacent Siblings Combinator </h1>
<p> A selector that uses the adjacent sibling combinator uses the plus symbol (+), and is almost the same as the general sibling selector. The difference is that the targeted element must be an immediate sibling, not just a general sibling. For that  CSS code should be like: 
</p>
<code>
p + p {
   font-size: 1.5em;
   margin-bottom: 0px;
}
</code>
<h1> Apply CSS effects on mouse hover, active, focus and visited </h1>

<p> Too apply CSS effect on mouse hover CSS should be like </p>
<code> 
a:hover {
	color: red;
	}
	</code>
<p> For active CSS should be like </p>
<code> a:active {
	color: red;
	}
</code>
<p> For visited CSS should be like </p>
<code>
a:visited {
	color: red;
	}
</code>
<p> For focus CSS should be like </p>
<code>
a:focus {
	color: red;
	}
</code>
<p> Now the question I have in mind, can we use these CSS selectors in jQuery? </p>













