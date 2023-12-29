## About
Springboot 3 Example projects

### Requirement
```
Java        : 21
Springboot  : 3.2.0
```

## Overview
### Basic
- learn initialize project, pom, application.yml, banner, compile, run, project structure (jdk)   `DONE`
- learn create API and spring component(controller, service, repostory) `DONE`
- Springboot3 & MySql (librarry, config, JPA, CRUD)  `DONE`
- Springboot3 & sl4j (librarry, annotation, config, custom log)   `DONE`
- Springboot3 & liquibase (librarry, config, change-log.yml, query sql file, table change log)    `DONE`
- Springboot3 & Swagger Open API (librarry, config, permitAll url, test)   `DONE`
- Springboot3 & unitest (testing the controller & service class) 

### Intermediete
- Springboot3 & Spring Security (librarry, config, jwt, authorization, authentication, permitall api)   `DONE`
- Springboot3 & CORS (config, set all propertiy of CORS)  `DONE`
- Springboot3 & Redis (librarry, application.yml, config, service, CRUD)    `DONE`
- Springboot3 & RabbitMQ (librarry, application.yml, config, publisher, listener, message header, message body, exchange, route, queue)   `DONE`
- Springboot3 & Kafka (librarry, application.yml, config, publisher, listener, broker, group, topic)   `DONE`
- Springboot3 & elastic (librarry, application.yml, config, elastic CRUD service)    `DONE`

### Advance
- Springboot3 & Rollback Transaction (@Transactional, rollbackfor, @ControllerAdvice, @ExceptionHandler) `Done`
- Springboot3 & Connection Pooling (Tomcat Connection Pooling, set max pooling, active pooling, idle pooling, lock pooling)
- Springboot3 & Concurrency (@Transactional, Optimistic Locking, Pesimistic Locking, Versioning)
- Springboot3 & @Async (annotation, bean registration, implement async been on function )
- Springboot3 & @Scheduler (annotation, execute the scheduler)
- Springboot3 & RateLimmiter (resilent4j librarry, config, implement on controller)
- Springboot3 & Metric API (spring actuator lib, config, permitall url metric, testing generate metric)
- Springboot3 & Prometheus-Grafana (librarry, config, prometheus connection status check, prometheus execute sraping api, grafana datasource config, prometheus.yml, grafana dataource.yml)


### Microservices
- Registry Service (librarry, config, registry server, registry client)
- Spring cloud gateway (librarry, application.yml, config, routing, filtering)
- Spring Cloud gateway CORS
- Auth service with feature (user, role, permission, menu, authentication, authorization, jwt, redis  auth)
- Main Service with features (product API for CRUD into mysql, publish into kafka)
- Search Service with features (product API for search data into elastic, listen data from `kafka` and CRUD to `elastic`)
- RateLimmiter with Resilent4j
- Monitoring with Prometheus and Grafana

### Deployment
- learn how to config using spring profile (dev, staging)    `DONE`
- learn how to set value from environtment value for .yml file `DONE`
- learn how to dockerize project (Dockerfile, docker compose, docker image, docker container, expose port, docker network, connection) 
- learn how to ci/cd (github action, pipeline, vps) 

### Server
- install portainer for docker management on vps

## List Of Repositories
All repo's was privated
| Status | Name | Desc |
|--|--|--|
| Done | sb3-init | init, pom.xml, banner, application.yml, spring profile (dev, prod)|
| Done | sb3-db-migration | liquibase, config, change-log.yml, .sql |
| Done | sb3-crud-mysql | mysql connector java, jpa, crud, query native, @Controller @Service @Repository |
| Done | sb3-spring-security | spring security 6, security configuration, jwt, authentication, authorization, middleware, UserDetail Spring|
| Done | sb3-redis | spring data redis, config yml, RedisConfig, redis Expired TTL, redis for auth & authorization |
| Done | sb3-cors | CorsConfig.java, allow request header, allow response header, allow origins url, allow http method |
| Done | sb3-logger | slf4j, logback |
| Done | sb3-swagger-api-doc | swagger, open api, api doc |
| Done | sb3-rabbitmq | spring rabbit, config yml, publish, listen, exchange, route, queue  |
| Done | sb3-kafka | spring kafka, config yml, publish, listen, broker, group, topic |
| Done | sb3-elastic | spring elastic, config yml, listen data from rabbitmq, crud elastic, searching |
| Done | sb3-rollback-transaction | @Transactional, rollbackfor, @ControllerAdvice, @ExceptionHandler |
| inprogress | sb3-connection-pooling | librarry tomcat jdbc, hikariCP |
| Inprogress | sb3-microservices | springcloud gateway, routing, filter, oauth, redis, kafka, elastic, postgres, prometeus, grafana|




