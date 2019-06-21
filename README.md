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
**`Text`**
- text-align: center | left | right | *justify* ( căn lề `alignment` ) 
- text-decoration: none | underline | *overline* | *line-through*
- text-transform: uppercase | lowercsae | capitalize
- text-indent: 11px ( khoảng cách thụt lề )
- letter-spacing: 5px ( khoảng cách giữa các chữ cái )
- word-spacing: 5px ( khoảng cách giữa các từ )
- line-height: 1.2 ( khoảng cách giữa các dòng)
- text-shadow: x y color ( đổ bóng text )
- font-family: sans-serif
[Explore more](https://adam-marsden.co.uk/css-cheat-sheet)

**`Font`**
- font-family: font1 | font2 | font3 ( test từng font 1 -> 3 )
- font-style: normal | intalic | bold
- font-size: 20px ( default 16px )
- font-weight: normal | bold | 400 | 600 | 700 | 900
- Insert font Google:

		<link href="https://fonts.googleapis.com/css?family=Roboto&display=swap" rel="stylesheet">
		
 	Use the following CSS rules to specify these families:
		 
		font-family: 'Roboto', sans-serif;
		
 	[Font Google](https://fonts.google.com/)
- Custom font:

		@font-face{
			font-family: myFristFont;
			src: url(path/fontname.tff)
		}
 	Use the following CSS rules to specify these families:

		font-family: myFristFont;


