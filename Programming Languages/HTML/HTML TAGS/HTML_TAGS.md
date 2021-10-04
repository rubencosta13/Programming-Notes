# HTML TAGS

---
Here are some of the most important HTML tags
There are much more. You can find a list of all the HTML tags in: [LINK](https://way2tutorial.com/html/tag/index.php)
---

Lets get started

---
Header:
---

```html
<html>
  <body>
      <h1>I'm a Header (h1)</h1>
      <h2>I'm a Header (h2)</h2>
      <h3>I'm a Header (h3)</h3>
      <h4>I'm a Header (h4)</h4>
      <h5>I'm a Header (h5)</h5>
      <h6>I'm a Header (h6)</h6>
  </body>
</html>
```
<h1>I'm a Header (h1)</h1>
<h2>I'm a Header (h2)</h2>
<h3>I'm a Header (h3)</h3>
<h4>I'm a Header (h4)</h4>
<h5>I'm a Header (h5)</h5>
<h6>I'm a Header (h6)</h6>



---
Body: 
---
Body is where all the content of the page is going to be displayed. 

in the body tag you can use some of the following tags:


---
## Text tags:
---

```html
<html>
  <body>
      <p>This is an HTML paragraph</p>
  </body>
</html>
```

<p>This is an HTML paragraph</p>

```html
<html>
  <body>
      <i>This shows a text in Italic</i>
  </body>
</html>
```

<i>This shows a text in Italic</i>

```html
<html>
  <body>
      <u>This text shows as underlined</u>
  </body>
</html>
```
<u>This text shows as underlined</u>

```html
<html>
  <body>
      <p>This text is <sup>superior to the line</sup></p>
  </body>
</html>
```
<p>This text is <sup>superior to the line</sup></p>

```html
<html>
  <body>
      <p>This text is <sub>inferior to the line</sub></p>
  </body>
</html>
```
<p>This text is <sub>inferior to the line</sub></p>

```html
<html>
  <body>
      <p>This text is <b>bold</b></p>
  </body>
</html>
```
<p>This text is <b>bold</b></p>


```html
<html>
  <body>
      <p style='color: orange'>This text is colored</p>
  </body>
</html>
```
<p style='color: orange'>This text is colored</p> (in github you might not see the colors, but you can test it by yourself)

You can add any color, replacing the orange value for any color you want, As well as combine any of the other tags from above

Here is an example: 
```html
<html>
  <body>
      <p style='color: red'>This text is <b><sup>colored and bold</sup></b> and we can also make it <i>Italic</i></p>
    </body>
</html>
```

<p style='color: red'>This text is <b><sup>colored and bold</sup></b> and we can also make it <i>Italic</i></p>


---
Image tags:
---

Adding an image is always a great choice to your website

```html
<html>
  <body>
      <img scr='https://cdn-icons-png.flaticon.com/512/25/25231.png'>Here is an image from the github logo</img>
      <!-- Important to note that the image, this way is going to be displayed as the original size-->
  </body>
</html>
```
<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" />

Here is an image from the github logo

```html
<html>
  <body>
      <img scr='https://cdn-icons-png.flaticon.com/512/25/25231.png' width='100px' height='100px'>Here is an image from the github logo</img>
      <!-- This image is a 100px by 100px image using the values **width** and **height** you can set a dimension to the image-->
  </body>
</html>
```
<img src="https://cdn-icons-png.flaticon.com/512/25/25231.png" width="100" height="100" />

Here is an image from the github logo

---
"Link" tags:
---
To make a text clickable, we have to use a special tag called: "a"

```html
<html>
    <a href="http://github.com/rubencosta13">This goes to RubenCosta13`s Github page</a>
</html>
```
<a href="http://github.com/rubencosta13">This goes to RubenCosta13`s Github page</a>

There are a lot of diferent combinations, you can even use [Text Formating](#text-tags)


```html
<html>
    <a href="mailto:rubenlavoscosta@gmail.com">Clicking this link you will send me an email</a>
    <!-- This sends an email thanks to the word: mailto: (If we divide the word mailto into two words we will get Mail to which is the function of this word) -->
</html>
```

<a href="mailto:rubenlavoscosta@gmail.com">Clicking this link you will send me an email</a>
