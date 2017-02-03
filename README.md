## Website Performance Optimization portfolio project

### How to run
Access the website thru Github Repository.
The first page is a profile page that contians multiple on-going projects.
Click the Cam's Pizzeria at the bottom to view an eye-burning online pizza hut!

Scroll up and down the pizzeria to check the smoothness!

Also, you can change the pizza size thru the slider. 

The Chrome Dev Tool console will give you ideas of the website performance.

### Part 1: Below are the optimizations applied to the index.html
- 1. Grunt the network-consuming images (pizzeria).
- 2. Set media query for the stylesheet (print.css) dedicated for printing purpose.
- 3. Use internal font-family (sans-serif) instead of requesting from google fonts.
- 4. Minify and inline style.css into html.
- 5. Async blocking google analytics script tasks.
- 6. Minify the final index.html file.
- 7. Inline some of the jpg files to render more contents via the html request.


### Part 2: Below are the steps taken to optimize FPS in pizza.html
- 1. Cancel the "unnecessary" animation of the random pizzas in the background layer. (reduce FSL and adjust a little bit opacity...)
- 2. Avoid FSL during rendering thru replacing the loop structure by jQuery selector. The css style thus can be modified in a single pass. (main.js line:451)

