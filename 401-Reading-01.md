# Reading Notes #
## Node Ecosystem, TDD, CI/CD ##

1.	Describe (in plain English) what Array.map() 
It makes new array by calling a specific function on each element provided in the parent array. 

2.	Describe (in plain English) what Array.reduce() 
It reduces whatever function it was called for each value of the array to a reduced or single value. 
3.	Provide code snippets showing how to use superagent() to fetch data from a URL and log the result

# Superagent.get(url).then(happyHome) {
  Const homePrice = happyHome.body;
  Const homeData = homePrice.data.map(happyHome => new Home(happyHome);
  Response.send(homeData);

# With normal Promise .then() syntax

- Const promise2 = new Promise((resolve, reject) => {
  Resolve(‘Success’);
  });
  Promise2.then((value) => {
  Console.log(value);
  //expected output: “Yes!”
  });


# Again with async / await syntax

Async function hello ( ) {
return greeting = await Promise.resolve(‘Hello”);
};
Hello ( ).then(alert); 

4.	Explain promises as though you were mentoring a Code 301 level student
- Promise is just like in real life it promises to do something. Promise is an object and there are 3 states of the Promise object.
Pending:- initial state, before the promise succeeds or fails
Resolved:- Completed Promise
Rejected :- Failed Promise
 

5.	Are all callback functions considered to be Asynchronous? Why or Why Not?
- The short answer will be yes, but there is a catch to it. Every asynchronous function takes a function argument, but not every function that does so is asynchronous. It matters how the argument is used inside the function. 


# References:
https://bytearcher.com/
https://www.freecodecamp.org/news/javascript-es6-promises-for-beginners-resolve-reject-and-chaining-explained/
https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous/Async_await
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise/then

