# HTML 
### Links allows us to move from one web page to another web page, for example : 
1. ### We can link from one website to another . 
2. ### We can link from pages from the same web site . 
3. ### Links that open in a new browser window. 

## We can use link by using anchor element < a   href="the website url"> here goes the text that the user click on > < /a> this is how  we link to another website . 
## We can move on pages on our site  < a href="index.html">Home</a> 
## We can use another html pages on the same website even if its inside a folder or multipe folders for examples : 
1. ### < a href="reviews.html">Reviews</a> to link a file inside the same folder  
2. ### < a href="music/listings.html">Listings</a> to link a file inside a folder  

##  We can open the link in a new window using target    < a href="http://www.imdb.com" target="_blank">

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
3. #### Ab solute positioning   position:absolute

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

# JavaScript
###  Programmers use functions, methods, and objects to organize their code by using : 
1. #### BUILT-IN OBJECTS
2. #### OBJECTS
3. #### Functions and Methods

# Functions
## Functions let us group a series of statement together to perform a specific task, we can reuse the function if we need it in diffrent parts of the script . 

## First we call the function that we need (calling), then we give the function the parameters that the function needs, and the function will return a value to us . 

## To declare a function we need to give it a name and write it a statements needed to achieve the function task:
 function sayhello() {
     document.write('hello)
 }
## After declaring a function we can excute all of the statements in it with one line of code, this is known as calling the function. 

## Some function has parameters, some function has values are called arguments and they can be provided as values or as variables. 
## For examples : 
1. Arguments as values : getArea(3,5);
2. Arguments as variables : 
wallwidth=3; wallHeight=5; getArea(wallwidth, wallHeight)
## Pair Programming
### Pair programming is the practice of two developers sharing a single workstation .
### Pair programming involves two roles:
1. #### Driver : the programmer who is typing
2. #### Navigator : navigator thinks about the big picture, what comes next, how an algorithm might be converted in to code .

### Advantages of pair programming : 
1. #### Greater efficiency
2. #### Engaged collaboration
3. #### Learning from fellow students
4. #### Social skills
5. #### Job interview readiness
6. #### Work environment readiness