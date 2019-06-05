# StaticWebsite
A simple website about a destination, made using html, css and bootstrap.

For simplitiy sakes I am using including header and footer in all html files as I  would need to run it from a server.

I could have included header.html and include it like this

```javascript
$(function(){
  $("#header").load("header.html"); 
  $("#footer").load("footer.html"); 
```

but If you run it as a file, It won't load it because of cross origin issues.

