# REST. RESTful services.

**REST**, or **REpresentational State Transfer**, is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other. REST does not enforce any rule regarding how it should be implemented at the lower level, it just put high-level design guidelines and leaves us to think of our own implementation.

Services developed in accordance with REST architecture are called **Restful** Web Services. RESTful systems, are characterized by how they are stateless and separate the concerns of client and server.

#### REST defines 6 architectural constraints

1. Uniform Interface
  
  **This rule has been described with 4 sub-items.**
  
  * Resource identification in requests. Rather than making all our requests to a singular service endpoint, we now start talking to individual resources.
  * Resource manipulation through representations. When a data belonging to the source is obtained on the client side, this data should be sufficient to make the necessary changes on the source.
  * Self-descriptive messages. It introduces using HTTP verbs and HTTP response codes
  * Hypermedia as the engine of application. The point of hypermedia controls is that they tell us what we can do next, and the URI of the resource we need to manipulate to do it. Rather than us having to know where to post our appointment request, the hypermedia controls in the response tell us how to do it. One obvious benefit of hypermedia controls is that it allows the server to change its URI scheme without breaking clients. A further benefit is that it helps client developers explore the protocol. The links give client developers a hint as to what may be possible next.

2. Client Server Architecture
3. Stateless
4. Cacheable
5. Layered system
6. Code on demand (optional)





### Resources
* https://martinfowler.com/articles/richardsonMaturityModel.html
* https://restfulapi.net/rest-architectural-constraints/
* https://ademcatamak.medium.com/5-rules-of-rest-architecture-434abaf5db44
