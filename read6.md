There are many common the hardest thing about writing code :
Learning a new technology
Naming things
Testing your code
Debugging
Fixing bugs
Making software maintainable

# but understanding the problem domain its really the hardest part of programming .

If understanding the problem domain is the hardest part of programming and you want to make programming easier, you can do one of two things:
1. Make the problem domain easier
2. Get better at understanding the problem domain

You can often make the problem domain easier by cutting out cases and narrowing your focus to a particular part of the problem.
What I mean by this is that it is often beneficial to take a part of the problem and fully understand that part before expanding the problem domain.

***********************************************************

# JavaScript Objects
Objects contain a set of variables and functions to create a model of a something you would recognize from the real world .
* JavaScript objects are containers for named values called properties or methods

# Object Definition
In an object, variables are known as properties of the object; functions are known as methods of the object .
## Object Properties
- The name:values pairs in JavaScript objects are called properties.
- You can access object properties in two ways: objectName.propertyName
## Object Methods
- Methods are actions that can be performed on objects.
- Methods are stored in properties as function definitions

var person = {
  firstName: "John",
  lastName : "Doe",
  id       : 5566,
  fullName : function() {
    return this.firstName + " " + this.lastName;
  }
};

***********************************************************
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











