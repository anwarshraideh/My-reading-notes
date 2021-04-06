# What is functional programming?

Functional programming is a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable data .

# how do we know if a function is pure or not? 

It returns the same result if given the same arguments (it is also referred as deterministic)
It does not cause any observable side effects

- Any function that relies on a random number generator cannot be pure.

## Pure functions benefits
The code’s definitely easier to test. We don’t need to mock anything.

## Immutability
Unchanging over time or unable to be changed.

* When data is immutable, its state cannot change after it’s created. If you want to change an immutable object, you can’t. Instead, you create a new object with the new value.


- toLowerCase: converts the string to all lower case
- trim: removes whitespace from both ends of a string
- split and join: replaces all instances of match with replacement in a given string

# Functions as first-class entities

The idea of functions as first-class entities is that functions are also treated as values and used as data.
Functions as first-class entities can:
refer to it from constants and variables
pass it as a parameter to other functions
return it as result from other functions
The idea is to treat functions as values and pass functions like data. This way we can combine different functions to create new functions with new behavior.

## Higher-order functions
When we talk about higher-order functions, we mean a function that either:
takes one or more functions as arguments, or
returns a function as its result
The doubleOperator function we implemented above is a higher-order function because it takes an operator function as an argument and uses it.
You’ve probably already heard about filter, map, and reduce. Let's take a look at these.

# Filter
Given a collection, we want to filter by an attribute. The filter function expects a true or false value to determine if the element should or should not be included in the result collection. Basically, if the callback expression is true, the filter function will include the element in the result collection. Otherwise, it will not.
A simple example is when we have a collection of integers and we want only the even numbers.
Imperative approach

# Reduce
The idea of reduce is to receive a function and a collection, and return a value created by combining the items.


* It's important to get your code right the first time because in many businesses there isn't much value in refactoring. Or at least, it's hard to convince stakeholders that eventually uncared for codebases will grind productivity to a halt
