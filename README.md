# APIGateway

An API gateway is programming that sits in front of an application programming interface (API) and acts as a single point of entry for a defined group of microservices. 

To implement API Gateway in our application we have to use zuul proxy i.e. we have to create the zuul server application where we will mention where to route the request in properties or YAML file.

**To Implement API Gateway we need to follow below steps:**

* For this we have to create Zuul server Microservice.
* Need to add zuul dependency
* In main class use @EnableZuulProxy
* In YAML file we have to define zuul attributes such as prefix, routes path URL if MS is registered with eureka then service ID

**Below is the direct and APIGateway call for APIGatewayClient API**
![SS]()
![SS]()
