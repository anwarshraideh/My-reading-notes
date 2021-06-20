# Reading: Props and State

## Review

1- Does a deployed React application require a server?
No you don't need a server ,  It also works well when integrated into an existing server side app.

2- Why do we prefer to test a React application at the behavior rather than the unit level?
When it comes to React components you want to check how your component is rendered and if all props you pass to the component influence the behavior of your component as expected.

3- What does npm run build do?
When you're ready to deploy to production, running npm run build will create an optimized build of your app in the build folder

4- Describe the actual composition / architecture of a React application .
Components are often described as “just functions” but in our view they need to be more than that to be useful. In React, components describe any composable behavior, and this includes rendering, lifecycle, and state. Some external libraries like Relay augment components with other responsibilities such as describing data dependencies. It is possible that those ideas might make it back into React too in some form.



## Term

***BDD*** Behavior-driven development is an extension of test-driven development: development that makes use of a simple, domain-specific scripting language (DSL). These DSLs convert structured natural language statements into executable tests. The result is a closer relationship to acceptance criteria for a given function and the tests used to validate that functionality. As such it is a natural extension of TDD testing in general.
***Acceptance Tests*** testing technique performed to determine whether or not the software system has met the requirement specifications, the main purpose is to evaluate the system's compliance with the business requirements and verify if it is has met the required criteria for delivery to end users. Forms of accpetance testing: user acceptance testing, business acceptance testing, alpha testing, beta testing.

***mounting***  is the process of outputting the virtual representation of a component into the final UI representation (e.g. DOM or Native Components). In a browser that would mean outputting a React Element into an actual DOM element (e.g. an HTML div or li element) in the DOM tree. In a native application that would mean outputting a React element into a native component.

***build***  the process of converting source code into an “executable” bundle by the browser.


## Preparation Materials


## setState

- setState React components with state render UI based on that state. When the state of components changes, so does the component UI. setState() is the only way to update state after the initial state setup.
- Update to a component state should be done using setState() also you can pass an object or a function to setState() .


## Handling Events

Handling events with React elements is very similar to handling events on DOM elements.
There are some syntax differences: React events are named using camelCase rather than just lowercase, and with JSX you pass a function as the event handler rather than a string

## Forms
Forms Handling forms is about how you handle the data when it changes value or gets submitted.
In HTML, form data is usually handled by the DOM.
In React, form data is usually handled by the components.
When the data is handled by the components, all the data is stored in the component state.
You can control changes by adding event handlers in the onChange attribute

## State
The state is an updatable structure that is used to contain data or information about the component and can change over time. The change in state can happen as a response to user action or system event. It is the heart of the react component which determines the behavior of the component and how it will render. A state must be kept as simple as possible. It represents the component's local state or information. It can only be accessed or modified inside the component or by the component directly.

## Props
Props are read-only components. It is an object which stores the value of attributes of a tag and work similar to the HTML attributes. It allows passing data from one component to other components. It is similar to function arguments and can be passed to the component the same way as arguments passed in a function. Props are immutable so we cannot modify the props from inside the component.

## Testing Basically, React Testing Library (RTL)
 is made of simple and complete React DOM testing utilities that encourage good testing practices So rather than dealing with instances of rendered React components, your tests will work with actual DOM nodes. The utilities this library provides facilitate querying the DOM in the same way the user would. Finding form elements by their label text (just like a user would), finding links and buttons from their text (like a user would). It also exposes a recommended way to find elements by a data-testid as an "escape hatch" for elements where the text content and label do not make sense or is not practical.

 