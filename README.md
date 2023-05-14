Haupia
=================
## a tasty little component library by Jeff Yaus

About
-----           
Haupia is a lightweight (just 28K minified!) component library for webpages, designed to be simple to use, to install, and to modify.
It is made from **just pure CSS**, meaning **no build steps**, no JavaScript dependencies, no CSS processing to configure, no image directory to set up. 
While maybe not as feature-rich as some libraries, Haupia is ideal when you just want to get going with a minimum of fuss. 
Just drop the stylesheet onto your page, and you're off! 

Installation
-----
Just download the .css file, link to it on your page, and that's it! Go (coco)nuts!

Usage
----
Documentation and examples at [https://jyaus.github.io/haupia/](https://jyaus.github.io/haupia/)

Browser Support
----
Haupia uses CSS custom properties (variables) and CSS filters, which [most modern browsers](https://caniuse.com/#feat=css-variables) support. 
Dismissible Alerts require the `:has` feature, which [some browsers](https://caniuse.com/css-has) may not support.


Version History
-----
* Version 3.0.1 (2023 May 13): 
 - fixed Accordion marker on Safari
* Version 3.0 (2023 May 13): 
 - breaking API change: "haupia" instead of "hp" in class and variable names
 - breaking API change: Collapsible replaced with Accordion
 - breaking API change: new API for Breadcrumbs, for better a11y support
 - breaking API change: new API for dismissable Alerts, for better a11y support
 - a11y support: added focus-visible state; removed Unicode characters for icons
 - revised visuals for many components
* Version 2.0 (2019 September 27): added accessibility support, including some minor API changes
* Version 1.1 (2018 April 6): added support for shadows on buttons; disabled elements get a "not allowed" cursor
* Version 1.0.1 (2018 March 29): Minor visual fix to the "simple" tabs.
* Version 1.0 (2018 March 28): Hello, world!
