# Service Oriented Architecture(SOA)
### What is an SOA?
Service-oriented architecture is a method or a service provider for multiple software platforms to create business applications like Uber, Ola, etc, Developers use SOA to reuse the service for different platforms
to make the applications.

For example, multiple apps are using SOA for authentication purposes they use third-party services like Google, Facebook, G-mail, etc they use this type of third parties for authentication purpose. In simple words, you can create a single authentication service and you can reuse it for multiple platforms.

SOA is a design pattern which can build distributed systems and provide services for other applications services.
### What are the Pros and Cons of SOA?
### Pros

 - It can save a lot of time and also cost.
 - The large scale of services.
 - Small range of technologies are used.
### Cons
 - It is not good for DevOps since deployment can be complicated
 - The size of the software is significant.
 - Strict governance, protocols, and processes are in place.
### Principles of SOA
 - Interoperability
 - Loose coupling
 - Abstraction
 - Granularity
### Components of SOA
 #### Service
This is the basic building blocks of SOA. this can be visible to the internal users of the organization.
#### Service implementation
The service implementation is the code that builds the logic for performing the specific service function, such as user authentication or bill calculation.
#### Service contract
The service contract defines the nature of the service and its associated terms and conditions, such as the prerequisites for using the service, service cost, and quality of service.
#### Service interface
In SOA, other services or systems communicate with a service through its service interface. The interface defines how you can invoke the service to perform activities or exchange data.
#### Service provider
The service provider creates, maintains, and provides one or more services that others can use. Organizations can create their services or purchase them from third-party service vendors.
#### Service consumer
The service consumer requests the service provider to run a specific service. It can be an entire system, application, or other service. The service contract specifies the rules that the service provider and consumer must follow when interacting with each other.
### How does SOA work?
When the user or consumer requests the service provider it can take the request from the consumer and process the data and performs some tasks and send the response to the user.
Examples are UBER, OLA, etc.
### References

- https://aws.amazon.com/what-is/service-oriented-architecture
- https://www.geeksforgeeks.org/service-oriented-architecture/
- https://www.javatpoint.com/service-oriented-architecture
