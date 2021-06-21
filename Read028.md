# Readings: Component Composition


## Review, Research, and Discussion

1- Can a parent component access the state of a child component? 
In React we can access the child's state using Refs. we will assign a Refs for the child component in the parent component. then using Refs we can access the child's state.

2- What can be passed along in a prop variable?

props enable you to pass variables from one to another component down the component tree. Any information, function, JavaScript that needs to be passed down.

3- How can a child component “know” the state of another component?
To obtain the state of another component, you can pass the component's state to it's child components as props. You can also have components share a common ancestor, and have them access the same state in a similar manner


## Term

***component props*** Keyword in React for properties, can be any information, function, JavaScript that needs to be passed to another component. Can only be passed in one direction, from the root to its children, no way for data to be passed up.

***component state*** The state is an instance of React Component Class can be defined as an object of a set of observable properties that control the behavior of the component. In other words, the State of a component is an object that holds some information that may change over the lifetime of the component.

***application state*** In an application, state is interface between data (from backend or local change) and the representation of this data with UI elements on the front-end. State is able to keep the data of different components in sync because each state update will rerender all relevant components. State can be a medium to communicate between different components as well

## Preparation Materials

### React Recap

Component Lifecycle A component can only be in one stage at a time. It starts with mounting and moves onto updating. It stays updating perpetually until it gets removed from the virtual DOM. Then it goes into the unmounting phase and gets removed from the DOM.

The lifecycle methods allow us to run code at specific points in the component’s life or in response to changes in the component’s life.

Update This phase is triggered every time state or props change. Like in mounting, getDerivedStateFromProps is called (but no constructor this time!).

Unmounting Our component lived a good life, but all good things must come to an end. The unmounting phase is that last stage of the component lifecycle. When you remove a component from the DOM, React runs componentWillUnmount right before it gets removed. You should use this method to clean up any open connections such as WebSockets or intervals


### props.children

Props Children It's recommended that you pass all element inside the component as props.children
a special prop, automatically passed to every component, that can be used to render the content included between the opening and closing tags when invoking a component

### composition vs inheritance

Inheritance

Those familiar with Object Oriented Programming are well aware of Inheritance and use it on a regular basis. When a child class derives properties from it’s parent class, we call it inheritance. There are variety of use-cases where inheritance can be useful.

Composition

Composition is also a familiar concept in Object Oriented Programming. Instead of inheriting properties from a base class, it describes a class that can reference one or more objects of another class as instances.


