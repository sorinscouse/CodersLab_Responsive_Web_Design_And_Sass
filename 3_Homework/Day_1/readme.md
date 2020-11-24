# Sass & RWD - homework

> Write the code in appropriate files according to exercise descriptions.

**VERY IMPORTANT - Your homework is checked using an automated system. In order for the answers to be considered correct, all the pages MUST display the same messages as in the exercise description, and function and method names MUST be the same as in the exercise description!**


### Day 1 - Sass
> Do the exercises in main.scss and index.html. Generate an appropriate .css file in the css directory

#### Exercise 1

Wrote a mixin named `setTooltip` that will enable you to set any given text in a tooltip. Pass the text to be displayed and the color of tooltip as parameters. The tooltips should appear when the mouse cursor hovers over the `ul` element with `list` class in `index.html`.
Hint: Create an appropriate pseudo-element, e.g. :before or :after.

#### Exercise 2

Based on the map below (using an appropriate Sass function), create a list that contains values only.
Next, using the values from the list and a loop, set sizes for headers in `index.html`, from the smallest to the largest.

```
$font-sizes: (
 fs1: 100px,
 fs2: 50px,
 fs3: 6px
 );
```
Use: http://sass-lang.com/documentation/Sass/Script/Functions.html
