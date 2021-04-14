# Reading note 16

1.	What’s the difference between a FIFO and a standard queue?
- FIFO queues have essentially the same features as standard queues, but provide the added benefits of supporting ordering and exactly-once processing. FIFO queues provide additional features that help prevent unintentional duplicates from being sent by message producers or from being received by message consumers.

2.	How can the server be assured a message was properly received?
- when the server has received a request header, and then receives an empty line, and if the request was a GET (which has no payload), it knows the request is complete and can move on to dealing with forming a response. In other cases, it can move on to reading Content-Length worth of payload and act accordingly.

3.	What classic design pattern is best represented by event driven programming?
4.	How do you test an event driven system?
- There are multiple levels of tests you will typically write for your system. In the most canonical case, you will write unit tests, service tests, and end-to-end tests. In each of these cases, your System Under Test (SUT, what is actually being tested) comprises a different part of your application.

- Document the following Vocabulary Terms

- FIFO Queue – in fifi queue messages are grouped into “Message groups” and all messages within a message group are sent and received in strict order.

- Pub/Sub – in Pub/Sub service and sends messages to the topic. A message contains a payload and optional attributes that describe the payload content. The service ensures that published messages are retained on behalf of subscriptions.

# references 
https://www.google.com/
https://dictionary.cambridge.org/us/dictionary/english/queue
https://www.geeksforgeeks.org/
https://www.codesdope.com 