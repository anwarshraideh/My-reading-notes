# Reading: Component Based UI

## Review, Research, and Discussion

1- Name 5 Javascript UI Frameworks (other than React)

Angula , Vue , Ember , Svelte3 and Ext JS by Sencha.

2- What’s the difference between a framework and a library?

The key difference between a library and a framework is "Inversion of Control". When you call a method from a library, you are in control. But with a framework, the control is inverted: the framework calls you. Both of them define an API for programmers to use


## Term

***Rendering***  refers to showing the output in the browser.Javascript uses the document object model (DOM) to manipulate the DOM elements.

***Templates*** refers to the client side data binding method implemented with the JavaScript language. Popular JavaScript templating languages are: AngularJS, Backbone.js, Ember.js, Handlebars.js, and Mustache.js. The templating engine is responsible for connecting to the data model, processing the code specified in the source templates, and directing the output to a specific pipeline, text file, or stream.

***State*** The state is an instance of React Component Class can be defined as an object of a set of observable properties that control the behavior of the component. In other words, the State of a component is an object that holds some information that may change over the lifetime of the component.


## Preparation Materials

## JSX

JSX is a syntax extension to JavaScript, it produces React "elements" and React embraces the fact that rendering logic is inherently coupled with other UI logic: how events are handled, how the state changes over time, and how the data is prepared for display .
React separates concerns with loosely coupled units called "components" that contain both markup and logic
Can put any valid JavaScript expression inside the curly braces in JSX (2+2, user.firstName, or formatName(user) for example)
Can use JSX inside of if statements and for loops, assign it to variables, accept it as arguments and return it from functions and Use quotes to specify string literals as attributes also use curly braces to embed a JavaScript expression in an attribute
If a tag is empty, you can close it immediately with /> .
By default, React DOM escapes any values embedded in JSX before rendering them, thus it ensures that you can never inject anything that's not explicitly written in your application
Can think of React elements as descriptions of what you want to see on the screen, React reads these objects and uses them to construct the DOM and keep it up to date .

## Rendering Elements

Elements are the smallest building blocks of React apps, an element describes what you can see on the screen
Unlike browser DOM elements, React elements are plain objects, and are cheap to create .
React DOM takes care of updating the DOM to match the React elements
Applications built with just React usually have a single root DOM node .
If you are integrating React into an existing app, you may have as many isolated root DOM nodes as you'd like
React elements are immutable, once you create an element you can't change its children or its attributes
An element is like a single frame in a movie, it represents the UI at a certain point in time
React only updates what is necessary, React DOM compares the element and its children to the previous one and only applies the DOM updates necessary to bring the DOM to the desired state .


