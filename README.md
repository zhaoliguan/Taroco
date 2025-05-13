

  ##Foreword
-

  ##Project Introduction
-
A microservice development framework system based on Domain-Driven Design (DDD) using Spring Boot, Spring Cloud, and Axon Framework. It provides a complete set of microservice architecture modules including a unified user center, user authorization and authentication, configuration center, service registry, service routing, circuit breaking, tracing and governance, and canary release. In the future, a storage system and WeChat integration will be added.


  ##Project Architecture
-
  ``` lua
Taroco
├── taroco-assembling -- Project Aggregation Engineering
├── taroco-cloud -- Basic components related to Spring Cloud microservices
|    ├── cloud-admin -- Service Monitoring
|    ├── cloud-api-gateway -- Service Gateway
|    ├── cloud-circuit-breaker -- Service Fault Tolerance Protection
|    ├── cloud-config -- Distributed Configuration Center
|    ├── cloud-registry -- Service Registry
├── taroco-common -- Project Basic Service Components
├── taroco-user-center -- User Center
|    ├── uc-auth -- User Authorization System
|    ├── uc-command -- User Command End
|    ├── uc-common -- User Public Use
|    ├── uc-query -- User Query End
```
  
  
1
