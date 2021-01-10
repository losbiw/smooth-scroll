# Smooth-scroll-page
A way too smoothly scroll through a web page with minimal effort

## Using
In order to use the package you have to: 
1. Import it in your html file ```<script src="https://cdn.jsdelivr.net/npm/smooth-scroll-page/index.js"></script>```
1. Add a unique class to all sections you want to scroll through and only them
1. Add a unique class to all anchor links that lead to scroll sections from the previous step and replace ```href="#something"``` attribute with ```hash="something"```(optional)
1. Add another script tag/file with following code inside ```smoothScroll.init(sectionClassName, linkClassName)```
   1. sectionClassName has to be equal to scroll sections class name
   2. linkClassName has to be equal to anchor links class name
