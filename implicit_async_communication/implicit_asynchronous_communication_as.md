## Implicit invocation architectures
*  구성 요소
   *  publisher, sender, producer, source ... 
      *  message/event anouncement
   *  subscriber, receiver, consumer, target, ...
      *  registering their interest, handling events/messages
*  참고
   *  Implicit vs Explicit invocation
      *  explicit invocation 
         *  e.g. obj1 --> obj2
      *  implicit invocation
         *  e.g. obj1 --> **event space**, **event space** --> listeners objs
   *  non-buffered vs buffered
      *  non-buffered : e.g observer. event listener
         *  observer --(subscribe)--> subject
         *  subject --(fire event)--> observer
      *  buffered :  publish & subscribe , message queue
         *  publisher --(publish event)--> **event channel**
         *  subscriber --(subscribe)--> **event channel**
         *  **event channel** --(fire event)--> subscriber
*  종류
   *  [non-buffered event-based implicit invocations architecture style](non-buffered_event-based_implicit_invocations_as.md)
   *  [buffered-message based architecture style](buffered_message_based_as.md)