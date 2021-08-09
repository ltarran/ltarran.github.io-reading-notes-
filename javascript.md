
<h1><center>What is JavaScript?</center></h1>

JavaScript is a scripting language that allows you to implement complex feature on web pages. 

* HTML structures and give meaning to web content. 
* CSS is a language of style.
* JavaScript is scripting language that enables you to create dynamically updating content, control multimediea, and animate images.

<h2><b> The three layers build on top of one another.</b></h2>

Add HTML to give structure and purpose:

```
<p>Hello World</p>
```

<p>Hello World</p>

Then add CSS to give style:

```
p {
  font-family: 'helvetica neue', helvetica, sans-serif;
  letter-spacing: 1px;
  text-transform: uppercase;
  text-align: center;
  border: 2px solid rgba(0,0,200,0.6);
  background: rgba(0,0,200,0.3);
  color: rgba(0,0,200,0.6);
  box-shadow: 1px 1px 2px rgba(0,0,200,0.4);
  border-radius: 10px;
  padding: 3px 10px;
  display: inline-block;
  cursor: pointer;
}
```
Finally add some JavaScript to implement dynamic behavior

```
const para = document.querySelector('p');

para.addEventListener('click', updateName);

function updateName() {
  let name = prompt('Enter a new name');
  para.textContent = 'Hello World: ' + name;
}
```

<h3><center> <b>Initial Setup</b> </center></h3>

The place where you will add code is inside your ```<Script>``` element at the bottom of HTML

```
<script>

  // Your JavaScript goes here

</script>
```

<center> <b>Add variables to store data.</b> </center>

```
let randomNumber = Math.floor(Math.random() * 100) + 1;

const guesses = document.querySelector('.guesses');
const lastResult = document.querySelector('.lastResult');
const lowOrHi = document.querySelector('.lowOrHi');

const guessSubmit = document.querySelector('.guessSubmit');
const guessField = document.querySelector('.guessField');

let guessCount = 1;
let resetButton;
```

<center>This sets up variables and constant you need to store data</center>
 
1. <b>Variable</b>

Variables are containers for values such as numbers or strings of text.
* `var`
* `let`
* `const`

2. <b>Constants </b>

Constants are used to store values that are unable to be changed. 
Created with the keyword `const`.


[Home](http://ltarran.github.io/reading-notes)


<h3> <center><b>Functions and Operators<center></b> </h3>


A JavaScript <b>function</b> is a block of code designed to perform a particular task.

* The name of the function.
* A list of parameters to the function, enclosed in parentheses and separated by commas.
* The JavaScript statements that define the function, enclosed in curly brackets, {...}.

The code defines the name: square

``` 
function square(number) {
  return number * number;
}
```

JavaScript <b>operators</b> allow us to perform tests, do math, join strings together, and other such things.

<b>Control flow</b>

The control flow is the order in which the computer executes statements in a script.
