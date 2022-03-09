# eureka-service
This is a system designed in Spring Boot/Data/Cloud used for microservice registration and discovery

## Development environment

**Eureka Server —** Enable our project to be a EUREKA server, which will, in turn, discover all the other projects.

**Spring Boot Actuator —**  To enable our project to be monitored by the EUREKA server and any other monitoring tools will be able to ping this service’s uptime.

 Service is running on docker, image specified in docker-compose.yml file, and started by docker-compose.
 
 http://localhost:8761/
 
 You should see the EUREKA Server Dashboard page like below:
 
![image](https://user-images.githubusercontent.com/100357322/157353564-f2a67ea4-830c-4dd5-b09e-2c22c5a17ec8.png)

## Reason to choose EUREKA
Typically, when we begin a project, we have all of the configurations in the properties file. Adding and modifying these properties becomes more difficult as the number of services developed and deployed grows. Some services may cease to exist, while others may relocate. This manual property change may cause problems. In such scenarios, Eureka Service Registration and Discovery makes life easier. As all services are registered to the Eureka server and lookup done by calling the Eureka Server, any change in service locations need not be handled and is taken care of
