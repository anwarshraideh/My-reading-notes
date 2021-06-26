# Reading: Hooks API


## Review, Research, and Discussion

- Why do we not need more .html pages in a multi-page React app?

Because of react-route-dom library, which will allow us to have multiple routes and on each route we can render component.

- If we wanted a component to show up on every page, where would we put it and why?
Inside the <BrowserRouter />, outside a <Route /> -> this will allow it to render on all pages regardless of a specified route. Although from this article it also looks like putting it outside of the <BrowserRouter /> all together might work as well to render to every page, if it is setup properly.

- What does props.children contain?
used to display whatever you include between the opening and closing tags when invoking a component.



## Term

***Composition*** React Composition is a development pattern based on React's original component model where we build components from other components using explicit defined props or the implicit children prop.
***Children / Child Components*** components that are nested within a parent React component (button within a form for example), within the parent components JSX tags React docs
***Hash Routing*** Hash value will be handled by react router. It is used to support legacy browsers which usually doesn't support HTML pushState API, It doesn't need any configuration in server to handle routes, This route isn't recommended by the team who created react router package.
***Link Routing*** Provides declarative, accessible navigation around the application


## Preparation Materials

Hooks: Hooks are the new feature introduced in the React 16.8 version. It allows you to use state and other React features without writing a class. Hooks are the functions which "hook into" React state and lifecycle features from function components. It does not work inside classes.

Hooks are backward-compatible, which means it does not contain any breaking changes. Also, it does not replace your knowledge of React concepts.

If you write a function component, and then you want to add some state to it, previously you do this by converting it to a class. But, now you can do it by using a Hook inside the existing function component.

Rules of Hooks:

Only call Hooks at the top level.
Only call Hooks from React functions.
Pre-requisites for React Hooks

Node version 6 or above
NPM version 5.2 or above
We need hooks when we can't break a complex UI to the first level.

Hooks apply the React philosophy (explicit data flow and composition) inside a component, rather than just between the components.

useState is a Hook (we’ll talk about what this means in a moment)

The only argument to useState is the initial state.The initial state argument is only used during the first render.

useState return a pair of values: the current state and a function that updates it.

useEffect do tell React that your component needs to do something after render. React will remember the function you passed (we’ll refer to it as our “effect”), and call it later after performing the DOM updates. In this effect, we set the document title, but we could also perform data fetching or call some other imperative API.

We use useEffect after every render. 

