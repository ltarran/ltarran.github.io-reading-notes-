#   <b><center>What is CSS?</center></b>
CSS stands for Cascading Style Sheets. It is the language for describing the presentation of Web pages, including colours, layout, and fonts, thus making our web pages presentable to the users

* Changing Color and size
* Create Layout
* Effects  


## <b>Three Ways to Insert CSS</b>
There are three ways of inserting a style sheet:

### 1. <b>External CSS</b>
    * External style sheets are saved as .csss files and can be used to determine the appearance of an entire website through one file. 
    *  External styles are defined within the ```<link>``` element, inside the ```<head>```section of an HTML page. 
 
 Example:

```
<!DOCTYPE html>
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

### 2. <b>Internal CSS</b>
    * An internal style sheet may be used if one single HTML page has a unique style.

    * The internal style is defined inside the ```<style>``` element, inside the ```<head>``` section.

Example:

```<head>
<style>
Body  {  background-color:thistle;  }
P  {  font-size:20px;  color:mediumblue;  }
</style>
</head>
```

### 3. <b>Inline CSS</b>

    * An inline style may be used to apply a unique style for a single element.
    * Inline styles are defined within the "style" attribute of the relevant element

Example:

```<h1 style="color:blue;text-align:center;">This is a heading</h1>
<p style="color:red;">This is a paragraph.</p>
```
#
1. [Home](https://ltarran.github.io/reading-notes)  

2. [Growth Mindset](https://ltarran.github.io/reading-notes/growthmindset)

3. [Learning Markdown](https://ltarran.github.io/reading-notes/learningmarkdowns)

4.  [Coders Computer](https://ltarran.github.io/reading-notes/coderscomputer)

5.  [Git](https://ltarran.github.io/reading-notes/git)

6. [HTML](https://ltarran.github.io/reading-notes/html)

7. [Wire Framing](https://ltarran.github.io/reading-notes/wireframing)