<img alt="Logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">

# RWD &ndash; Media Queries

> Remember to separate exercises with comments and to write legible, well formatted code.

## Exercises done with the lecturer

### Exercise 1. Changing background  (~ 5min - 10min)

In`index.html`, change background color to yellow if the width of the screen is less than `420px`. If it is greater than `420px`, change the background color to blue.

### Exercise 2. Mixin  and `@content` (~ 5min - 10min)

In `index.html` find a `form` element with `my-form` class.

Create a mixin that will enable you to set a `placeholder` for `input` and `textarea` elements in every browser.
Use the `@content` attribute to pass text color to the mixin.

Remember that in the case of the textarea element, adding space between opening and closing tags (space, enter) result in the placeholder not working anymore.

-------------------------------------------------------------------------------

## Exercises to do on your own

### Exercise 1. Media queries  (~ 5min - 10min)
Set media queries according to the following table.

| Screen size in px | Background color |
| :---: | :---: |
| up to 400 | green |
| 400 to 800 | violet |
| over 800 | orange |


### Exercise 2. Element layout  (~ 5min - 10min)
Create two `div` elements in the HTML file. In the Sass file, set them side by side and set their width and height to **300px**. Also, set a color for them, and the left margin to **10px**. Using media queries, make the elements fall under one another on screens narrower than **900px**. In such case, their width should be set to **100%**.
