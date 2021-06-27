# Reading - Custom Hooks

## Review, Research, and Discussion

1 What does a component’s lifecycle refer to?
Lifecycle of a component is series of methods that are invoked in different stages of the component's existence. Lifecycle methods give ways to interact with component logic before/during/after being used in the DOM. 

2 Why do you sometimes need to “wrap” functions in useCallback when called from within useEffect 
useCallback will help in avoiding regeneration of functions when the functional component re-renders. However there isn't much of a performance difference caused by recreation of functions. You are specifying a function as a dependency to useEffect .

3 Why are functional components preferred over class components?
Less code, easy to read and test. 


4 What is wrong with the following code?
useEffect() cannot be called inside a loop



## Term

1 state hook : useState(), similar to this.setState() in a class except it doesn't merge the old and new state together. The only argument to useState() is the initial state. Allows us to add a state powered variable to our application


2 effect hook : he Effect Hook lets you perform side effects in function components:

3 reducer hook : used to store and update states, just like the useState Hook. It accepts a reducer function as its first parameter and the initial state as the second.



## Custom Hooks React
A custom hook allows you to extract some components logic into a reusable function. A custom hook is a Javascript function that starts with use and that call can other hooks. ... We are just refactoring our code into another function to make it reusable.

## Using a Custom Hook
In the beginning, our stated goal was to remove the duplicated logic from the FriendStatus and FriendListItem components. Both of them want to know whether a friend is online.

## useToggle
Basically, what this hook does is that, it takes a parameter with value true or false and toggles that value to opposite. It's useful when we want to take some action into it's opposite action.

## useAuth
A very common scenario is you have a bunch of components that need to render different depending on whether the current user is logged in and sometimes call authentication methods like signin, signout, sendPasswordResetEmail, etc.

## Rules of Hooks
Only Call Hooks at the Top Level.
Only Call Hooks from React Functions.
Don’t call Hooks from regular JavaScript functions.

