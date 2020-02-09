# § OOAD
# § Design Principles & Patterns
  * Creational
    * factory method (class level)
    * abstract factory
    * builder patern
    * prototype
    * singleton
  * structural
    * adapter pattern(class/object level)
    * bridge pattern
    * composite pattern
    * decorator pattern
    * facade pattern
    * flyweight pattern
    * [proxy pattern](design_pattern/proxy/proxy_pattern.md)
  * behavioral
    * interpreter
    * template method pattern
    * CoR
    * Command
    * [iterator pattern](design_pattern/iterator/iterator.md)
    * mediator pattern
    * memento
    * observer
    * state
    * strategy pattern
    * visitor
  
  
# § Architecture Styles
* data flow architecture style
  * batch sequential
  * pipe and filter
  * process control
* data-centered architecture style
  * shared repository
  * active repository
  * blackboard
* hierarchical architecture style (layered style)
  * layered
  * mvc
  * pac
* tiered systems
  * client-server
  * multi-tiers (N-tier) architecture style
  * p2p(peer to peer)
* load-balancing systems
  * broker
  * dispatcher (load balancer)
  * master-slave
  * edge-based architecture style
* service based systems
  * service-oriented architecture (SOA)
  * [micro service architecture (MSA)](architectures/microservice/msa.md)
* (정리필요)[implicit asynchronous communication architecture style](architectures/implicit_async_communication/implicit_asynchronous_communication_as.md)
  * event-based systems
    * buffered-message-based
      * publish and subscibe architecture style (message topic, one to many)
      * point to point messaging (message queue, one to one)
    * non-buffered event-based implicit invocations ≒ observer
    * event-driven architecture style
    * sensor controller actuator architecture style  
* adaptive systems
  * blackboard
  * microkernel
* other styles
  * variations of MVC architecture style
  * reflection architecture style
* interaction-oriented software architecture
  * mvc (module view controller)
  * pac (presentation-abstraction-control)
* others
  * virtual machine
  * plug-in
  * [proxy](architectures/proxy/proxy_as.md)
  * message broker
  * XML-based web service
  * restful


# § Quality Attribute
* [품질 모델](quality_attributes/quality_attributes.md)
* [availability](quality_attributes/availability/availability.md)