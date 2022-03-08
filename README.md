# eureka-service
This is a system designed in Spring Boot/Data/Cloud used for microservice registration and discovery

## Development environment

**Eureka Server —** Enable our project to be a EUREKA server, which will, in turn, discover all the other projects.

**Spring Boot Actuator —**  To enable our project to be monitored by the EUREKA server and any other monitoring tools will be able to ping this service’s uptime.

 Service is running on docker, image specified in docker-compose.yml file, and started by docker-compose.
 
 http://localhost:8761/
 
 You should see the EUREKA Server Dashboard page like below:
 
 ![image](https://user-images.githubusercontent.com/100357322/157209469-f611b044-cdbc-446f-9eed-dfd96e058337.png)
