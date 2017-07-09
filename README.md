# Website Optimisation Project
### Optimisation made in index.html
* Included styles.css file inline in index.html .
* added media="print" in the print.css link to improve performance.
* added media="print" in the google font link to imporve performance.
* Compressed the images so that the page loads faster.
* made the perfmatters script file asynchronous.
* made google analytics script file asynchronous.
* pagespeed score for the optimised file is (mobile/desktop)=(95/95)
* link for the github page is [here](https://konarssuresh.github.io/frontend-nanodegree-mobile-portfolio/)

### Optimisation made for pizza.html
* Made style.css and bootstrap-grid.css inline to improve performance of page.
* made main.js defer to improve page performance.

### Changes made in main.js
* reduced number of pizzas based on screensize.
* removed **document.body.scrollTop / 1250** out of for loop to increase fps
* changed quertySelector,querySelectorAll to more specific selectors.
* removed *document.getElementsByClassName("randomPizzaContainer")* outside for loop and stored in a variable called pizzaBoxes.





