# Sass & RWD - homework

> Write the code in appropriate files according to exercise descriptions.

**VERY IMPORTANT - Your homework is checked using an automated system. In order for the answers to be considered correct, all the pages MUST display the same messages as in the exercise description, and function and method names MUST be the same as in the exercise description!**


### Day 2
> Do the exercises in main.scss and index.html. Generate an appropriate .css file in the css directory.

#### Exercise 1 - RWD units

In `index.html` you will find a section named `test_units`. Study it carefully. There are several elements within it.
Set the font size of the `test_units` section to `30px`, add border, set its width to `25em` and height to `5em`.
Set the font size of the `header` element to `50%`.

Your task is to write a single CSS rule for span elements that will set their font size (using `em` units) in such a way that:
* the first span was half the size of the font size defined for the `test_units` section,
* the second span was the same size as the font size defined for the  `test_units` section.

#### Exercise 2 - Media Queries and Mobile first

In `index.html` you will find a section named `blocks`.
Create 5 `div` elements with `block` class within it and set the following properties for each of them:
* width: `25%`
* height: `100vh`
* border: `1px solid red`
* align them side by side (if you have any problems doing it, remember the box-model)

Next:
* on screens narrower than `450px` align the elements one under another and hide the last one,
* on screens wider than `450px` and narrower than `720px` align the elements side by side, show the last one and hide the first one,
* on screens wider than `720px` but narrower than `1024px` show only the last and the first element.
Use the **Mobile first** approach.
