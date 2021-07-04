# Readings: Redux - Combined Reducers

## Review, Research, and Discussion

- Why choose Redux instead of the Context API for global state?
Redux is the industry standard for managing state of large applications, so it is important to know well. It is more optimized for larger projects, because the context API re-renders more often.

- What is the purpose of a reducer?
Buffer that sits and protects the application state, changes to state by the components have to be passed through the reducer and have to play by the reducers rules. Reducer is a function that runs every time state needs to be updated, and always returns the new state of the application.


- What does an action contain?
An action contains a type and whatever payload you want it to have.


- Why do we need to copy the state in a reducer?
Reducers are not allowed to modify the existing state, instead they must make immutable updates by copying the existing state and making changes to the copied values

## Term

- immutable state : State cannot be modified, reducers must make copies of existing state to make updates.
- time travel in redux : The Redux DevTools records dispatched actions and the state of the Redux store at every point in time. This makes it possible to inspect the state and travel back in time to a previous application state without reloading the page or restarting the app

- action creator is merely a function that returns an action object. Redux includes a utility function called bindActionCreators for binding one or more action creators to the store’s dispatch() function.
- reducer :  Functions that take current state and an action as arguments, and return a new state result, (state, action) => newState. (source: Redux docs
- dispatch : Dispatch is the act of sending something somewhere. In computer science, this term is used to indicate the same concept in different contexts, like to dispatch a call to a function, dispatch an event to a listener, dispatch an interrupt to a handler or dispatch a process to the CPU.




## Preparation Materials

## Multiple Reducers Example
import {combineReducers, createStore } from 'redux';
Example reducer: const userReducer = (state={}, action) => { return state };
Example combineReducer example: const reducers = combineReducers({user: userReducer, tweets: tweetReducer})

## Redux Docs: Using Combined Reducers
Takes an object of reducer functions and returns a new reducer function
createStore function takes preloadedState as a second argument


## Redux Docs: Combined Reducer Syntax
Reducers passed to combineReducers must satisfy the following:
any action that is not recognized, must return state that was given as first argument
must never return undefined
if state given to it is undefined, must return initial state for the specific reducer
