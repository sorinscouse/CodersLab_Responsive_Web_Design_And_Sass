<img alt="Logo" src="http://coderslab.pl/svg/logo-coderslab.svg" width="400">

# Sass/RWD - Snippets
> Short pieces of code that solve various problems, illustrate dependencies, or show how to use some more complicated functions.

## Gulp

### 1. How should a gulpfile with Sass compilation look like?

```JavaScript
var gulp = require('gulp');
var sass = require('gulp-sass');
var sourcemaps = require('gulp-sourcemaps');

gulp.task('sass', function() {
    return gulp.src('scss/style.scss')
        .pipe(sourcemaps.init())
        .pipe(sass({
            errLogToConsole: true,
            outputStyle: 'expanded'
        }))
        .pipe(sourcemaps.write())
        .pipe(gulp.dest('css'))
});

gulp.task('watch', function(){
    gulp.watch('scss/**/*.scss', ['sass']);
});
```

## Sass

### 2. How should the file structure in the project look like?

```
[catalog] css
[catalog] images
[catalog] js
[catalog] sass
         .gitignore
         gulpfile.js
         index.html
```
Sass directory structure
```
[catalog] sass
    [catalog] modules
                _all.scss
                _colors.scss
                _mixins.scss
    [catalog] partials
                _footer.scss
                _header.scss
                _base.scss
    main.scss
```


## RWD


### 1. Centering an element using viewport

Why are the bottom and top margins set to 30vh? We must fill `100%` of viewport: `30 * 2 + 40` equals 100vh

```
.rectangle {
    width: 40vw;
    height: 40vh;
    margin: 30vh auto;
    background-color: green;
}

```

### 2. Detecting the device using JavaScript

```JavaScript
var isMobile = false;
if( /Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent) ) {
  isMobile = true;
}
```
There are many more methods to check the device. See: http://stackoverflow.com/questions/11381673/detecting-a-mobile-browser
