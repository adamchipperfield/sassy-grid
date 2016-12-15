# Sassy Grid
12-column grid built in SASS

# How to Use
Getting started with this grid is super easy.

1. Download styles.css and add to your project
2. Use the simple classes to set up the grid.

# The Classes
  - `grid` is the master wrapper
  - `row` declares a row of columns
  - `column` is required for each column. It's also equivalent to using the `span-1` class (see below).
  - `span-*` is used to span a column over a stated number of columns. It's used in addition to the `column` class.
  
# The `span-*` Class
You can use the `span-*` class to have an individual column 'span' (or take up the space of) a number of columns. For example, if you use the class `span-3`, the element will take up the width of 3 columns.

The most common use for this functionality is for websites with a 2-column layout (main content and a sidebar). You'd have two `div` elements, each with the `column` class. The main content div will have the class `span-8` added and the sidebar div will have the class `span-4` added. Notice these add up to 12 to complete the row.

# Want to use SASS?
If you are adventurous and would like to delve into the world of SASS, simply use the scss/styles.scss file in your SASS set up. Not used SASS before? Check out the awesome docs over as [sass-lang.com](http://sass-lang.com/).
