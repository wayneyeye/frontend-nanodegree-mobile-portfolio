## Website Performance Optimization portfolio project

### Part 1: Below are the optimizations applied to the index.html
- 1. Grunt the network-consuming images (pizzeria).
- 2. Set media query for the stylesheet (print.css) dedicated for printing purpose.
- 3. Use internal font-family (sans-serif) instead of requesting from google fonts.
- 4. Minify and inline style.css into html.
- 5. Async blocking google analytics script tasks.
- 6. Minify the final index.html file.


### Part 2: Below are the steps taken to optimize FPS in pizza.html

To optimize views/pizza.html, you will need to modify views/js/main.js until your frames per second rate is 60 fps or higher. You will find instructive comments in main.js. 

- 1. Cancel the "unnecessary" animation of the random pizzas in the background layer. (reduce FSL and adjust a little bit opacity...)

