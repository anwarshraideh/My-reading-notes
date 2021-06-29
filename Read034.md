# Reading: <Login /> and <Auth />

## Review, Research, and Discussion
- Why is the Context API useful?

Context API is useful because it can help to make information globally available in the app rather than having to pass it in props to each individual child element.

- Can a component outside of a provider get its context?
Yes, any component inside the app can get the context as long as it is passed properly and imported at the top of the target page.


- What are some common use cases for using the Context API?
Needing to pass functions that need to be available in mutiple places.


- Describe “Context Hell”
When using the context API, splitting global state properties so as not to share a “god object” creates “Context hell,” a layer of countless contexts wrapping your React application




# Term

- global state state that is accessible at the top level of the app and passed via props
- global context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language. For example, in the code below we manually thread through a “theme” prop in order to style the Button component: class App extends React
- provider React uses provider pattern in Context API to share data across tree descendants
- consumer A consumer is where the stored information ends up. It can request data via the provider and manipulate the central store if the provider allows it.


# Preparation Materials

Role-based access control (RBAC): restricts network access based on a person’s role within an organization and has become one of the main methods for advanced access control. The roles in RBAC refer to the levels of access that employees have to the network.

Benefits of RBAC:

Reducing administrative work and IT support.
Maximizing operational efficiency.
Improving compliance.

React-cookie library: it's a Javascript object with all your cookies. The key is the cookie name.

react-cookies component
React's way of using and saving cookies

