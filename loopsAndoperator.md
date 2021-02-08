# Comparison Operators

Comparison operators are used in logical statements to determine equality or difference between variables or values the result will be true or false .

==	equal to
===	equal value and equal type
!=	not equal
!==	not equal value or not equal type
>	greater than
<	less than
>=	greater than or equal to
<=	less than or equal to


*************************************************

# Logical Operators

Logical operators are used to determine the logic between variables or values.

&&	and	(6 < 10 && 3> 1) is true	
||	or	(6 == 5 || 3 == 5) is false	
!	not	!(6 == 3) is true


*************************************************

# JavaScript Loops

Loops are handy, if you want to run the same code over and over again, each time with a different value .

## Kinds of Loops :
for - loops through a block of code a number of times
while - loops through a block of code while a specified condition is true

### The For Loop

The for loop has the following syntax

### Syntax 

for (statement 1; statement 2; statement 3) {
  // code block to be executed
}

Statement 1 is executed (one time) before the execution of the code block.

Statement 2 defines the condition for executing the code block.

Statement 3 is executed (every time) after the code block has been executed.

example :
for (i = 0; i < 5; i++) {
  text += "The number is " + i + "<br>";
}


### The While Loop

The while loop loops through a block of code as long as a specified condition is true

### Syntax 

while (condition) {
  // code block to be executed
}

example :

while (i < 10) {
  text += "The number is " + i;
  i++;
}


*************************************************


