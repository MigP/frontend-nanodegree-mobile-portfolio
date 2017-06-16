# 1 - Contents

1. - [Contents](README.md#1-contents)
2. - [Installation](README.md#2-installation)
3. - [Part 1 - Portfolio](README.md#3---part-1---portfolio)
    * 3.1 - Assets
    * 3.2 - HTML
    * 3.3 - CSS
    * 3.4 - Javascript
4. - [Part 2 - Pizzas](README.md#4---part-2---pizzas)
    * 4.1 - Assets
    * 4.2 - HTML
    * 4.3 - CSS
    * 4.4 - Javascript

# 2 - Installation

Clone or download. Copy all the content anywhere on your disk and use your browser to open "index.html" for the Portfolio page, or "pizza.html" for the Pizzas page.

# 3 - Part 1 - Portfolio

### [Live Demo](https://migp.github.io/frontend-nanodegree-mobile-portfolio/)

* 3.1 - Assets

    * Created a pizzeria-2.jpg and optimised it. The image went from 2.25Mb to 55.9Kb.

* 3.2 - HTML

    * Minified style.css and inlined it in the head.
    * Linked to the minified version of print.css (print.min.css).
    * Linked to the minified version of perfmatters.js (permatters.min.js).
    * Made the google analytics script async.
    * Removed the link to google fonts and used an async script instead.
    * Moved the google analytics script to the end of the body.
    * Minified index.html.
    
* 3.3 - CSS

    * Minified style.css and inlined it in the head of index.html.
    * Minified print.css (print.min.css).

* 3.4 - Javascript

    * Minified perfmatters.js (permatters.min.js).

# 4 - Part 2 - Pizzas

* 4.1 - Assets

    * Reduced the size of pizza.png and optimised it. The image went from 48.7Kb to 18.1Kb.

* 4.2 - HTML

    * Minified styles.css and inlined it in the head.
    * Linked to the minified version of bootstrap-grid.css (bootstrat-grid.min.css).
    * Linked to the minified version of main.js (main.min.js).
    * Minified pizza.html

* 4.3 - CSS

    * Minified style.css and inlined it in the head of index.html.
    * Minified bootstrap-grid.css (bootstrat-grid.min.css).

* 4.4 - Javascript

    * Reversed a few For loops in order to simply the test condition (lines 343, 347, 351, 442, 495, and 518).
    * Removed the function determineDx altogether which was complicating things unnecessarily, and simplified the function changePizzaSizes (lines 425-445).
    * Took the declaration of pizzasDiv out of the For loop (line 459).
    * Reduced the number of pizzas created from 100 to 30 (line 460).
    * Modified the function updatePositions to avoid forced synchronous layouts (line 493).
    * Used translateX instead of left (line 498).
    * Calculated the number of pizzas needed to fill the screen, and changed sliding from 200 to to that number (lines 517-520).
    * Removed the two lines setting the height and width of the pizzas and added that to the inline styles instead (lines 522-533).
    * Minified main.js (main.min.js).
