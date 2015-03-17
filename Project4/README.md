To optimize Index.html, I did the following:

1. In-lined some of the CSS in the HTML. Mainly the CSS needed to render the above the fold content including header. 
2. Reduced the size of the images and specified the image size in the HTML
3. Moved the scripts to the end of the HTML
4. Minified the CSS. 

To optimize views/js/main.js, I did the following: 
1. Improved the updatedPositions function by taking the declaration of variables out of the For loop. 
2. Improved the function for page at load by adding the pizzas when the page is loaded
3. Create the pizzas in memory so we can append the pizzas one time 
5. Only 30 pizzas are created in the background instead of 200 as only a certain number are visible on the screen.
6. I took declarations of variables out of the changePizzaSizes function 
7. I switched from querySelector and querySelectorAll to GetElementById and GetElementsByClassName respectively to improve js performance
8. Minified main.js

Further details on optimizations are provided in comments in main.js

Resources Used:
1. Piazza Discussions (Specifically P4 Tips by Aaron McLean)
2. Page Speed Insights Chrome Extension
3. Chrome Develper Tools 
4. CSS Minifier at http://cssminifier.com/
5. JS Minifier at http://jscompress.com/

