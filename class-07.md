# HTML Tables
## There are so many types of information that needs to be displayed in a grid or a table, 
### For example : 
1. #### sports results
2. #### train timetables 
3. #### stock reports

### A table represents information in a grid format .

### In HTML to create a table we use the table element : 
### < table>
### You indicate the start of each row using the opening< tr> tag , It is followed by one or more
### < td> elements (one for each cell in that row)
### The td stands for table data.
### At the end of each cell you use a closing < /td> tag.
### to add table heading we use < th> element its purpose is to represent the heading for either a column or a row.
### colspan attribute : The colspan attribute can be used on a < th> or < td> element to indicates how many columns that cell should run across.
### < thead> The headings of the table should sit inside the < thead> element.
### < tbody>The body should sit inside the < tbody> element.
### <t foot> The footer belongs inside the <t foot> element.

# JavaScript
## We can use the keyword and the object constructor to create a blank object and we can add properties and methods to the objet later . 

1. #### Define the object type by writing a constructor function. There is a strong convention, with good reason, to use a capital initial letter.
2. #### Create an instance of the object with new.

function Car(make, model, year) {
  
  this.make = make;
  
  this.model = model;
  
  this.year = year;
}

var mycar = new Car('Eagle', 'Talon TSi', 1993);

### Another example : 
var hotel = new Object();
hotel.name= 'Park';

hotel.rooms = 120;

hotel .booked = 77;

hotel .checkAvailability = function()

return this . rooms - this.booked;
} ;


var elName = document.getElementByid('hotelName');

elName.textContent = hotel . name;

var elRooms = document .getElementByid('rooms');

elRooms .textContent = hotel .checkAvailability(};

## we can create objects using two ways : 
1. ### LITERAL NOTATION
2. ### OBJECT CONSTRUCTOR NOTATION

### this : The keyword this is commonly used inside functions and objects. Where the function is declared alters what this means. It always refers to one object, usually the object in which the function operates.

## Arrays are a special type of objects, they hold a key and value pairs, the key for each value is its index . 

num=[100,200,300] , 
index number 0 has a value of 100 and so on 

## We have three group of build in objects : 
1. #### browser object model
2. #### document object model
3. #### global javascript objects

## Document object model 
### examples of the DOM methods that select content or update the content of a page:
1. ### document.write()
2. ### document.getElementByld()
3. ### document.querySelectorA11 ()
4. ### document.createTextNode()
5. ### document.createElement()