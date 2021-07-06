# Readings: Redux - Additional Topics

## Review, Research, and Discussion

- What’s the best practice for “pre-loading” data into the store (on application start) in a Redux application?

The most 'redux-like' way of handling the pre-loading of data would be to fire off the asynchronous action in the lifecycle method (probably componentWillMount ) of a Higher Order Component that wraps your app.

- When using a thunk/async action that dispatches the actual action, which do you export from your reducer?
You export the actual action from the reducer.



## Term

- middleware : middleware provides a third-party extension point between the when an action is dispatched and the moment it reaches the reducer. It needs to be used for asynchronous calls with Redux.
- thunk : Function that wraps an expression to delay its evaluation



## Preparation Materials

## Redux Toolkit

- What is Redux Toolkit?

Redux Toolkit is our official, opinionated, batteries-included toolset for efficient Redux development. It is intended to be the standard way to write Redux logic, and we strongly recommend that you use it.

- Redux Toolkit was originally created to help address three common concerns about Redux:
"Configuring a Redux store is too complicated"
"I have to add a lot of packages to get Redux to do anything useful"
"Redux requires too much boilerplate code"
