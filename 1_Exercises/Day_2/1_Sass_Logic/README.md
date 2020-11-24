<img alt="Logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">

# Sass - Logic

> Remember to separate exercises with comments and to write legible, well formatted code.

## Exercise done with the lecturer

### Interpolation and logic (~ 10min - 15min)

Write several headers on the page, e.g. from **h1** to **h4**. In a variable, save line height and basic font size, then apply the styles for the whole document.

Style the headers in such a way that their size changes based on the defined font size. Use loops and interpolation.
Calculate properly the size of each header, remember about their hierarchy (**h1** should be the biggest).

Set different colors for the headers.

Use: http://sass-lang.com/documentation/Sass/Script/Functions.html

-------------------------------------------------------------------------------
## Exercises to do on your own

### Exercise 1. Drawing shapes (~ 5min - 10min)

Write a mixin named `drawItem` that will take two parameters - shape to draw and its background color.

* If the shape is `circle` - it will create a circle with 100px diameter.
* If the shape is `rectangle` - it will create a square with 200px side.

Add the mixin to the `div` with `draw-container` class.

### Exercise 2. Interpolation and logic (~ 10min - 15min)

Using a loop, set border color for ten containers, e.g. `div` elements. The color should be orange for even containers, and blue for the odd ones.
Give the containers **classes** from ```block_1``` to ```block_10```. Use a loop.
