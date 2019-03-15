# add a link to your current page into the DOM to make it clickable
The anchor text is the page title, and the href is the current location.
This is useful for interacting with the current page with extensions, and also changing which chrome profile you are viewing the page with


To use this bookmarklet, create a new bookmark, and add the following javascript code into the URL field.
```javascript
javascript:!function(a){var b=document.createElement("textarea"),c=document.getSelection();b.textContent=a,document.body.appendChild(b),c.removeAllRanges(),b.select(),document.execCommand("copy"),c.removeAllRanges(),document.body.removeChild(b)}("["+document.title+"]("+document.location+")");
```
