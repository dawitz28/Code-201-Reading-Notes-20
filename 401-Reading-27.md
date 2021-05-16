# Reading Note 27

- Does a deployed React application require a server?
React application doesn’t require to server to deploy it builds the virtual DOM and does its diff operations on the client’s browser. In this way it is also cost sufficient. 

- Why do we prefer to test a React application at the behavior rather than the unit level?
This seems like a personal preference and I think we use them as a combined for the best results as they complement each other very nicely. 

- What does npm run build do?
We run this command to create a “build” directory that uses “build tool” and able to merge all our CSS files into one file and the same thing to our JavaScript files. This way we minimize the number and size of files the user gets. 

- Describe the actual composition / architecture of a React application

## Vocabulary Terms

- BDD Behavior Driven Development is a software engineering process that stems from Test Driven Development (TDD) and Acceptance Test Driven. 
- Acceptance Tests is a level of software testing where a system is tested for acceptability. The purpose of this test is to evaluate the system’s compliance with the business requirements ad assess whether it is acceptable for delivery.
- Mounting is the phase in which our React component mounts on to DOM. This method is called just before a component mounts on the DOM or the render method is called. After this method, the component gets mounted.
- Build merges all your CSS files into one file and it does the same thing for JavaScript files as well so it’ll  be easier and to have less files when sending it off to your user. 


