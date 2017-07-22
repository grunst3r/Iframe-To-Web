# Iframe To Web
### Web = Home Page
```
var iframe = document.getElementById('temporal');
iframe.onload = function(){
 frame = iframe.contentWindow;
 frame.abc();
}
```
### Iframe = Functions
```
function abc(){
alert("Hello !");
}
```
