
# layout
## CSS treats each HTML element as if it is in its own box, it could be block-level box or an inline box . 
### Examples of block-level elements : 
1. #### < li>
2. #### < h1>
3. #### < p>
### Examples of inline elements : 
1. #### < img>
2. #### < b>
3. #### < i>
## If one block-level element sits inside another block-level element then the outer box is known as the containing or parent element.
### CSS positioning schemes :
1. #### Normal flow    position:static
2. #### Relative Positioning    position:relative
3. #### Absolute positioning   position:absolute

## We can use float to take an element in normal flow and place it as far to the left or right example
   float: right;

## we can create Multi-Column Layouts with floats :
.column1of2 {

float: left;

width: 620px;

margin: 10px;}

.column2of2 {

float: left;

width: 300px;

margin: 10px;}

## We can use CSS frameworks to provide the code for common tasks, for example, creating layout grids, styling forms, creating printer-friendly versions of pages etc .
## In CSS we can split up CSS style rules into separate style sheets, There are two ways to add multiple style sheets to a page:
1. #### Your HTML page can link to one style sheet and that stylesheet can use the @import rule to import other style sheets
2. #### In the HTML you can use a separate < link> element for each style sheet.

### We have property called clear it say that no element withinthe same containing elementshould touch the left or righthand sides of a box. 
#### if we use clear :left The left-hand side of the box should not touch any other elements.
#### if we use clear: right  The right-hand side of the box should not touch any other elements.
#### clear: none Elements can touch either side.

### Fixed width layout designs do not change size as the user increasesor decreases the size of their browser window.
### Liquid layout designs stretch and contract as the user increases or decreases the size of their browser window.