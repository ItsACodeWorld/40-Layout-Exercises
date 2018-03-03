# 40-Layout-Exercises

## Intro:

This layout exercise is created by [@byr-gdp](https://github.com/byr-gdp/40LayoutExercise) , this is an English vrsion translated by me.

All exercises based on the following HTML structure (do not change the HTML structure, or it will lose the meaning of practice), all you need to do is to add css code in *layout* area to change the layout of the page. 


HTML:
```html
<div id="container">
	<div id="header">Header</div>
	<div id="wrapper">
		<div id="content">Content</div>
	</div>
	<div id="navigation">Navigation</div>
	<div id="extra">Extra stuff</div>
	<div id="footer">Footer</div>
</div>
```

CSS:
```css
/*basic style*/
#container { 
    font-size: 12px; 
    font-family: arial, sans-serif;
}
p { 
    margin: 0 10px 10px;
}
#header {
    height: 80px; 
    background-color: rgb(238,238,238); 
    color: rgb(122,177,36); 
    padding-left: 10px; 
    line-height: 80px; }
#header h1 {
    margin: 0;
}
#navigation {
    background-color: rgb(186,203,253);
}
#extra {
    background-color: rgb(253,133,67);
}
#footer {
    height: 14px;  
    padding:5px 10px 5px 10px; 
    color: #FFF; 
    background-color: #333;
}
#footer p {
    line-height: 14px; 
    margin: 0px;
}

/* layout */

```

## Exercises

### 1.Three percentage columns(n.1)

There are three elements: *wrapper*, *navigation* and *extra*

Guide:

Set the width of *wrapper* to 50% and horizontally center the *wrapper* element.
Set width of *navigation* and *extra* to 25%, *navigation* on the left side of *wrapper*, *extra* on the right.

Example:

![image](https://camo.githubusercontent.com/d0f13a8302f280ce4eae9216a4be2969e9271334/68747470733a2f2f6f6f6f2e306f302e6f6f6f2f323031352f30382f31342f353563643962633731633436352e706e67)



