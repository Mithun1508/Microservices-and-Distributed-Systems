# Microservices



![Screenshot 2021-11-30 at 12 32 51](https://user-images.githubusercontent.com/40702606/144061535-7a42e85b-59d6-4f7f-9c35-18a48b49e6de.png)


Bootstrap With Maven
 ~ Maven 
 
 ~ IntelliJ 
 
 ~ Open The Project with IntelliJ
 
 ~ Maven Parent Module 

 
## First Microservice
 ~  Spring Cloud 
 
 ~ Create Your First Microservice

 ~  Model Controller and Service 
 
 ~ Postgres and PGAdmin on Docker 

  ~ Connecting to DB 

  ~ Databases 


 
## Microservice Communication via HTTP

~  Fraud Microservice 

~  Database Setup for Fraud

~ Fraud Controller Service and Repository 

~ RestTemplate

~ Testing Microservice Communication 

~ Section End Git Commit

~ Service Discovery with Eureka

~ Service Discovery 

~  Spring Cloud Dependency 

~ Setting up Eureka Server  

~ Dashboard  

 ~ Eureka Clients
 
~ @LoadBalanced 


## Open Feign
~ Open Feign 

 ~ Feign client Feign 
 
~ Using Fegin Client

~ Microservice Communication With Feign

~ Section End Git Commit

## Distributed Tracing
~ Distributed Tracing 

 ~ Adding Sleuth
 
~ Zipkin 

~ Zipkin Container

~ Spring Cloud Sleuth Zipkin 

 ~ Zipkin Dashboard


## Api Gateway With Spring Cloud Gateway
 ~ What are Load Balencers 
 
  ~ Load Balancer Algorithms
 ~ Load Balancer Health Checks 
 ~Spring Cloud Gateway
~ Bootstrap API Gateway
~  Configuring API Gateway
~API Gateway in Action 
~Section End Git Commit

## Message Queues
 ~ Why a message queue 
 ~ Simulate Slow Response 
 ~ Kafka RabbitMQ and SQS (4:19)
~ AMQP Exchange Types (4:55)

## RabbitMQ
 ~ Rabbit MQ Container 
 ~ AMQPTemplate and JacksonConverter
 ~ SimpleRabbitListenerContainerFactory 
 ~ Notification Queue Configuration 
  ~  Queue Topic and Binding 
 ~  Message Producer
 ~ Publishing Messages (9:16)
 ~ Customer Microservice Publishing Messages To Queue (5:49)
  ~ @RabbitListener (7:08)
~  Zikin Dashboard With RabbitMQ
 ~ We made it. Our code is Asynchronous (2:15)
 ~ Section End Git Commit
 
## Packaging Microservices to Runnable Jar
 ~ Intro (0:53)
 ~ Maven Compiler Plugin (7:22)
 ~ Spring Boot Maven Plugin (6:19)
  ~  Installing Root and Individual Modules with Maven (6:34)
 ~ Running all Jars (9:14)
 ~ Section End Git Commit

## Packaging Jars to Docker Images

       ~Docker Images and Containers 
       ~Docker Architecture
       ~Docker Registries
      ~Docker Login 
       ~Spring Boot Maven Plugin and Jib 
       ~ Maven Plugin 
        ~Sub Module Configuration
 ~ Build and PushExercise  Adding Eureka Server and ApiGW to Docker Compose 
     ~Docker Network
    ~Spring Profiles 
        ~ ApiGW and Eureka Server Docker Containers
 ~  Section End Git Commit

## Kubernetes AKA k8s
   ~ Intro 
 ~ What is Kubernetes 
  ~ Master and Control Plane (8:29)
  ~ Worker Nodes (6:21)
  ~ Running Kubernetes Clusters (4:44)
 ~ Minikube (6:40)
 ~ Installing Kubectl (5:52)
  ~ Start9 - Pods (3:02)
~ Deployments (4:10)
 ~ Services (3:00)
~ Service Discovery (6:31)

## Deploying Postgres RabbitMQ and Zipkin to k8s
 Start1 - IntelliJ k8s Plugin (2:32)
 Start2 - Never Deploy Postgres on k8s. Only for local testing (2:37)
 Start3 - Postgres YAMLs (9:45)
 Start4 - Postgres Running in k8s (5:25)
 Start5 - Exercise (0:47)
 Start6 - Exercise Sol (7:50)
 Start7 - Section End Git Commit

## Refactoring Microservices for k8s
  ~ Intro (1:31)
~ No need for API Gateway Anymore
~ Disabling Eureka (1:51)
 ~ Refactor Feign Clients (7:13)
~ Adding SPRING_PROFILES_ACTIVE=default (6:07)
~ Kube Profile (4:40)
~ Building new Images and Testing Docker Compose (4:33)
 ~  Section End Git Commit

## Deploying Microservices to k8s
 ~ Customer YAMLs (6:35)
 ~ Customer Up in Running in k8s 
 ~ We done it. Microservices running in k8s (4:47)
 ~ Section End Git Commit

## Managed Kubernetes Cluster with Linode
 ~ Commands for this sections
 ~ Linode
~ Create K8s Cluster
 ~ Dashboard Overview
~ Kubernetes Dashboard
~  Connect To Cluster Using kubectl
 ~ Postgres
 ~ Zipkin and LoadBalancers
~ RabbitMQ
~ Deploying Microservices
 ~ Testing deployment
~ Managed Postgres Database
~ Connecting to Managed Database
~ Override DB Connection Details with Env Variabales
~ Apply Customer yaml
 ~ Apply Notification and Fraud
~ Testing everything
~ Destroy resources

## Kafka
 ~ What is Kafka (7:55)
 ~ Kafka Broker (4:53)
 ~ Bootstrap Project (2:03)
~  Kafka Producer Config 
~  Kafka Template Send (3:38)
 ~ Kafka Consumer (3:58)
 ~ ConsumerConfig (5:19)
 ~  KafkaListener (3:56)
 ~  Restful Api and Kafka Integration (4:29)
 ~  Custom Objects (8:31)
~  Deployment and Managed Kafka (1:59)
~ Spring for Apache Kafka Documetation (1:06)

## Bringing Back API Gateway for Security
 StartBring Back APIW and Eureka Server
 StartEnabling Eureka Client
 StartStarting All Services
 StartTesting POST request
Security - API Key Authentication
 StartAPI Key Authentication
 StartKey and Applications Overview
 StartApiKeyAuthorization Filter
 StartOrdering the Filter
 StartTesting the Filter
 StartApi Key Validation Overview
 StartExtracting the Route
 StartAttaching ApiKey to request
 StartAccesing Key From Request Header
 StartFakeApiAuthorizationChecker
 StartTesting API Authentication Flow
ApiKey Management App
 StartComing soon
Oauth2 & KeyCloak

## Outline 
  Don't Use Spring Cloud Config Server 
 Vault and Secrets Management 
 Reporting Service
  Deployment 
 

