__C__~~S~~_S_
---
Internal css

`<p style="color:green; font-size:20px;"> Hello World!</p>`

### Preview
<p style="color:green; font-size:20px;"> Hello World!</p>

### multiple changes

```html
<head>
    <title></title>
    <style type="text/css">
        h1{
            color:green;
            font-size:20%;
        }
        p{
            color:blue;
            font-size:25%;
        }
    </style>
</head>
```

create a html file. example file.html

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8">
		<title>External CSS</title>
		<link rel="stylesheet" type="text/css" href="externalcss.css">
	</head>
		<body>
			<h1> External CSS Tutorial </h1>
			
			<p> 
				Bangladesh, nestled in South Asia, is a land of vibrant culture, rich history, and resilient people. With its lush green landscapes, intricate waterways, and bustling cities, Bangladesh offers a tapestry of experiences to visitors and inhabitants alike.</p>
			
			<p> Despite facing challenges such as frequent natural disasters and socio-economic disparities, the nation displays remarkable resilience and determination. Dhaka, the capital city, pulsates with energy, reflecting the country's dynamic spirit.</p> 
			
			<p> Bangladesh is renowned for its mouthwatering cuisine, from spicy curries to delectable sweets, tantalizing taste buds across the globe. Its cultural heritage, spanning from the ancient ruins of Paharpur to the ornate mosques of Bagerhat, speaks volumes about its diverse past. Moreover, Bangladesh has made significant strides in sectors like textiles, agriculture, and technology, contributing to its growing economy. As it continues to evolve, Bangladesh stands as a testament to the strength of its people and the richness of its heritage.</p>
		</body>
</html>
```

create a css file. example file.css

```css
h1{
text-align:center;
color:lightblue;
}
p{
	text-align:left;
	color:lightgreen;
}
```  
<img src="./images/external.png"/>

### one style use where it's required "class & id"

`"." use as class`
`"#" use as id`

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="UTF-8">
		<title> style use multiple</title>
		<style type="text/css">
			.style-1{
				color:lightblue;
				font-size:75%;
			}
			#paragraph-style1{
				color:green;
			}
		</style>
	</head>
	<body>
		<h1 class="style-1"> This is a tutorial page</h1>
		<h2 class="pargraph-style1"> Read Carefully </h2>

		<p class="style-1"> Bangladesh is renowned for its mouthwatering cuisine, from spicy curries to delectable sweets, tantalizing taste buds across the globe. </p>
		
		<p id="paragraph-style1">Its cultural heritage, spanning from the ancient ruins of Paharpur to the ornate mosques of Bagerhat, speaks volumes about its diverse past. Moreover, Bangladesh has made significant strides in sectors like textiles, agriculture, and technology, contributing to its growing economy.</p>
		
		<p id="paragraph-style1"> As it continues to evolve, Bangladesh stands as a testament to the strength of its people and the richness of its heritage.</p>
	</body>
</html>
```

```html
<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8">
		<title>explaination of class and id</title>

		<style type="text/css">
			#section1{
			background-color:lightblue;
			}
			#section1 h1{
			color:green;
			}
			#section1 p{
			color:lightpink;
			}
			.style1{
			color:blue;
			}
			.style2{
			font-size:70;
			}
		</style>
		</head>
		<body>
			<div id="section1">
				<h1> heading </h1>
				<p> this is inside headin paragraph</p>
			</div>			
			</br>
			<div class="style1 style2">
				<h1> heading </h1>
				<p> this is inside headin paragraph</p>
			</div>
		</body>
</html>
```
<img src="./images/explainclassid.png"/>
