## non-buffered event-based implicit invocations architecture style
* synopsis
  * publisher-subscriber or producer-consumer
  * subscribers register themselves with the event source
  * subscriber is notified of such events occurrences
  * subscriber decide on the actions to execute
  * ≒ oberver pattern
* structure
  * event sources and event listenrs
  * event registration process
  * no buffer available between these two parties
* applications
  * interactive GUI components communication and IDE tools
* Pros and Cons
  * Pros.
    * framework availability
    * reusability of components
    * system maintenance and evolution
    * indepenency and flexible connectivity
    * parallel execution of event handlings is possible
* related architectures
  * PAC, message-based, MVC, multi-tier, state machine architectures