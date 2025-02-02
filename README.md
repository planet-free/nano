# nanoJS

[![License MIT](https://img.shields.io/badge/licence-MIT-blue.svg)](https://choosealicense.com/licenses/mit/)
[![Gzip Size](https://img.badgesize.io/https://unpkg.com/@planet-free/nano@1.0.5/src/nanoJS.min.js?compression=gzip)](https://unpkg.com/@planet-free/nano@1.0.5/src/nanoJS.min.js)
[![npm](https://img.shields.io/npm/v/@planet-free/nano.svg)](https://www.npmjs.com/package/@planet-free/nano)


Minimal standalone JS library for DOM manipulation

<a href="https://planet-free.github.io/nano/"><img src="logos/png/horizontal%20-%20logo/nano-logo.png"/></a>

nanoJS is around 100 lines of code (0.9 Kb compressed) JavaScript library for basic DOM manipulation. It has jQuery like syntax and supports chaining.

Syntax demos:

```javascript

$(".someClass").css("background-color:green;").html("Hello World");

$('#c').animate('2.3', '1.2','0','1','1','0','0', '0','0','1').css('background-color:red').text('Hello');

$("#a").on("click", function(){

  $("#someDiv").css("background-color:green;color:#fff;");

})

```

[You can find it here some basic examples.](docs.md) also the [Mission & Philosophy of nanoJS](mission.md)


It works in IE9 and later. (some methods addClass, removeClass and toggleClass will not work in IE9)

Read more here:

[https://planet-free.github.io/nano/](https://planet-free.github.io/nano/)

or on my blog:

[http://www.vcarrer.com/2018/05/nanojs-javascript-for-dom-manipulation.html](http://www.vcarrer.com/2018/05/nanojs-javascript-for-dom-manipulation.html)


You can use direct download or:

```sh
npm i @planet-free/nano
```

```sh
yarn add @planet-free/nano
```

```html
<script src="https://unpkg.com/@planet-free/nano@1.0.5/src/nanoJS.min.js"></script>

OR

<script src="https://cdn.jsdelivr.net/npm/@planet-free/nano/src/nanoJS.min.js"></script>
```

### Utils:

addClass  
animate  
attr  
css  
cssdom  
empty  
eq  
getAttr  
html  
insertAfter, insertBefore, insertFirst insertLast  
offset  
on  
parent  
removeAttr  
removeClass  
siblings  
text  
toggleClass  
log
