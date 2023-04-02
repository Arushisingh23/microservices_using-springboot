# Microservices-on-cloud 


![image](https://user-images.githubusercontent.com/85683967/224427479-26b05c79-9714-4e1b-8a77-bdf8a803f283.png)





This repository showcases the creation and deployment of microservices using Spring Boot. It includes code for building microservices and deploying them in a microservices based architecture. Both aspects of the microservices implementation are covered in this project.

Tools:
Spring Boot,
Docker,
Eclipse IDE,
Git client.

Orchestration platform: Kubernetes


![image](https://user-images.githubusercontent.com/85683967/224427613-162127ab-6790-4951-abdb-a9eee9e896d3.png)




Two microservices were created with the help of the spring boot framework.​​

The (light weight) database i.e. H2 ​has been used.​

The Eureka Server is used to keep track of all active clients, API gateways, and microservice instances that are currently running.​​

Dynamic scaling has been implemented with the aid of the Eureka naming server and an API gateway made using Spring Cloud Gateway.​​

Using Docker and Kubernetes, containerization and deployment have been carried out​​


URLS

Currency Exchange Service

http://localhost:8000/currency-exchange/from/USD/to/INR

Currency Conversion Service

http://localhost:8100/currency-conversion-feign/from/USD/to/INR/quantity/10

Eureka

http://localhost:8761/

Zipkin

http://localhost:9411/


API GATEWAY

http://localhost:8765/currency-conversion-feign/from/USD/to/INR/quantity/10
http://localhost:8765/currency-conversion-new/from/USD/to/INR/quantity/10



working demo of the project:https://drive.google.com/file/d/1HOLN3WYC7sSg2JSixInGkkqnxTRvSBdu/view?usp=sharing



document link:https://docs.google.com/document/d/1PZxmxUaCa3izWuE4B83BR0xLRzN59Tx6VpKQSjF4sDc/edit?usp=sharing
