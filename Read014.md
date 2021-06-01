
# Readings: Event Driven Architecture



# Review, Research, and Discussion

- What’s the difference between a FIFO and a standard queue?
FIFO queues is the same as standard queues, but it supports ordering and exactly-once processing and ensure the order in which messages are sent and received is strictly preserved.

- How can the server be assured a message was properly received?
The most common approach is to use a hash function that combines all the bytes in the message with a secret key and produces a message digest that is difficult to reverse

- What classic design pattern is best represented by event driven programming?
The observer pattern is a software design pattern in which an object, named the subject, maintains a list of its dependents, called observers, and notifies them automatically of any state changes, usually by calling one of their methods. It is mainly used for implementing distributed event handlingsystems, in "event driven" software.

- How do you test an event driven system?
 There are multiple levels of tests you will typically write for your system. In the most canonical case, you will write unit tests, service tests, and end-to-end tests. In each of these cases, your System Under Test (SUT, what is actually being tested) comprises a different part of your application.



# Vocabulary Terms

- FIFO Queue : a queue works based on the first-in, first-out (FIFO) principle. ... The enqueue operation inserts an element at the end of the queue, whereas the dequeue operation removes an element from the front of a queue
- Pub/Sub : is an asynchronous messaging service that decouples services that produce events from services


# Preparation Materials

- AWS: Cloud computing gives you access to servers, storage, databases, and a broad set of application services over the Internet. A cloud services provider such as Amazon Web Services, owns and maintains the network-connected hardware required for these application services, while you provision and use what you need via a web application.

- AWS Elastic Beanstalk: AWS Elastic Beanstalk is an easy-to-use service for deploying and scaling web applications and services developed

