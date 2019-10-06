## buffered mesaged-based architecture style
* 참고
  * message queue vs message topic
    * message queue
      * one to one or point to point
    * message topic
      * one to many
* Structure
  * message producer
  * message consumer
  * message service providers
    * they are connected asynchronously by either a message queue ora  message topic
    * it's typically implemented as a message-oriented middleware(MOM) 
      * providing a reliable message service on a distributed system
* Characteristics (messaging system)
  * used to build reliable, scalable, flexible distributed applications
  * essential for a peer-to-peer client-server
  * high degree of independency of components within the messaging system
    * loosly couples distributed commncation between sw components
  * *much more reliable than the simple event-listener based system*
* applications
  * Java Message Server(JMS)
  * point-to-point messaging (P2P messaging architcture)
    * using message-**queue**
  * public-subscribe messaging(P&S)
    * using message-**topic**
* 동작
  * message producer --(send())--> message queue/topic
  * message queue/topic --(onMessage())--> message consumer
* Pros and Cons.
  * Pros.
    * Anonymity
    * Concurrency
    * Scalability and reliability of message delivery
    * support batch processing
    * loose couplng between producers and consumers