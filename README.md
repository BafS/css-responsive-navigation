A simple responsive navigation write in pure CSS.

Tested with firefox, chrome, opera and IE9+

How to use it ?
---------------

```html
<nav class="nav">
	<label for="toggle-nav" data-icon="☰" role="navigation"></label>
	<input type="checkbox" id="toggle-nav">

	<ul class="menu" role="menu">
		<li><a href="#">Index</a></li>
		<li><a href="#">FAQ</a></li>
		<li><a href="#">About</a></li>
	</ul>
</nav>
```

![exemple](http://i.imgur.com/cUJD8Lc.png)
[Test online](http://bafs.github.io/css-responsive-navigation/exemple_with_style.html)

You can also use [fastclick](https://github.com/ftlabs/fastclick) to remove click delays on browsers with touch UIs.