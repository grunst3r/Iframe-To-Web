# Iframe To Web
### Web = Home Page
```
var frame = null;
var iframe = document.getElementById('iframe');
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
