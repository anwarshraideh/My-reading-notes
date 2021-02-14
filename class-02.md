You should write comments to explain what your code does.They help make your code easier to read and understand.

MULTI-LINE comments 
starting with the /* characters and ending with the */ characters.

SINGLE-LINE comments
anything that follows the two forward slash characters // on that line will not be processed by the JavaScript interpreter

A script will have to temporarily store the bits of information it needs to do its job. It can store this data in variables.

the data stored in a variable can change (or vary) each time a script runs.  


to declare the variable we type and assign it a value:
var price = 5;

DATA TYPES :

NUMERIC DATA TYPE 0.75
STRING DATA TYPE 'Hi'
BOOLEAN DATA TYPE true 


ARRAYS
An array is a special type of variable. It doesn't just store one value; it stores a list of values. 
You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of
the array).The values are assigned to the array inside a pair of square brackets, and each value is separated by a comma. The
values in the array do not need to be the same data type, so you can store a string, a number and a Boolean all in the same array.
var colors; 
colors= ['white','black','custom'];

Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).

Expressions evaluate into a single value.
Expressions rely on operators to calculate a value. 
An expression evaluates into (results in) a single value. Broadly speaking there are two types of expressions.  
EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE
EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE 

A switch statement starts with a variable called the switch value.Each case indicates a possible value for this variable and the
code that should run if the variable matches that value. 

You have a default option that is run if none of the cases match.
• If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing
better performance than multiple if statements).

********************************************************************************
headings

HTML has six "levels" of headings: 
(<h1>This is a Main Heading</h1>)
(<h2>This is a Level 2 Heading</h2>)
(<h3>This is a Level 3 Heading</h3>)
(<h4>This is a Level 4 Heading</h4>)
(<h5>This is a Level 5 Heading</h5>)
(<h6>This is a Level 6 Heading</h6>)

To create a paragraph, surround the words that make up the paragraph with an opening <p> tag and closing </p> tag.
By enclosing words in the tags (<b> )and (</b>) we can make characters appear bold.

By enclosing words in the tags (<i>) and (</i>) we can make characters appear italic.


The (<sup>) element is used to contain characters that should be superscript such as the suffixes of dates or mathematical concepts like
raising a number to a power .

The (<sub>) element is used to contain characters that should be subscript. It is commonly used with foot notes or chemical
formulas .

if you wanted to add a line break inside the middle of a paragraph you can use the line break tag (<br />).

To create a break between themes — such as a change of topic in a book or a new scene in a play — you can add a
horizontal rule between sections using the (<hr />) tag

There are some text elements that are not intended to affect the structure of your web pages, but they do add extra information to the
pages — they are known as semantic markup.


browsers will show the contents of a (<strong>) element in bold.
browsers will show the contents of an (<em>) element in italic

The (<q>) element is used for shorter quotes that sit within a paragraph
If you use an abbreviation or an acronym, then the (<abbr>) element can be used. A title attribute on the opening tag is used to specify the full term.
When you are referencing a piece of work such as a book, film or research paper, the (<cite>) element can be used to indicate where the citation is from.

The (<dfn>) element is used to indicate the defining instance of a new term.
The (<address>) element has quite a specific use: to contain contact details for the author of the page.
The (<ins>) element can be used to show content that has been inserted into a document, while
the (<del>) element can show text that has been deleted from it.

The (<s>) element indicates something that is no longer accurate or relevant (but that should not be deleted).

****************************************************************************************************************

CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.

CSS declarations sit inside curly brackets and each is made up of two parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.

The (<link>) element can be used in an HTML document to tell the browser where to find the CSS file used to style the page 
href This specifies the path to the CSS file .
type This attribute specifies the type of document being linked to
rel This specifies the relationship between the HTML page and the file it is linked to. The value should be stylesheet when
linking to a CSS file.

(<style>) You can also include CSS rules within an HTML page by placing them inside a (<style>) element, which usually sits inside the
(<head>) element of the page. 

Rules are made up of selectors (that specify the elements the rule applies to) and declarations (that indicate what these elements should look like).
X Different types of selectors allow you to target your rules at different elements.

