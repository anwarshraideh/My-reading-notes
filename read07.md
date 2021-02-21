# CREATING MANY OBJECTS CONSTRUCTOR NOTATION 

Object constructors can use a function as a template for creating objects.
First, create the template with the object's properties and methods.

- The **this** keyword is used instead of the object name to indicate that the property or method belongs to the object that this function creates.
The keyword this is commonly used inside functions and objects.Where the function is declared alters what this means. It always refers
to one object, usually the object in which the function operates.  
- The **new** keyword when they create an object using that function .
function Person(first, last, age, eye) {
  this.firstName = first;
  this.lastName = last;
  this.age = age;
  this.eyeColor = eye;
  this.nationality = "English";
}

// Create 2 Person objects
var myFather = new Person("John", "Doe", 50, "blue");

- In JavaScript, data is represented using name/value pairs. To organize your data, you can use an array or object to group a set of
related values. In arrays and objects the name is also known as a key. 

VARIABLES : has just one key (the variable name) and one value. 
ARRAYS : can store multiple pieces of information.Each piece of information is separated by a comma.The order of the values is important because items
in an array are assigned a number (called an index). 

# Browsers come with a set of built-in objects that represent things like the browser window and the current web page shown in that window. These
built-in objects act like a toolkit for creating interactive web pages. 
# The window object represents the currentbrowser window or tab. It is the topmost object in the Browser Object Model, and it contains other objects that tell you about the browser. 

window.document
window.screen
window.innerHeight

## THE DOM TREE IS A MODEL OF A WEB PAGE 
DOM tree, and it is stored in the browsers' memory. It consists of four main types of nodes :document nodes,element nodes, attribute nodes, and text nodes. 
Each node is an object with methods and properties .

Accessing and updating the DOM tree involves two steps:
1: Locate the node that represents the element you want to work with.
2: Use its text content, child elements, and attributes. 

The terms elements and element nodes are used interchangeably but when people say the DOM is working with an element, it is actually working with a node that represents that element.

#SELECTING ELEMENTS USING ID ATTRIBUTES
get El ementByi d () allows you to select a single element node by specifying the value of its id attribute.
var el = document.getElementByid('one'); 

#DOM QUERIES THAT RETURN MORE THAN ONE ELEMENT
* When a DOM method can return more than one element, it returns a Nodelist (even if it only finds one matching element). 
getElementsByTagName('hl ' ) 
getElementsByClassName('hot') 
querySe l ectorA 11 ( ' l i [id] ' ) 

# SELECTING AN ELEMENT FROM A NODELIST
There are two ways to select an element from a Nodelist: The item() method and array syntax.
Both require the index number of the element you want.  
1.THE item{) METHOD 
Nodelists have a method called item() which will return an individual node from the Node list.
2.array syntax

*The get ElementsByClass Name() method allows you to select elements whose c1ass attribute contains a specific value. 

# SELECTING ELEMENTS USING CSS SELECTORS 
querySe1ector() returns the first element node that matches the CSS-style selector.
querySe1ectorA11 () returns a Nodelist of all of the matches. 
var el = document .querySel ector('li.hot ' }; 
var els = document .querySelectorAll('li.hot') ; 


***********************************************************************************
# What's a Table?
A table represents information in a grid format.Examples of tables include financial reports, TV schedules, and sports results

## Basic Table Structure

The < table > element is used to create a table. The contents of the table are written out row by row
< tr > You indicate the start of each row using the opening < tr > tag. (The tr stands for table row.).
< td > Each cell of a table is represented using a < td > element. (The td stands for table data.).
The < th > element is used just like the < td > element but its purpose is to represent the heading for either a column ora row. (The th stands for table
heading.)
< thead > The headings of the table should sit inside the < thead > element.
< tbody > The body should sit inside the < tbody > element. 
< tfoot > The footer belongs inside the < tfoot > element.

- You can make cells of a table span more than one row or column using the rowspan and colspan attributes.

***********************************************************************************

# Domain Modeling
Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

## Define a constructor and initialize properties
To define the same properties between many objects, you'll want to use a constructor function.

* This is object-oriented programming in JavaScript at its most fundamental level.

- The new keyword instantiates (i.e. creates) an object.
- The constructor function initializes properties inside that object using the this variable.
- The object is stored in a variable for later use

***********************************************************************************