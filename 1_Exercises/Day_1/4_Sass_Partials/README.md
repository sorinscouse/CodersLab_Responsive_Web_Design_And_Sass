<img alt="Logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">

# Sass - Partials

> Remember to separate exercises with comments and to write legible, well formatted code.


## Exercise done with the lecturer

### Exercise 1. Organizing your project  (~ 10min - 15min)

Create directories and files that you will need and organize them as shown below.
Place sample styles according to the description:

```
[folder] scss
    [folder] modules
                _all.scss - variables that store font size and width values
                _colors.scss - variables with colors
    [folder] partials
                _footer.scss - styles for the footer element, use variables defined earlier
                _header.scss - styles for the header element, use variables defined earlier
                _content.scss - styles for the article element, use variables defined earlier
                _base.scss - styles for the entire page
    main.scss - only imports of files created earlier
```

-------------------------------------------------------------------------------
## Exercises to do on your own

### Exercise 1. Dividing style sheets

In `scss` catalog there is a `main.scss` file with styles for the page written in a comment. Take them out of the comment and divide the file as shown in the previous exercise.
