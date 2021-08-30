---
title: HTML
date: 2021-07-20 19:16:42
icon: icon-html
background: bg-yellow-600
tags:
    - null
categories:
    - Programming
intro: |
    This HTML quick reference cheat sheet lists the common HTML tags and their attributes in an easy-to-read format.
---


Getting started {.cols-3}
------------

### hello.html {.col-span-2 .row-span-2}

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML5 Boilerplate</title>
</head>
<body>
    <h1>Hello world, hello QuickRef.ME!</h1>
</body>
</html>
```

Or try it out in the [jsfiddle](https://jsfiddle.net/Randy8080/1e4wz20b/)

### Comment

```html
<!-- this is a comment -->

<!--
    Or you can comment out a
    large number of lines.
-->
```


### Paragraph

```html
<p>I'm from QuickRef.ME</p>
<p>Share quick reference cheat sheet.</p>
```
See: [The Paragraph element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/p)




### HTML link

```html 
<a href="https://quickref.me">QuickRef</a>
<a href="mailto:jack@abc.com">Email</a>
<a href="tel:+12345678">Call</a>
<a href="sms:+12345678&body=ha%20ha">Msg</a>
```
---

|   |          |                                                    |
|---|----------|----------------------------------------------------|
|   | `href`   | The URL that the hyperlink points to               |
|   | `rel`    | Relationship of the linked URL                     |
|   | `target` | Link target location: <br/>`_self`, `_blank`, `_top`, `_parent` |
{.left-text}

See: [The \<a> Attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a#attributes)



### Image Tag

```html {.wrap}
<img loading="lazy" src="https://xxx.png" alt="Describe image here" width="400" height="400">
```
---

|   |          |                                     |
|---|----------|-------------------------------------|
|   | `src`    | Required, Image location _(URL \| Path)_ |
|   | `alt`    | Describe of the image               |
|   | `width`  | Width of the image                  |
|   | `height` | Height of the image                 |
|   | `loading`| How the browser should load         |
{.left-text}

See: [The Image Embed element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img)



### Text Formatting Tags

```html
<b>Bold Text</b>
<strong>This text is important</strong>
<i>Italic Text</i>
<em>Emphasis - This text is emphasized</em>
<u>Underline Text</u>
<pre>Preformatted text</pre>
<code>Source code</code>
<del>Deleted text</del>
<mark>Marked/highlighted text</mark>
<ins>Inserted text</ins>
<sup>Makes text superscripted</sup>
<sub> Makes text subscripted</sub>
<small>Makes text smaller</small>
<pre>Pre-formatted Text</pre>
<kbd>Ctrl</kbd>
<blockquote>Text Block Quote</blockquote>
```


### Headings
```html
<h1> This is Heading 1 </h1>
<h2> This is Heading 2 </h2>
<h3> This is Heading 3 </h3>
<h4> This is Heading 4 </h4>
<h5> This is Heading 5 </h5>
<h6> This is Heading 6 </h6>
```
You should only have one h1 on your page


### Section Divisions

|                 |                                      |
|-----------------|--------------------------------------|
| `<div></div>`   | Division or Section of Page Content  |
| `<span></span>` | Section of text within other content |
| `<p></p>`       | Paragraph of Text                    |
| `<br>`          | Line Break                           |
| `<hr>`          | Basic Horizontal Line                |

These are the tags used to divide your page up into sections


### JavaScript in HTML

```html
<script type="text/javascript">
    let text = "Hello QuickRef.ME";
    alert(text);
</script>
```

#### External JavaScript

```html
<head>
    ...
    <script src="app.js"></script>
</head>
```

### CSS in HTML

```html
<style type="text/css">
    h1 {
        color: purple;
    }
</style>
```

#### External CSS

```html
<body>
...
<link rel="stylesheet" href="style.css"/>
</body>
```

### Inline Frame
```html {.wrap}
<iframe id="inlineFrameExample"
    title="YouTube video player"
    width="560"
    height="215"
    src="https://www.youtube.com/embed/HmZKgaHa3Fg"
    allow="fullscreen; accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture;">
