# What is jQuery.
jQuery is a popular JavaScript library. It was created by John Resig in 2006 with a purpose to make it easier for developers to use JavaScript on websites. It’s not a separate programing language and works in conjunction with JavaScript.

It is just a JavaScript file but estimates show it has been used on over a quarter of the sites on the web, because it makes coding simpler. 

jQuery's motto is "Write less, do more," because it allows you to achieve the same goals but in fewer lines of code than you would need to write with plain JavaScript. 

# jQuery Syntax

$(selector).action()

* $ sign to define/access jQuery
* (selector) to "query (or find)" HTML elements
* jQuery action() to be performed on the element(s)

# jQuery Selectors
jQuery selectors allow you to select and manipulate HTML element(s).

jQuery selectors are used to "find" (or select) HTML elements based on their name, id, classes, types, attributes, values of attributes and much more. It's based on the existing CSS Selectors, and in addition, it has some own custom selectors.

All selectors in jQuery start with the dollar sign and parentheses: $().

# GETTING ELEMENT CONTENT 

* . html() 
When this method is used to retrieve information 
from a jQuery selection, it retrieves only the HTML 
inside the first element in the matched set, along 
with any of its descendants. 
$ (' u l ' ) • html () ; 

* . text() 
When this method is used to retrieve the text from 
a jQuery selection, it returns the content from every 
element in the jQuery selection, along with the text 
from any descendants. 
 $ ( ' u l ') . text () ; 


# INSERTING ELEMENTS 

Inserting new elements involves two steps: 
1: Create the new elements in a jQuery object 
2: Use a method to insert the content into the page 

.before() 
This method inserts content before the selected element(s) . 
.prepend() 
This method inserts content inside the selected element(s), after the opening tag. 
.after() 
This method inserts content after the selected element(s). 
.append() 
This method inserts content inside the selected element(s), before the closing tag. 


# GETTING AND SETTING ATTRIBUTE VALUES

You can work with any attribute on any element using the attr() and r emoveAttr() methods. 

The value of the cl ass attribute can hold more than one class name (each separated by a 
space). The addCl ass() and removeCl ass() methods are very powerful because they let you add or remove an individual class name within the value of the cl ass attribute (and they do not affect any other class names). 


* The . css () method lets you retrieve and set the values of CSS properties.

# EVENT METHODS 
The • on () method is used to handle all events. Behind the scenes, jQuery handles all of the cross-browser issues you saw in the last chapter. 

****************************************************************
# pair programming

pair programming commonly involves two roles: the Driver and the Navigator.

* **The Driver** is the programmer who is typing and the only one whose hands are on the keyboard manages the text editor, switching files, version control, and—of course writing—code
* **The Navigator** uses their words to guide the Driver but does not provide any direct input to the computer thinks about the big picture, what comes next, how an algorithm might be converted in to code 

- Pair programming touches on all four skills: developers explain out loud what the code should do, listen to others’ guidance, read code that others have written, and write code themselves.

1. Greater efficiency
pair programming takes a lot longer and is less efficient. In reality, when two people focus on the same code base, it is easier to catch mistakes in the making. Research indicates that pair programing takes slightly longer, but produces higher-quality code 

2. Engaged collaboration
When two programmers focus on the same code, the experience is more engaging and both programmers are more focused than if they were working alone.Another important aspect of learning to program is knowing when to ask for help

3. Learning from fellow students

4. Social skills
Pair programming is great for improving social skills. When working with someone who has a different coding style, communication is key. This can become more difficult when two programmers have different personalities. Pair programming not only improves programming skills, but can also help programmers develop their interpersonal skills.


5. Job interview readiness
A common step in many interview processes involves pair programming between a current employee and an applicant, either in person or through a shared screen. They will carry out exercises together, such as code challenges, building a project or feature, or debugging an existing code base. By doing so, companies can get a better feel for how an applicant will fit into the team and their collaboration style.

6. Work environment readiness
Many companies that utilize pair programing expect to train fresh hires from CS-degree programs on how they operate to actually deliver a product. Code Fellows graduates who are already familiar with how pairing works can hit the ground running at a new job, with one less hurdle to overcome.



 

