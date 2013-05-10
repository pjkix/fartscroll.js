# fartscroll.js

Everyone farts. And now your web pages can too.

_Now with 100% less jQuery! (Sorry, jQuery, we still love you)_

### Setup:

1. Include "fartscroll.js" in your page.
2. Initialize the fartscroll plugin once the DOM has loaded:

```javascript
// Fart every 400 pixels scrolled
fartscroll(); 

// Fart every 800 pixels scrolled
fartscroll(800);
```
### Bookmarklet: 

Or use the following bookmarklet directly from your browser to add fartscroll to any page

	(function(){var e=document.createElement("script");e.setAttribute("src","https://raw.github.com/theonion/fartscroll.js/master/fartscroll.js");document.head.appendChild(e);window.setTimeout(function(){fartscroll(800)},500)})()
	
    
More info at [http://theonion.github.io/fartscroll.js/](http://theonion.github.io/fartscroll.js/).