</iframe>
```
#### ↓ Preview
<iframe id="inlineFrameExample"
    title="YouTube video player"
    width="560"
    height="215"
    src="https://www.youtube.com/embed/HmZKgaHa3Fg"
    allow="fullscreen; accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture;">
</iframe>

See: [The Inline Frame element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe)


HTML Tables {.cols-3}
--------------

### Table Example {.row-span-2}
```html
<table>
    <thead>
        <tr>
            <td>name</td>
            <td>age</td>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Roberta</td>
            <td>39</td>
        </tr>
        <tr>
            <td>Oliver</td>
            <td>25</td>
        </tr>
    </tbody>
</table>
```



### HTML Table Tags {.row-span-2}

| Tag                                                                               | Description                      |
|-----------------------------------------------------------------------------------|----------------------------------|
| [\<table>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)       | Defines a table                  |
| [\<th>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th)             | Defines a header cell in a table |
| [\<tr>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tr)             | Defines a row in a table         |
| [\<td>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/td)             | Defines a cell in a table        |
| [\<caption>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/caption)   | Defines a table caption          |
| [\<colgroup>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/colgroup) | Defines a group of columns       |
| [\<col>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/col)           | Defines a column within a table  |
| [\<thead>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/thead)       | Groups the header content        |
| [\<tbody>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tbody)       | Groups the body content          |
| [\<tfoot>](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/tfoot)       | Groups the footer content        |

### \<td> Attributes

| Attribute   | Description                                   |
|-------------|-----------------------------------------------|
| `colspan`   | Number of columns a cell should span          |
| `headers`   | One or more header cells a cell is related to |
| `rowspan`   | Number of rows a cell should span             |

See: [td\#Attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/td#attributes)



### \<th> Attributes

| Attribute   | Description                                   |
|-------------|-----------------------------------------------|
| `colspan`   | Number of columns a cell should span          |
| `headers`   | One or more header cells a cell is related to |
| `rowspan`   | Number of rows a cell should span             |
| `abbr`      | Description of the cell's content             |
| [scope](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th#attr-scope)     | The header element relates to |

See: [th\#Attributes](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/th#attributes)



HTML Lists {.cols-3}
--------------


### Unordered list
```html
<ul>
    <li>I'm an item</li>
    <li>I'm another item</li>
    <li>I'm another item</li>
</ul>
```
See: [The Unordered List element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)


### Ordered list

```html
<ol>
    <li>I'm the first item</li>
    <li>I'm the second item</li>
    <li>I'm the third item</li>
</ol>
```
See: [The Ordered List element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)


### Definition list

```html
<dl>
    <dt>A Term</dt>
    <dd>Definition of a term</dd>
    <dt>Another Term</dt>
    <dd>Definition of another term</dd>
</dl>
```
See: [The Description List element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl)




HTML Forms {.cols-3}
-----------


### Form tags {.row-span-2}
```html
<form method="POST" action="api/login">
  <label for="mail">Email: </label>
  <input type="email" id="mail" name="mail">
  <br/>
  <label for="pw">Password: </label>
  <input type="password" id="pw" name="pw">
  <br/>
  <input type="submit" value="Login">
  <br/>
  <input type="checkbox" id="ck" name="ck">
  <label for="ck">Remember me</label>
