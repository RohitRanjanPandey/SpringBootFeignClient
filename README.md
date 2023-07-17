# SpringBootFeignClient
A sample code depicting how to use Feign Client for synchronous communication between two MicroServices

In Spring Boot, the Feign client is a declarative web service client developed by Netflix. It simplifies the process of making HTTP requests to other services by providing a higher-level abstraction over the underlying HTTP client libraries.

You can check out this code, build it and run both microservices to test.

In this sample code, 
-> there are two microservices named **Order service** and **product service **
-> Order service has exposed endpoints to get all orders and a particular order by id
-> Order service talks to Product service using Feign Client to fetch all the products associated with the order and return them in response 
-> Order service talks to Product service using Feign Client to fetch the products for a particular id

**Note:- This is just a sample code to depict the Feign Client integrations and returns the cached response from API endpoints. No Database is used in this sample. **

