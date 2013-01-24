JQUERY HTML5 FULLSCREEN PLUGIN
===============================

With this plugin you can make any DOM element to fullscreen by binding to any event.

Can make a DOM element fullscreen in two steps. 

1)Load the plugin to HTML Page .Create a variable by calling the plugin and passing the DOM as Jquery Selector.

```javascript
	$(document).ready(function(){
			var fullscreenplugin = new $.fullscreen($('#imageFS'));
	});
```

2) Pass the `fullscreenplugin.enableFullScreen` as a callback to any event.

```javascript
		$('#fsbutton').click(fullscreenplugin.enableFullScreen);
```

DEMO LINK
---------
http://thecodejack.github.com/jquery-html5-fullscreen/demo/Test1.html

DEVELOPER
---------
Srikanth

ISSUES and Improvements
-----------------------
Can suggest the issues and improvements.