</form>
```

#### ↓ Preview
<form method="POST" action="api/login" style="padding: 20px;">
    <label for="email">Email: </label> 
    <input type="email" id="email" name="email" class="border border-gray-400 mt-2">
    <br/>
    <label for="pwd">Password: </label> 
    <input type="password" id="pwd" name="pwd" class="border border-gray-400 mt-2">
    <br/>
    <input type="submit" value="Login" class="mt-2">
    <br/>
    <input type="checkbox" id="ck" name="ck" class="mt-2">
    <label for="ck">Remember me</label> 
</form>


The HTML `<form>` element is used to collect and send information to an external source.


### Form Attribute
| Attribute   | Description                                                                                                                                           |
|-------------|-------------------------------------------------------------------------------------------------------------------------------------------------------|
| `name`      | Name of form for scripting                                                                                                                     |
| `action`    | URL of form script |
| `method`    | HTTP method, `POST` / `GET` _(default)_             |
| `enctype`   | Media type, See [enctype](https://developer.mozilla.org/en-US/docs/Web/API/HTMLFormElement/enctype) |
| `onsubmit`   | Runs when the form was submit |
| `onreset`    | Runs when the form was reset |





### Label tags
```html
<!-- Nested label -->
<label>Click me 
<input type="text" id="user" name="name"/>
</label>
```
---
```html
<!-- 'for' attribute -->
<label for="user">Click me</label>
<input id="user" type="text" name="name"/>
```
`for` in a label references an input's `id` attribute





### Input tags
```html
<label for="Name">Name:</label>
<input type="text" name="Name" id="">
```
#### ↓ Preview
<form style="padding: 20px;">
    <label for="username">Username:</label>
    <input type="text" name="username" id="username" class="border border-gray-400">
</form>

See: [HTML input Tags](/html#html-input-tags)


### Textarea tags
```html {.wrap}
<textarea rows="2" cols="30" name="address" id="address"></textarea>
```
#### ↓ Preview
<form style="padding: 20px;">
    <textarea rows="2" cols="30" name="address" id="address" class="border border-gray-400"style="width: 100%"></textarea>
</form>

Textarea is a multiple-line text input control



### Radio Buttons
```html
<input type="radio" name="gender" id="m">
<label for="m">Male</label>
<input type="radio" name="gender" id="f">
<label for="f">Female</label>
```
#### ↓ Preview
<form style="padding: 20px;">
    <input type="radio" name="gender" id="m">
    <label for="m">Male</label>
    <input type="radio" name="gender" id="f">
    <label for="f">Female</label>
</form>

Radio buttons are used to let the user select exactly one



### Checkboxes
```html
<input type="checkbox" name="sports" id="soccer">
<label for="soccer">Soccer</label>
<input type="checkbox" name="sports" id="baseball">
<label for="baseball">Baseball</label>
```
#### ↓ Preview
<form style="padding: 20px;">
    <input type="checkbox" name="sports" id="soccer">
    <label for="soccer">Soccer</label>
    <input type="checkbox" name="sports" id="baseball">
    <label for="baseball">Baseball</label>
</form>

Checkboxes allows the user to select one or more



### Select tags
```html
<label for="city">City:</label>
<select name="city" id="city">
    <option value="1">Sydney</option>
    <option value="2">Melbourne</option>
    <option value="3">Cromwell</option>
</select>
```

#### ↓ Preview
<form style="padding: 20px">
    <label for="city">City:</label>
    <select name="city" id="city" class="border border-gray-400">
        <option value="1">Sydney</option>
        <option value="2">Melbourne</option>
        <option value="3">Cromwell</option>
    </select>
</form>

A select box is a dropdown list of options



### Fieldset tags
```html
<fieldset>
    <legend>Choose your favorite monster</legend>
    <input type="radio" id="kraken" name="monster">
    <label for="kraken">Kraken</label><br/>
    <input type="radio" id="sasquatch" name="monster">
    <label for="sasquatch">Sasquatch</label><br/>
</fieldset>
```
#### ↓ Preview
<form style="padding: 20px">
    <fieldset class="border border-gray-400" style="padding: 20px">
        <legend>Choose your favorite monster</legend>
        <input type="radio" id="kraken" name="monster">
        <label for="kraken">Kraken</label><br/>
        <input type="radio" id="sasquatch" name="monster">
        <label for="sasquatch">Sasquatch</label><br/>
    </fieldset>
</form>




### Datalist tags
```html
<label for="b">Choose a browser: </label>
<input list="list" id="b" name="browser"/>
<datalist id="list">
  <option value="Chrome">
  <option value="Firefox">
  <option value="Internet Explorer">
  <option value="Opera">
  <option value="Safari">
  <option value="Microsoft Edge">
