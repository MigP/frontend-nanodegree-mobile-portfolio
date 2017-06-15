# 1 - Contents

1. - [Contents](README.md#1-contents)
2. - [Part 1 - Portfolio](README.md#2---part-1---portfolio)
    * 2.1 - Assets
    * 2.2 - HTML
    * 2.3 - CSS
    * 2.4 - Javascript
3. - [Part 2 - Pizzas](README.md#3---part-2---pizzas)
    * 3.1 - Assets
    * 3.2 - HTML
    * 3.3 - CSS
    * 3.4 - Javascript

# 2 - Part 1 - Portfolio

### [Live Demo](https://migp.github.io/frontend-nanodegree-mobile-portfolio/)

* 2.1 - Assets

    * Reduced the size of pizzeria.jpg and optimised it. The image went from 2.25Mb to 27.6Kb.

* 2.2 - HTML

    * Minified style.css and inlined it in the head.
    * Linked to the minified version of print.css (print.min.css).
    * Linked to the minified version of perfmatters.js (permatters.min.js).
    * Made the google analytics script async.
    * Removed the link to google fonts and used an async script instead.
    * Moved the google analytics script to the end of the body.
    * Minified index.html.
    
* 2.3 - CSS

    * Minified style.css and inlined it in the head of index.html.
    * Minified print.css (print.min.css).

* 2.4 - Javascript

    * Minified perfmatters.js (permatters.min.js).

# 3 - Part 2 - Pizzas

* 3.1 - Assets

    * Reduced the size of pizza.png and optimised it. The image went from 48.7Kb to 24.2Kb.

* 3.2 - HTML

    * Minified styles.css and inlined it in the head.
    * Linked to the minified version of bootstrap-grid.css (bootstrat-grid.min.css).
    * Linked to the minified version of main.js (main.min.js).
    * Minified pizza.html

* 3.3 - CSS

    * Minified style.css and inlined it in the head of index.html.
    * Minified bootstrap-grid.css (bootstrat-grid.min.css).

* 3.4 - Javascript

    * Reversed a few For loops in order to simply the test condition (lines 343, 347, 351, 442, 495, and 518).
    * Removed the function determineDx altogether which was complicating things unnecessarily, and simplified the function changePizzaSizes (lines 425-445).
    * Reduced the number of pizzas created from 100 to 30 (line 459).
    * Modified the function updatePositions to avoid forced synchronous layouts (line 493).
    * Used translateX instead of left (line 498).
    * Changed sliding from 200 to 40, which is more than enough (line 518).
    * Removed the two lines setting the height and width of the pizzas and added that to the inline styles instead (lines 522-533).
    * Minified main.js (main.min.js).
