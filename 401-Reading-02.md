# Reading Notes 2 #
1)	The main difference between the PUT and PATCH method is that the PUT method uses the request URI to supply a modified version of the requested resource which replaces the original version of the resource, whereas the PATCH method supplies a set of instructions to modify the resource.

2)	Provide links to 3 services or tools that allow you to “mock” an API for development like json-server. 

-	To mock an API call in a function, you just need to do these 3 steps:

•	Import the module you want to mock into your test file.
•	jest. mock() the module.
•	Use . mockResolvedValue(<mocked response>) to mock the response. That's it! 

-	Postman is a popular API client that makes it easy for developers to create, share, test and document APIs. This is done by allowing users to create and save simple and complex HTTP/s requests, as well as read their responses. The result - more efficient and less tedious work.

-	Swagger is an API testing tool that allows users to start their functional, security, and performance testing right from the Open API Specifications. Swagger tooling and Ready API platform make it easy to quickly create, manage, and execute API tests in the pipeline.
3)	Compare and contrast Swagger and APIDoc.js which HTTP status should be sent with each type of (un)successful API call?

Here is my finding regarding both:


•	Popularity: By comparing stats,  swagger-ui is more popular then apidocjs.
•	Consistency: If we already using swagger for our Dotnetcore service, then implementing swagger tool will consist more from Info and UI prospective.
•	Implementation complexity: apidocjs and swagger both required documentation content on implemented method as customize comment data. In addition they allow to write documentation data in separate resource file as .js and .json. If we already have swagger.json created by DotnetCore we can reuse more than 80% specification.
•	 Maintenance: For apidocjs will have to modify documentation for each affected method/endpoints if service changed. In swagger we can limit changes. But by implementing apidocjs we can isolate the layer.
•	Other benefits: Because swagger use plain .json that could be parsed through programing language, thus we can get advantage of various other 3rd parties in order to create http client and more. 
•	Future: Due to popularity of swagger, apidocjs provide information about apidoc-swagger converter so we can switch apidoc to swagger anytime.


4)	Compare and contrast SOAP and ReST
-	SOAP is a protocol, and REST is an architectural style. A REST API can actually utilize the SOAP protocol, just like it can use HTTP. So, right off the bat, they’re going to be packaged differently, function differently, and be used in different scenarios.
- Some quick REST and SOAP information:
•	REST is all about simplicity, thanks to HTTP protocols.
•	REST APIs facilitate client-server communications and architectures. If it’s RESTful, it’s built on this client-server principle, with round trips between the two passing payloads of information.
•	REST APIs use a single uniform interface. This simplifies how applications interact with the API by requiring they all interface in the same way, through the same portal. This has advantages and disadvantages; check with your developer to see if this will affect implementation changes down the road.
•	REST is optimized for the web. Using JSON as its data format makes it compatible with browsers.
•	REST is known for excellent performance and scalability. But, like any technology, it can get bogged down or bog down your app. That’s why languages like GraphQL have come along to address problems even REST can’t solve.

•	SOAP has tighter security. WS-Security, in addition to SSL support, is a built-in standard that gives SOAP some more enterprise-level security features, if you have a requirement for them.
•	Successful/retry logic for reliable messaging functionality. Rest doesn’t have a standard messaging system and can only address communication failures by retrying. SOAP has successful/retry logic built in and provides end-to-end reliability even through SOAP intermediaries.
•	SOAP has built-in ACID compliance. ACID compliance reduces anomalies and protects the integrity of a database by prescribing exactly how transactions can interact with the database. ACID is more conservative than other data consistency models, which is why it’s typically favored when handling financial or otherwise sensitive transactions.

## Vocabulary Terms
- Web Server:- A web server is server software, or a system of one or more computers dedicated to running this software, that can satisfy client HTTP requests on the public World Wide Web or also on private LANs and WANs.

- Express:- is a back end web application framework for Node. js, released as free and open-source software under the MIT License. It is designed for building web applications and APIs. It has been called the de facto standard server framework for Node.

- Routing:- is a way of organizing and managing application states. Its framework in JavaScript helps you to change the state of the application--perhaps moving from one admin panel section to another--while maintaining application persistence.

## Preparation Materials 
1.	Which 3 things had you heard about previously and now have better clarity on?
•	NPM
•	EXPRESS
•	PUT
2.	Which 3 things are you hoping to learn more about in the upcoming lecture/demo?
•	Module.exports
•	Query string
•	Request method
3.	What are you most excited about trying to implement or see how it works?
I’m excited to see what we learned in lectures come together once we build the app.  



# Reading Note 2 Reference
https://www.postman.com/
https://www.asptricks.net/2019/04/apidoc-vs-swagger-for-node-app.html
https://www.upwork.com/resources/soap-vs-rest-a-look-at-two-different-api-styles?gclid=Cj0KCQiA7NKBBhDBARIsAHbXCB7riMUgcPu8ca6GAPco383-yzXNObiSvG-h1edK58E5CzPR1M4EoAoaAuJGEALw_wcB
https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/Introduction
