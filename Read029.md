# Readings: Routing

## Review, Research, and Discussion

1- Do child components have direct access to props/state from the parent?

Child components have access to state from the parent (this.state) when in a class, and have access to props as a functional component.

2- When a component “wraps” another component, how does the child component’s output get rendered?
when adding the component as children.

3- Can a component, such as <Content />, which is a child also be used as a standalone component elsewhere in the application?
Yes it can be used in another case that the hole idea of usability.

4- What trick can a parent use to share all props with it’s children.
The parent can pass them directly to all children or pass a function to them to share all the states and props.


## Term

***props.children***can be used on components that represent generic boxes and don't know their children ahead of time (per React docs). It can be used to display whatever you include between the opening and closing tags when invoking a component
***composition***  a development pattern based on React’s original component model where we build components from other components using explicit defined props or the implicit children prop.

## Preparation Materials

### React Routing
React Routing is a package you need to install to use it. For our purpose of use we gonna use the < BrowserRouter > and < HashRouter > The < BrowserRouter > should be used when you have a server that will handle dynamic requests (knows how to respond to any possible URI), while the < HashRouter > should be used for static websites (where the server can only respond to requests for files that it knows about).

Usually it is preferable to use a < BrowserRouter >, but if your website will be hosted on a server that only serves static files, then the < HashRouter > is a good solution.

## React If

    function SomeComponent({condition}) {
     return <div>
    { condition ? <span>Yes it is true!</span> : null }
    </div>
    }

### Types of Queries:

- Single Elements

getBy...: Returns the matching node for a query, and throw a descriptive error if no elements match or if more than one match is found (use getAllBy instead if more than one element is expected).

queryBy...: Returns the matching node for a query, and return null if no elements match. This is useful for asserting an element that is not present. Throws an error if more than one match is found (use queryAllBy instead if this is OK).

findBy...: Returns a Promise which resolves when an element is found which matches the given query. The promise is rejected if no element is found or if more than one element is found after a default timeout of 1000ms. If you need to find more than one element, use findAllBy.

- Multiple Elements

getAllBy...: Returns an array of all matching nodes for a query, and throws an error if no elements match.

queryAllBy...: Returns an array of all matching nodes for a query, and return an empty array ([]) if no elements match.

findAllBy...: Returns a promise which resolves to an array of elements when any elements are found which match the given query. The promise is rejected if no elements are found after a default timeout of 1000ms.


