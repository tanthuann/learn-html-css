
# **Intro**

> Start 21/06/2019
 - This is my code HTML with CSS
 - Learnt from [Coders.tokyo](https://coders.tokyo/)
 - Learn **more** and **more** !
# **Add CSS**
- inline CSS
- internal CSS ( in tag style)
- include external CSS ( link  to filename.css )
# **Keyword** 
### **`Text`**
- text-align: center | left | right | *justify* ( căn lề `alignment` ) 
- text-decoration: none | underline | *overline* | *line-through*
- text-transform: uppercase | lowercsae | capitalize
- text-indent: 11px ( khoảng cách thụt lề )
- letter-spacing: 5px ( khoảng cách giữa các chữ cái )
- word-spacing: 5px ( khoảng cách giữa các từ )
- line-height: 1.2 ( khoảng cách giữa các dòng)
- text-shadow: x y color ( đổ bóng text )<br>
 	[Explore more](https://adam-marsden.co.uk/css-cheat-sheet)

### **`Font`**
- font-family: font1 | font2 | font3 ( test từng font 1 -> 3 )
- font-style: normal | intalic | bold
- font-size: 20px ( default 16px )
- font-weight: normal | bold | 400 | 600 | 700 | 900
- Insert font Google: <br>
	```html
	<link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
	```
	
 	Use the following CSS rules to specify these families:
 	```css
 	font-family: 'Roboto', sans-serif;
  ```
		
 	[Font Google](https://fonts.google.com/)
- Custom font:
	```css
	@font-face{
		font-family: myFristFont;
		src: url(path/fontname.tff)
	}
	```
 	Use the following CSS rules to specify these familie
	```css
	font-family: myFristFont;
	```

### **`Padding`**
- padding-bottom: 16px;
- padding-right: 16px;
- padding-left: 20px;
- padding-top: 20px;
	```css
	padding: 10px 20px 30px; /*top left-right bottom*/
	padding: 10px 20px; /*top-bottom left-right*/
	padding: 10px; /*all*/
	```

### **`Margin`**
- margin-bottom: 16px;
- margin-right: 16px;
- margin-left: 20px;
- margin-top: 20px;
	```css
	margin: 10px 20px 30px; /*top left-right bottom*/
	margin: 10px 20px; /*top-bottom left-right*/
	margin: 10px; /*all*/
	```

### **`Border`**
- border-width: 1px;
- border-style: solid;
- border-color: #629D6B;
	```css
	border: 1px solid #629D6B; /*width style color*/
	```
	and
	```css
	border-width: 10px 20px 30px; /*top left-right bottom*/
	border-width: 10px 20px; /*top-bottom left-right*/
	border-width: 5px; /*all*/
	```
- border-direction-color: #BD8576;
- border-direction-style: dotted;
- border-direction-width: 1px
	>##### *Direction: top | right | bottom | left*
- border-radius: 4px;

### **`Background`**
- background-color: *color*
- background-color: transparent;
- background-color: *gradient*
	Example gradient:
	```css
    background: rgb(2,0,36);
    background: linear-gradient(90deg, rgba(2,0,36,1) 0%, rgba(175,0,255,0.3225665266106442) 100%);
	```
	Tool online: [cssgradient.io](https://cssgradient.io/)
	>Or google with keyword: ***background gradient generator***
- background-image: url(*path*);
- background-size: cover | % | contain | *auto* | ...
- backgroud-repeat: repeat-x | repeat-y | *repeat* ( both x and y )
- background-position: x y | center;
- background-attachment: fixed | *scroll*<br>
	[Example CSS](Ep11%20BackgroundImage)

### **`Table`**
- Combination border of ```<table>```, ```<th>```, ```<td>``` .
- Gross border của element table:
	```css
		border-collapse: collapse;
	```
- Set width, height of ```<table>```
- vertical-align: top | middle | bottom (set element location)
- text-align and vertical-align combination.
- caption-side: top | bottom | ... (the placement of a table caption)

### **`Icon`**
- Use icon online: [fontawesome.com](https://fontawesome.com/)
	>Can explore more animation.
- Add script in **head** tag:
	
	```css
		<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.7.0/css/all.css" integrity="sha384-lZN37f5QGtY3VHgisS14W3ExzMWZxybE1SJSEsQp9S+oqd12jhcu+A56Ebc1zFSJ" crossorigin="anonymous">
		or
		<script src="https://kit.fontawesome.com/7c6793a68c.js"></script>
	```

### **`Status`**
- Link: not click link
- Visited: clicked
- Hover: point to
- Active: clicked but not release
- focus: clicked input.
	```css
	a:link {}
	```

### **`Display`**
- display: block | none | inline | inline-block (none not affect the layout)
	>inline-block, block: can set width, height, ....
- visibility: hidden ( The element will be hidden, but still affect the layout )

### **`Position`**
- static: default.
- relative : localtion set. (left bottom top right)
	```css
	div.relative {
	  position: relative;
	  left: 30px;
	  border: 3px solid #73AD21;
	}
	```
- fixed: localtion set and fixed it despite be scrolling.
- absolute: position with tag nearest
- sticky: display at position write html and define position fixed despite be scrolling.
- z-index: -1; ( display element in front of or behind )

### **`Overflow`**
- visible: default, overflow is not cut, content renders out side.
- hidden: overflow is cut, not render.
- scroll: overflow is cut, add a srcollbar to see content rest.
- auto: same srcoll but it adds scrollbars only when necessary
	```css
	overflow: hidden;
	```

### **`Combinators`**
- Descendant selector ( space ) 
- Child selector ( > )
- Adjacent sibling selector ( + )
- General sibling  selector ( ~ )

### **`Flex`**
- display: flex;
- flex-direction: column | row 
- justify-content: **flex-start** | flex-end | space-between | space-around | space-evenly | center
- align-items: **stretch** | flex-start | flex-end | baseline | center
	>Define align-items perpendicular to flex-direction
- flex-basis: 100px; ( width box )
- flex-grow: 1 ( 1 / 3) ( divide the rest into many section )
- flex-shrink: **1** (  subtract the overflow to section in tag  )
- order: **0** | 1 | 2 | ... ( Numerical order )