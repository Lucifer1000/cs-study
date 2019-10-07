## Proxy architecture style
* synopsis
  * the proxy forces method calls to an object to occu indirectly through a proxy object that acts as a surrogate for the other object, delegating method calls to that object.
  * proxy objects generally share a common interface or uperclass with the service-providing objects
* Benefits and Liabilities
  * benefits
    * Access control to originals
    * **memory savings** - (?)
    * performance gaining (cache proxy)
    * separation of housekeeping and functionality
  * liability
    * potential overkill, if proxies include overly sophisticated functionality
    * level of indirection


* reference
  * [proxy pattern](../../design_pattern/proxy/proxy_pattern.md)