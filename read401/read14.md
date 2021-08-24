## Event Driven Architecture


### 1. What’s the difference between a FIFO and a standard queue?
Standard queues provide at-least-once delivery, which means that each message is delivered at least once. FIFO queues provide exactly-once processing, which means that each message is delivered once and remains available until a consumer processes it and deletes it.

### 2. How can the server be assured a message was properly received?
it's add the message in queue and when the clinet recieve the message it will delete it.

### 3. How do you test an event driven system?
In an event-driven application architecture, the developer is going to have to do a lot more work. But this work can be reduced by creating an automation process that scaffolds up the unit testing environment. Once the process is automated, it can be shared with each developer in the team to meet their individual needs.


----------------------------------

### Terms: 

**FIFO Queue:**
A FIFO queue is a queue that operates on the first-in, first-out principle, hence the name. This is also referred to as the first-come, first-served principle.

(FCFS doesn’t roll off the tongue quite as nicely, though.)

In other words, FIFO queuing is when customers are served in the exact order in which they arrive.

FIFO is the most common type of queuing, and it’s generally believed to be the fairest way to manage queues.


**Pub/Sub:**
Pub/Sub allows services to communicate asynchronously, with latencies on the order of 100 milliseconds.

Pub/Sub is used for streaming analytics and data integration pipelines to ingest and distribute data. It is equally effective as messaging-oriented middleware for service integration or as a queue to parallelize tasks.


