# Grid

Please note this is a work in progress.

## Getting started

[Download Sass here](http://sass-lang.com/install).

To edit the Sass files, `cd` into the project directory and run `sass --watch scss:css` in the command line.

To just view the grid, open `index.html`.

## Motiviations for the new grid
* Not restrained to a fixed pixel grid. % and REMs only.
* Column widths can change at different breakpoints.
* Vertically align content easily.
* No more clear floats / clearfixes.
* It can handle any width you throw at it ranging from twelfths, all the way to one-whole.
* Nest grids infinite number of times.
* Mobile first media queries.
  
## Tests
* IE Edge - Passed
* IE11 - Passed
* IE10 - Passed
* IE9 - Passed
* Firefox (32 - 43) - Passed
* Chrome (37 - 48) - Passed
* Safari (5 - 9) - Passed
* Basically any browser that [supports REM units](http://caniuse.com/#feat=rem) will support the grid.
* Could write a px fallback for browsers that don't support REM units in the future.

## To be added
* Column offsetting