# HTML LISTS
## In HTML we can use three types of lists : 
1. ### odreded lists : < ol> each item in the list is numbered . 
2. ### unordered lists : < ul> lists that begin with a bullet point .
3. ### Definition lists : < dl> set of terms along with the definitions for each of those terms .

### In ordered lists and unordered list each item in the list is placed in < li> tag  < /li>
### In definition lists we use < dt> to contain the term being defined, < dd>This is used to contain the definition.

## We can put a second list inside a list tag(nested list ) 
 
# CSS (BOXES)
## Using Css we can set several properties that affect the appearance of these boxes for example:
1. ### boxes dimensions  
box {
height: 300px;
width: 300px;
background-color: #bbbbaa;}

2. ### borders around the boxes 
p.one {  border-width: 2px; }

3. ### we can set margins and   padding \
p.example { padding: 10px;}    p.example { margin: 20px;}

4. ### show and hide the boxes  
li.coming-soon { visibility: hidden;}

### WE can change the display settings :
1. inline
2. block
3. inline-block

## We can set border radius : 
p.one {
border-top-left-radius: 80px 50px;
moz-border-radius-top-left: 80px 50px;
webkit-border-radius-top-left: 80px 50px;}

# JavaScript 
## Arrays variable we can store list of values in it . 
var colors ;

colors=['white', 'black', ' custom '];
## if else statement 

if (score >= pass) {
msg = 'Congratulations, you passed!' ;
}

 else {
msg = 'Have another go!';}

## Switch statement 
### It starts with a variable called the switch value, each case indicates a possible value and the code that should run, example : 

switch (level) 
{
case 1:
msg = 'Good luck on the first test ' ;

break;

case 2:
msg = 'Second of three - keep going!';

break;

case 3:
msg = ' Final round, almost there!';

break;
default :
msg = 'Good l uck!';
break; }

## JavaScript is said to use weak typing because the data type for a value can change.

## Logical operators are processed left to right. They short-circuit (stop) as soon as they have a result

## Loops in Javascript : 
1. ### For looop
2. ### While loop 
3. ### do while loop 
