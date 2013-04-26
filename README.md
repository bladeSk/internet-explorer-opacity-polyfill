Internet Explorer Opacity Polyfill
==================================

A tiny polyfill that adds support for `opacity` CSS rules to IE8, IE7 and probably IE6 too.

Note that this polyfill does not work with inline styles.
jQuery is not required.

Usage
-----

Include the script in your header, optionally with the IE conditional tag.

	<!--[if lte IE 8]><script src="jquery.ie-opacity-polyfill.js"></script><![endif]-->

Now you can happily use `opacity` in your CSS files without the silly `filter` syntax.

	a.transparentLink { opacity: 0.5; }