Internet Explorer Opacity Polyfill
==================================

A tiny polyfill that adds support for `opacity` CSS rules to IE8, IE7 and IE6. jQuery not required.

Note that this polyfill does not work with inline styles. Another requirement for IE6 and 7 is to have the stylesheets hosted on the same domain as the website. Stylesheets that don't need opacity fixing may be placed anywhere.

Usage
-----

Include the script in your header, optionally with the IE conditional tag.

	<!--[if lte IE 8]><script src="jquery.ie-opacity-polyfill.js"></script><![endif]-->

Now you can use opacity in CSS like you would in a real browser (without the silly `filter` syntax).

	a.transparentLink { opacity: 0.5; }