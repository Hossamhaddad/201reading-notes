# HTML 
## HTML Forms give you the a set of elements to collect data from your users , one of the most popular forms is google search form . 

### Forms types : 
1. #### Adding Text
2. #### Making Choices
3. #### Uploading Files
4. #### Submitting Forms

### We can create forms using < form action="http://www.example.com/subscribe.php" method="get> tag 
### Every from element element requires an action attribute. Its value is the URL for the page on the server that will receive the information in the form when it is submitted.
### method Forms can be sent using one of two methods:
 1. #### get
 2. #### post.

## Text Input
### The < input> element is used to create several different form controls.
 
 < input type="text" name="username" size="15" maxlength="30" /> 
 ### type="text" type attribute has a value of text, name each form control requires a name attribute. The value of this attribute identifies the form control and is sent along with the information they enter to the server, size For example, a value of 3 would create a box wide enough to display three characters, maxlength attribute to limit the number of characters a user may enter into the text field.

### < textarea> element is used to create a mutli-line text input.

### Input types examples : 
1. #### Radio button
2. #### Checkbox
3. #### File Input box 
4. #### Image button

### The list-style-type property allows you to control the shape or style of a bullet point, for example : 
 list-style-type: lower-roman;}
### In unordered list : 
1. #### none 
2. #### disc
3. #### circle
4. #### square

### In ordered lsit : 
1. #### decimal-leading-zero
2. #### decimal
3. #### upper-alpha

### You can specify an image to act as a bullet point using the list-style-image property.
list-style-image: url("images/star.png");}
### Some CSS tables properites examples : 
1. #### width
2. #### padding
3. #### letter-spacing, font-size
4. #### background-color
5. #### hover
6. #### border-top or border-bottom

### The cursor property allows you to control the type of mouse cursor that should be displayed to users.
 example cursor: move


# JavaScript 
## When you browse the web, your browser registers different types of events.
### User Interface Events types 
1. #### load
2. #### unload
3. #### error
4. #### resize
5. #### scroll
### Keyboard Events :
1. #### keydown
2. #### keyup
3. #### keypress 
### Mouse Events : 
1. #### click
2. #### mouseout
3. #### mouseup
4. ####  dbl click

### Form Events
1. ####  reset
2. #### change
3. #### submit
4. #### select
5. #### paste

## THREE WAYS TO BIND AN EVENT TO AN ELEMENT:
1. #### HTML EVENT HANDLERS
2. #### TRADITIONAL DOM EVENT HANDLERS
3. #### DOM LEVEL 2 EVENT LISTENERS
