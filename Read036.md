# Reading: Application State with Redux

## Review, Research, and Discussion

- What are the advantages of storing tokens in “Cookies” vs “Local Storage”
Cookies are automatically saved, sent and removed by the browser. When doing browser level navigation, only cookies are sent. Sharing the same session across subdomains can easily be done with cookies. Cookies have a special flag called httpOnly, which means that malicious JS code cannot send the access token to the attacker.

- Explain 3rd party cookies.
Third party cookies are cookies that are set by a website other than the only you are currently on. For example, a "Like" button on a website which will store a cookie on a visitor's computer, that cookie can later be accessed by Facebook to identify visitors and see which websites were visited. Such a cookie is considered to be a 3rd party cookie.

- How do pixel tags work?
Pixel tags are typically single pixel, transparent GIF images that are added to a web page. Even though the pixel tag is virtually invisible, it is still served just like any other image you may see online.

## Term

***cookies*** Cookies, a mechanism for persisting data locally in a browser, can be incorporated into your React project in a matter of minutes. If you have React Router 4 and React Redux installed, some extra prop management is required to get your cookie object arriving at the correct Components.

***authorization*** Process of giving someone the ability to access a resource

***access control***  is a fundamental component of data security that dictates who’s allowed to access and use company information and resources. Through authentication and authorization, access control policies make sure users are who they say they are and that they have appropriate access to company data.

***conditional rendering*** is a term to describe the ability to render different user interface (UI) markup if a condition is true or false. In React, it allows us to render different elements or components based on a condition. This concept is applied often in the following scenarios: Rendering external data from an API.

## Preparation Materials

- What is Redux ?

Redux is a pattern and library for managing and updating application state, using events called “actions”.

It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. On top of that, it provides a great developer experience

- Why Should I Use Redux?

Redux helps you manage “global” state - state that is needed across many parts of your application.

- When Should I Use Redux?

Redux helps you deal with shared state management, but like any tool, it has tradeoffs. There are more concepts to learn, and more code to write. It also adds some indirection to your code, and asks you to follow certain restrictions. It’s a trade-off between short term and long term productivity.

- Benefits of redux:

You have large amounts of application state that are needed in many places in the app

The app state is updated frequently over time

The logic to update that state may be complex

The app has a medium or large-sized codebase, and might be worked on by many people

- Redux state

It is a self-contained app with the following parts:

The state, the source of truth that drives our app

The view, a declarative description of the UI based on the current state

The actions, the events that occur in the app based on user input, and trigger updates in the state
