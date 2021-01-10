# JavaScript
## Objects group together a set of variables and functions to create a model of a something you would recognize from the real world. 
### IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES . 
### IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS, Objects consist of a set of name/value pairs
## We can create an object using literal notation .
## For example : 
var person = {
  
  firstName: "John",
  
  lastName: "Doe",
  
  age: 50,
  
  eyeColor: "blue"
};
## You can access the method of an object using dot notaition . 

## DOM
### The Document Object Model (DOM) specifies how browsers should create a model of an HTML page and how JavaScript can access and update the contents of a web page while it is in the browser window.
## The DOM is neither part of HTML, nor part of JavaScript; it is a separate set of rules, it covers two primary areas:
1. #### Making a model of the HTML page 
2. #### Accessing and changing the HTML page 
## The model is called a DOM tree, and it is stored in the browsers' memory.It consists of four main types of nodes:
1. #### THE DOCUMENT NODE
2. #### ELEMENT NODES
3. #### ATTRIBUTE NODES
4. #### TEXT NODES

### Accessing and updating the DOM tree involves two steps:
1. #### Locate the node that represents the element you want to work with.
2. #### Use its text content, child elements, and attributes.

## DOM queries may return one element, or they may return a Nodelist,which is a collection of nodes .
## For example :
1. getElementByld( 1 id 1)
2. querySel ector( 1css selector ')
3. getEl ement sByClassName( 1class 1)
4. getEl ementsByTagName( 1 tagName 1)
5. querySelectorAll ( 1css select or •)

## Traversing the DOM can be difficult because some browsers add a text node whenever they come across whitespace between elements.   