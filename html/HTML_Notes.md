

# HTML

​													Find all references about HTML [here](https://www.runoob.com/markdown/md-link.html)

---

**The General Rule**:

<tagName> Some Contents </tagName>

---

**The basic HTML format **

```<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>

</body>
</html>
```



---

**Comments**

``` <!-- these are the comments -->```

---



## Tags:



**h1, h2, h3,...,h6 tag**

These elements are called block level elements.

---



**p Tag**

Elements are blockline element



- add **b Tag/ strong Tag** inside paragraph will **stronger** the contents 
- Add ***i/em Tag*** inside paragraph will ***italic*** the contents

---



**order list / unordered list**

```<ol>
		<li>Red</li>
		<li>Orange</li>
		<li>yellow</li>
	</ol>

	<ul>
		<li><strong>Red</strong></li>
		<li>Orange</li>
		<li>yellow</li>
	</ul>
```

---



**div**

- a generic container

- a block level element(takes a new line)

---



**span**

- a generic container
- not going do generate a new line

---



## Attributes:

**img**

insert image with src="..."

*eg*:

```<img src="http://www.ghi888.com/wp-content/uploads/2020/02/8-%E6%9B%BC%E8%81%94%E6%96%B0%E6%98%9F%E6%83%B3%E5%BD%93%E8%8C%83%E4%BD%A9%E8%A5%BF%E7%AC%AC%E4%BA%8C-1.jpg">```



---

**a**

create links for user to clink with href="...", also give the name between <a></a>

*eg*1:

```<a href="https://www.google.com">Click me to go to Google</a>```



It can also leads to another html page. eg:

```<a href="page2.html">go to page2</a>```



___



## Table

- tr element for each row
- td element for each cell
- th element for each header
- thead is the container for tr + th
- tbody is the container for tr + td



---



## Forms

- **form tag**

  a shell or container for different inputs

  - **action** attribute:

    ​	Specify where to send the data.

  - **method** attribute:

    ​	what type of the http request to send(get, post, etc.)

- **input tag**

  Go inside the forms. Create interactive controls.

  - **type** attribute:

    Determine the type of input

    - radio: usually one choice for user to select
    - Checkbox: allow user to select or unselect

  - **placeholder** attribute:

    background display

  - **id** attribute:

    identification with the **for** set at label tag

  - **name** attribute

    For user to pick one decision. Giving an individual input, a way store/send in http request.

  - **value** attribute

    Indicate the decision the *name* choice.

***To make a form, take a form tag and fill up with input types***



- **label tag**

  ***a container to contain input tag***

  - **for** attribute:

    identification with the **id** attribute set at input tag

    

- **Simple Validations **

  - The 'required' attribute validates that an input is not empty in *input*

  - There are also type validations, eg. try changing "type" from "text" to "email"

  - Password:

    "pattern": can limit the password length,etc.

    *eg: pattern = ".{5,10}"*

    which means "**5 to 10 characters**".

    The string can also be filled in title="" in the password input.

  

- **select tag** 

  - option: 

    Conclude ***option*** tag inside to let user to select options.

    The option value will be the value of the ***key*** as *name* set in select tag

  - Option with value = ""

    value will replace the value set between "><".

    

- **buton**

  If button is at the end of the form, it will submit the form.



- **Textarea tag**

  a text area for user to input, and can be designed with row/columns

  Eg. row="10", cols="10"









