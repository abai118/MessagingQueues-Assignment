# Message queues 

* A message queue is a form of asynchronous service-to-service communication used in serverless and microservices architectures. Messages are stored on the queue until they are processed and deleted. Each message is processed only once, by a single consumer. Message queues can be used to decouple heavyweight processing, to buffer or batch work, and to smooth spiky workloads.you can find more resources on this [link](https://aws.amazon.com/sqs/)[1]


* Message queues allow different parts of a system to communicate and process operations asynchronously. A message queue provides a lightweight buffer which temporarily stores messages, and endpoints that allow software components to connect to the queue in order to send and receive messages

* The messages are usually small, and can be things like requests, replies, error messages, or just plain information. To send a message, a component called a producer adds a message to the queue. The message is stored on the queue until another component called a consumer retrieves the message and does something with it.
* To send a message, a component called a producer adds a message to the queue. The message is stored on the queue until another component called a consumer retrieves the message and does something with it.

[![ Message Queues process](/assets/images/shiprock.jpg "Shiprock, New Mexico by Beau Rogers")]( https://d1.awsstatic.com/product-marketing/Messaging/sqs_seo_queue.1dc710b63346bef869ee34b8a9a76abc014fbfc9.png)


# Benefits or Features of Message Queues 

* In modern cloud architecture, applications are decoupled into smaller, independent building blocks that are easier to develop, deploy and maintain. Message queues provide communication and coordination for these distributed applications.
* some other benifits or features are listed below 
* ### Better Performance
* Message queues enable asynchronous communication, which means that the endpoints that are producing and consuming messages interact with the queue, not each other.
* ### Increased Reliability
* If one part of the system is ever unreachable, the other can still continue to interact with the queue. The queue itself can also be mirrored for even more availability.
* ### Granular Scalability
* Message queues make it possible to scale precisely where you need to. When workloads peak, multiple instances of your application can all add requests to the queue without risk of collision.
* ### Simplifed Decoupling
* Message queues remove dependencies between components and significantly simplify the coding of decoupled applications.
# Top Message Queue (MQ) Software
* **MuleSoft Anypoint Platform.**
* **IBM MQ.**
* **Apache Kafka.**
* **Apache Qpid.**
* **Azure Scheduler.**
* **RabbitMQ.**
* **Azure Queue Storage.**
* **TIBCO Rendezvous.**

# What is enterprise service bus (ESB)?
An enterprise service bus (ESB) is a software platform used to distribute work among connected components of an application. It is designed to provide a uniform means of moving work, offering applications the ability to connect to the ESB and subscribe to messages based on simple structural and business policy rules.

[![ esb]()]( https://www.mulesoft.com/sites/default/files/diagram-basic-esb.png)# MessagingQueues-Assignment


