#Page Preloader

Based off of Codrops tutorial found here - http://tympanus.net/codrops/2014/08/05/page-preloading-effect/


This is a page preloading effect made with CSS animations, SVG, and JavaScript.

*Inline SVGs* are used so we can style their paths in CSS. 
I made the DevMountain logo by converting it to .svg and exporting its path using [Gimp](https://www.gimp.org/).


##Resources:

####CSS
[CSS Transitions](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transitions/Using_CSS_transitions) - provide a way to control animation speed when changing CSS properties
[CSS Transforms](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Transforms/Using_CSS_transforms) - change the shape and position of content without disrupting document flow
[CSS Animations](http://www.w3schools.com/css/css3_animations.asp) - allows element to gradually change from one style to another (see also: [@keyframes](https://developer.mozilla.org/en-US/docs/Web/CSS/@keyframes))
[translate3d()](https://developer.mozilla.org/en-US/docs/Web/CSS/transform-function/translate3d) - moves position of element in 3d space

####SVG
[SVG](https://developer.mozilla.org/en-US/docs/Web/SVG) - markup language for describing vector graphics (SVG is to graphics what HTML is to text)
[SVG Line Animation](https://jakearchibald.com/2013/animated-line-drawing-svg/) - interactive blog post about SVG line animation
[fill](https://css-tricks.com/almanac/properties/f/fill/) - fills in the color of SVG shape

####JavaScript
[Modernizr](https://modernizr.com/) - Modernizr tells you what HTML, CSS and JavaScript features the user’s browser has to offer.

[classie](https://github.com/desandro/classie) - Use classie only if you need to support older browsers that do not support classList