</datalist>
```

#### ↓ Preview
<form style="padding: 20px">
    <label for="myBrowser">Choose a browser:</label>
    <input list="browsers" id="myBrowser" name="myBrowser" class="border border-gray-400"/>
    <datalist id="browsers">
      <option value="Chrome">
      <option value="Firefox">
      <option value="Internet Explorer">
      <option value="Opera">
      <option value="Safari">
      <option value="Microsoft Edge">
    </datalist>
</form>




### Submit and Reset Buttons
```html
<form action="register.php" method="post">
  <label for="foo">Name:</label>
  <input type="text" name="name" id="foo">
  <input type="submit" value="Submit">
  <input type="reset" value="Reset">
</form>
```
#### ↓ Preview
<form action="register.php" method="post" style="padding: 20px">
    <label for="name">Name:</label>
    <input type="text" name="name" id="name" class="border border-gray-400">
    <input type="submit" value="Submit">
    <input type="reset" value="Reset">
</form>

`Submit` the data to server; `Reset` to default values





HTML input Tags {.cols-2}
-----------


### Input Attributes {.row-span-2}
The input tag is an empty element, identifying the particular type of field information to obtain from a user.
```html {.wrap}
<input type="text" name="?" value="?" minlength="6"	 required />
```

----

| - |                         |                                                 |
|---|-------------------------|-------------------------------------------------|
|   | `type="…"`              | The type of data that is being input            |
|   | `value="…"`             | Default value                                   |
|   | `name="…"`              | Used to describe this data in the HTTP request  |
|   | `id="…"`                | Unique identifier that other HTML elements      |
|   | `readonly`              | Stops the user from modifying                   |
|   | `disabled`              | Stops any interaction                           |
|   | `checked`               | The radio or checkbox select or not             |
|   | `required`              | Being compulsory, See [required](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/required#example)                                |
|   | `placeholder="…"`       | Adds a temporary, See [::placeholder](https://developer.mozilla.org/en-US/docs/Web/CSS/::placeholder#examples)                                |
|   | `autocomplete="off"`    | Disable auto completion                         |
|   | `autocapitalize="none"` | Disable auto capitalization                     |
|   | `inputmode="…"`         | Display a specific keyboard, See [inputmode](https://developer.mozilla.org/en-US/docs/Web/HTML/Global_attributes/inputmode)  |
|   | `list="…"`              | The id of an associated [datalist](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/datalist)              |
|   | `maxlength="…"`         | Maximum number of characters                    |
|   | `minlength="…"`         | Minimum number of characters                    |
|   | `min="…"`               | Minimum numerical value on range & number       |
|   | `max="…"`               | Maximum numerical value on range & number       |
|   | `step="…"`              | How the number will increment in range & number |
|   | `pattern="…"`           | Specifies a [Regular expression](/regex), See [pattern](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/pattern)        |
|   | `autofocus`             | Be focused                                      |
|   | `spellcheck`            | Perform spell checking                          |
|   | `multiple`              | Whether to allow [multiple](https://developer.mozilla.org/en-US/docs/Web/HTML/Attributes/multiple) values |
|   | `accept=""`             | Expected file type in [file](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/file) upload controls      |
{.left-text}

Also see: [Attributes for the \<input> element](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input#attributes)


### Input types

|                         |                                                              |
|-------------------------|--------------------------------------------------------------|
| `type="date"`           | <input type="date" class="border border-gray-400">           |
| `type="time"`           | <input type="time" class="border border-gray-400">           |
| `type="month"`          | <input type="month" class="border border-gray-400">          |
| `type="datetime-local"` | <input type="datetime-local" class="border border-gray-400"> |
| `type="week"`           | <input type="week" class="border border-gray-400">           |

| `type="checkbox"`       | <input type="checkbox" class="border border-gray-400">       |
| `type="radio"`          | <input type="radio" class="border border-gray-400">          |
| `type="color"`          | <input type="color" value="#0FB881" class="border border-gray-400">          |
| `type="file"`           | <input type="file" class="border border-gray-400">           |
| `type="hidden"`         | <input type="hidden" class="border border-gray-400">         |

| `type="number"`         | <input type="number" class="border border-gray-400">         |
| `type="range"`          | <input type="range" class="border border-gray-400">          |

| `type="text"`           | <input type="text" class="border border-gray-400">           |
| `type="search"`         | <input type="search" class="border border-gray-400">         |
| `type="password"`       | <input type="password" class="border border-gray-400">       |
| `type="email"`          | <input type="email" class="border border-gray-400">          |
| `type="tel"`            | <input type="tel" class="border border-gray-400">            |
| `type="url"`            | <input type="url" class="border border-gray-400">            |

| `type="image"`          | <input type="image" src="https://raw.githubusercontent.com/mdn/learning-area/master/html/forms/image-type-example/login.png" width="70"> |
| `type="reset"`          | <input type="reset" class="border border-gray-400">          |
| `type="button"`         | <input type="button" class="border border-gray-400">Button</input>         |
| `type="submit"`         | <input type="submit" class="border border-gray-400">         |


### Input CSS selectors

|                  |                                                |
|------------------|------------------------------------------------|
| `input:focus`    | When its keyboard focused                      |
See: [Input pseudo classes](/css#input-pseudo-classes)


HTML meta Tags {.cols-2}
-----------

### Meta tags {.row-span-3}

The meta tag describes meta data within an HTML document. It explains additional material about the HTML.


```html
<meta charset="utf-8">
```

```html
<!-- title -->
<title>···</title>
<meta property="og:title"  content="···">
<meta name="twitter:title" content="···">
```
---

```html
<!-- url -->
<link rel="canonical"       href="https://···">
<meta property="og:url"  content="https://···">
<meta name="twitter:url" content="https://···">
```
---

```html
<!-- description -->
<meta name="description"         content="···">
<meta property="og:description"  content="···">
<meta name="twitter:description" content="···">
```
---

```html
<!-- image -->
<meta property="og:image"  content="https://···">
<meta name="twitter:image" content="https://···">
```
---

```html
<!-- ua -->
<meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
```
---

```html
<!-- viewport -->
<meta name="viewport" content="width=device-width">
<meta name="viewport" content="width=1024">
```




### Open Graph
```html
<meta property="og:type" content="website">
<meta property="og:locale" content="en_CA">
<meta property="og:title" content="HTML cheatsheet">
<meta property="og:url" content="https://quickref.me/html">
<meta property="og:image" content="https://xxx.com/image.jpg">
<meta property="og:site_name" content="Name of your website">
<meta property="og:description" content="Description of this page">
```
Used by Facebook, Instagram, Pinterest, LinkedIn, etc.


### Twitter Cards
```html
<meta name="twitter:card" content="summary">
<meta name="twitter:site" content="@QuickRef_ME">
<meta name="twitter:title" content="HTML cheatsheet">
<meta name="twitter:url" content="https://quickref.me/html">
<meta name="twitter:description" content="Description of this page">
<meta name="twitter:image" content="https://xxx.com/image.jpg">
```
See: [Twitter Card Documentation](https://developer.twitter.com/en/docs/tweets/optimize-with-cards/overview/summary)



### Geotagging
```html
<meta name="ICBM" content="45.416667,-75.7">
<meta name="geo.position" content="45.416667;-75.7">
<meta name="geo.region" content="ca-on">
<meta name="geo.placename" content="Ottawa">
```
See: [Geotagging](https://en.wikipedia.org/wiki/Geotagging#HTML_pages)



Also see
--------

- [HTML 4.01 Specification](https://www.w3.org/TR/REC-html40/cover.html#minitoc) _(w3.org)_