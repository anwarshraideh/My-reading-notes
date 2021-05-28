# Readings: Event Driven Applications


## Review

# Why is access control important?
Access control is important because it is a valuable security technique that can be used to regulate who or what can view or use any given resource.

# What is a role used for?
Role-based access control (RBAC) is a method of restricting network access based on the roles of individual users within an enterprise. RBAC lets employees have access rights only to the information they need to do their jobs and prevents them from accessing information that doesn't pertain to them.

# Why is role based access control more scalable than discretionary or mandatory access control?
Unlike Mandatory Access Control (MAC) where access to system resources is controlled by the operating system (under the control of a system administrator), Discretionary Access Control (DAC) allows each user to control access to their own data.



## Vocabulary Terms

- Authorization : : Authorization is a security mechanism to determine access levels or user/client privileges related to system resources including files, services, computer programs, data and application features
- Role Based Access Control : Role-based access control (RBAC) is a method of restricting network access based on the roles of individual users within an enterprise. RBAC lets employees have access rights only to the information they need to do their jobs and prevents them from accessing information that doesn't pertain to them.
- Capabilities : the ability to perform or achive certain actions or outcomes 


## Preparation Materials :

Event-Driven Programming is a logical pattern that we can choose to confine our programming within to avoid issues of complexity and collision
- An Event Handler is a callback function that will be called when an event is triggered.
- A Main Loop listens for event triggers and calls the associated event handler for that event.
- When the EventEmitter object emits an event, all of the functions attached to that specific event are called synchronously. Any values returned by the called listeners are ignored and discarded.
- Much of the Node.js core API is built around an idiomatic asynchronous event-driven architecture in which certain kinds of objects (called "emitters") emit named events that cause Function objects ("listeners") to be called.

- For instance: a net.Server object emits an event each time a peer connects to it; a fs.ReadStream emits an event when the file is opened; a stream emits an event whenever data is available to be read.

- All objects that emit events are instances of the EventEmitter class. These objects expose an eventEmitter.on() function that allows one or more functions to be attached to named events emitted by the object. Typically, event names are camel-cased strings but any valid JavaScript property key can be used.

