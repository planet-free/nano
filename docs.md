# nanoJS Docs


#### addClass
```js
$("#a").addClass("newclass");
```

#### animate
```js
$('#c').animate('2.3', '1.2','0','1','1', '0', '0', '0', '0', '1');
```

#### attr
```js
$('#c').attr("class", "newclass");
```

#### css
```js
$(".someClass").css("background-color:green");
```

#### cssdom
```js
$("div").cssdom({backgroundColor:"red", color:"#fff"});
```

#### empty
```js
$('#c').empty();
```

#### eq
```js
$("div").eq(0).html("Hello World!");
```

#### getAttr
```js
$("#b").getAttr("class");
```

#### html
```js
$('#c').html("<p>Hello World!</p>");
```

#### insertAfter, insertBefore, insertFirst insertLast
```js
$('#c').insertAfter("<p>Hello World!</p>");
```
#### offset
```js
$("#b").offset();
$("#c").css("width:" + offset.width + "px");
```

#### on
```js
$("#a").on("click", function(){

  $("#someDiv").css("background-color:green; color:#fff;");

})
```
#### parent
```js
$("p").parent().css("background-color:green");
```

#### removeAttr
```js
$('#c').removeAttr("class");
```

#### removeClass
```js
$('#c').removeClass("someClass");
```
#### siblings
```js
$("#active").siblings().css("background-color:green");

$("li").eq(2).siblings().css("background-color:red");
```

#### text
```js
$('#b').text("Hello World!");
```

#### toggleClass
```js
$('#c').toggleClass("someClass");
```

#### $(this)
```js
$("div").on("click", function(){

  $(this).css("background-color:red");

})
```
