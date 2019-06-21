
# **Intro**

> Start 21/06/2019
 - This is my code HTML with CSS
 - Learnt from [Coders.tokyo](https://coders.tokyo/)
 - Learn **more** and **more** !
# **3 ways add CSS**
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
- text-shadow: x y color ( đổ bóng text )
- font-family: sans-serif<br>
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
- Shorthand
	- padding: 10px 20px 30px; /*top left-right bottom*/
	- padding: 10px 20px; /*top-bottom left-right*/
	- padding: 10px; /*all*/

### **`Margin`**
- margin-bottom: 16px;
- margin-right: 16px;
- margin-left: 20px;
- margin-top: 20px;
- Shorthand:
	- margin: 10px 20px 30px; /*top left-right bottom*/
	- margin: 10px 20px; /*top-bottom left-right*/
	- margin: 10px; /*all*/

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
- border-radius
