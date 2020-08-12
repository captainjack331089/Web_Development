# CSS

Cascading Sytle Sheets

a skin of the web structure



---

 ***The General Rule:***

```selector {property: value; anotherProperty: value;}```

*We want to seperate HTML from CSS*

---

- Using the <link> Tag(put in the head) to connect HTML file and CSS file

  eg.

  ```<link rel="stylesheet" type="text/css" href="app.css">```

---



- Colors

  - name: 

    eg. color: red

    You can find all the colors can be used in CSS [here](https://colours.neilorangepeel.com/).(147 colors)

  - hexadecimal: # + String of 6 hexadecimal numbers (from 0-F)

    eg. color: #FFFFFF;

    You can find the color hex based on your choice [here](https://www.webfx.com/web-design/color-picker/)

  - RGB: 3 channels: Red, Green, and Blue, Each ranges from 0-255.

    eg. color: rgb(255,255,255);

  - RGBA: like RGB, with an alpha (transparency)channel, ranges from 0.0-1.0

    eg. color: rgba(11,99,23, .8);

---



- Background

  - background: rgb(255,100,100);

  - background: url(https://.....);
  - background-repeat, background-size, etc to filter the background.

---



-  Border
  - border-color
  - border-width
  - border-sytle

---



- ID Selector

  - id="" set at html and use the id name at css file(#)

    Note: id only occurs one time in html file.

---



- Class Selector

  

  Select all elements with a given class (.)

  You can find a lot useful css selectors [here](https://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048).



Here are some selector samples:

```css

li {

}

/*class*/
.hello {

}

/*id*/
#name {

}
/*Star*/
/*will style all elements, but not very often use*/
* {
	border: 1px solid lightgrey;
}

/*Descendant Selector*/
/*every anchor inside li take effect*/
li a {
	color: red;
}

/*Adjacent Selector*/
/*select element that come after an element*/

h4 + ul {
	border: 4px solid red;
}

/*Attribute Selector*/
/*a way to select element based on any attribute*/
a[href="https://www.google.com"] {
	background: blue;
}

input[type="text"] {
	background: green;
}

/*nth of type*/
/*takes a number, select every nth every specif elements*/

ul:nth-of-type(3) {
	background: purple;
}

li:nth-of-type(3) {
	background: red;
}
```



---

- Specificity

  Whatever style is closest to the element, that one will win out.

  

  For the specificity calculator reference, check [here](https://specificity.keegan.st/)

---

- Fonts 

You can find all Fonts reference [here](https://www.cssfontstack.com/)

Following are some common fonts set code:

```css

p {
	font-family: Arial;
}

h1 {
	font-family: Geneva;
}

/*font-size*/
body {
	font-size: 10px;
}
/*em is dynamic compare with others*/

h1 {
	font-size: 5.0em;
}

p {
	font-size: 2.0em;
}

span {
	font-size: 2.0em;  }

/*font-weight*/
/*how thick the lines/p are*/
p {
	font-weight: bold;
	/*font-weight: normal;*/
	/*font-weight: 100-800;*/
}

/*line-height	*/
/*space between lines*/
p {
	line-height: 2;
}

/*text-align*/
/*control how the text givien to the left or center or right*/
h1 {
	text-align: right;
}

p {
	text-align: center;
}

/*text-decoration*/
/*text-decoration is used to give text underline effect or line through or etc*/
p {
	text-decoration: underline;
}

h1 {
	text-decoration: line-through;
}
```



***Google Fonts:***

When using google fonts.

- Link google fonts url in html file.

```html
<html>
<head>
	<title>Fonts</title>
	<link rel="stylesheet" type="text/css" href="font.css">
	<link href="https://fonts.googleapis.com/css2?family=Recursive:wght@500&display=swap" rel="stylesheet">
</head>
<body>

<h1>Fonts Demo Page</h1>

<p>yeezy</p>

<p>jordan</p>
</body>
</html>
```

- add font family from google font to css file

```css

p {
	font-family: 'Recursive';
}
```



---



-  ***Box Model***

  - ***Content***

    

  - ***Padding***

    Between border and content, called padding.

    

  - ***Border***

  

  - ***Margin***

    Between the border and outside, called Margin.

  