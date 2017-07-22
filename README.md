# Iframe To Web
### Web = Home Page
```
<iframe id="iframe" src="iframe.html" frameborder="0" style="display:block;"></iframe>
```
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
