Front-End Web Developer Nanodegree Project 4 WebSite Optimization
=======

Received PageSpeed Insights score of:

**94/100 Mobile**
**95/100 Desktop**

(https://developers.google.com/speed/pagespeed/insights/?url=http%3A%2F%2Fmahoneyz.github.io%2FP4_WebOptimization%2F&tab=mobile)
###



How to run the Web Opimization page:
--------

Go to: http://mahoneyz.github.io/P4_WebOptimization/



Optimizations I made to the views/js/main.js file:
-------
* created variable 'ThePizzaContainer' outside the for loop and using getElementsByClassName instead of querySelectorAll

* moved the dx variable creation outside the loop

* incorporated the newwidth variable into the line changing the style.width

* moved pizzasDiv outside the for loop.

* changed uses of querySelectorAll to getElementsByClassName where appropriate

* created the variable phase outside of the loop

* created variable 'thePos' outside loop to improve performance. (dropped time generate last 10 frames by an average of 60 ms)

* created variable specifically for the length of thePizzaContainer so it is not evaluated in every iteration of the for loop

* moved elem declaration outside the for loop

* using getElementById instead of querySelector for better performance

* created a specific variable for the length of items so we don't have to evaluate it every iteration of the for loop below

* created new smaller version of the optimized pizzeria.jpg pic that will be used by index.html (pizza.html will use the regular sized one)



Jim Mahoney June 2015
--------






[Resources]
--------
https://www.udacity.com/course/ud884
https://developer.chrome.com/devtools/docs/tips-and-tricks
https://developers.google.com/web/fundamentals/performance/critical-rendering-path/render-blocking-css.html https://developers.google.com/web/fundamentals/performance/critical-rendering-path/adding-interactivity-with-javascript.html
