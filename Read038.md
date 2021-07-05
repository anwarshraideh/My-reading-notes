# Readings: Redux - Asynchronous Actions

## Review, Research, and Discussion

- How granular should your reducers be?
There should be a separate reducer function for each slice of data. They are combined before being put into the store.
- Pro or Con – multiple reducers can “fire” when a commonly named action is dispatched
When your reducer has finished and returned the new application state, asyncDispatch will trigger store. dispatch with whatever action you give to it. You might try using a library like redux-saga.

- Name a strategy for preventing the above
Using Redux middleware thunk, allows for evaluating the actions.

## Term

- store : Holds the whole state tree of the application, only way to change the state inside is to dispatch an action on it.
- combined reducers : Helper function turns an object whose values are different reducing functions into a single reducing function you can pass to createStore.

## Preparation Materials

### async actions

Redux middleware enables writing logic with side effects
Redux Thunk middleware allows us to write functions that get dispatch and getState as arguments
$npm install redux-thunk
import thunkMiddleware from 'redux-thunk'
const composedEnhancer = composeWithDevTools(applyMiddleware(thunkMiddleware))

### thunk middleware
a Redux store doesn’t know anything about async logic. It only knows how to synchronously dispatch actions, update the state by calling the root reducer function, and notify the UI that something has changed. Any asynchronicity has to happen outside the store.
"The term originated as a humorous past-tense version of 'think'."
import { createStore, applyMiddleware } from 'redux';
