# A Simple and Basic Responsive Grid Using CSS Flexible Box #

June 2016  
Edwardson Tan

## Features ##
* CSS Flexible Box is used instead of inline blocks and floats
* All columns widths are specified as percentages
* Multi-column layout automatically changes to a single column for small viewport devices and resized broswers on desktops
* Stylesheet is coded in Sass with gutter margin defined as a single variable and is therefore adjustable to suit page/site requirements
* Images wider than the columns they're contained in resize automatically to fit column width

## Requirements ##
[Sass](http://sass-lang.com/) compiler is necessary to create the CSS. (I use [Koala](http://koala-app.com/).)

## Procedure ##
Download normalize.css into css folder/directory. Compile scss file and import normalize.css and any other css files and then minify the combined css. [Koala](http://koala-app.com/) does the scss compilation, import of external files, and css minfication automatically when configured correctly.

## Acknowledgement ##
[Normalize.css](https://necolas.github.io/normalize.css/) is by Nicolas Gallagher and Jonathan Neal. Their stylesheet is provided on an [MIT License](https://opensource.org/licenses/MIT).

## License ##
[MIT License](https://opensource.org/licenses/MIT)
