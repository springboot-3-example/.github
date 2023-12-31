## About
Springboot 3 Example projects

### Requirement
```
Java        : 21
Springboot  : 3.2.0
```

## Basic
- learn initialize project, pom, application.yml, banner, compile, run, project structure (jdk)   `DONE`
- learn create API and spring component(controller, service, repostory) `DONE`
- Springboot3 & MySql (librarry, config, JPA, CRUD)  `DONE`
- Springboot3 & sl4j (librarry, annotation, config, custom log)   `DONE`
- Springboot3 & liquibase (librarry, config, change-log.yml, query sql file, table change log)    `DONE`
- Springboot3 & Swagger Open API (librarry, config, permitAll url, test)   `DONE`
- Springboot3 & unitest (testing the controller & service class) 

| Status | Name | Desc |
|--|--|--|
| Done | sb3-init | init, pom.xml, banner, application.yml, spring profile (dev, prod)|
| Done | sb3-db-migration | liquibase, config, change-log.yml, .sql |
| Done | sb3-crud-mysql | mysql connector java, jpa, crud, query native, @Controller @Service @Repository |
| Done | sb3-logger | slf4j, logback |
| Done | sb3-swagger-api-doc | swagger, open api, api doc |


## Intermediete
- Springboot3 & Spring Security (librarry, config, jwt, authorization, authentication, permitall api)   `DONE`
- Springboot3 & CORS (config, set all propertiy of CORS)  `DONE`
- Springboot3 & Redis (librarry, application.yml, config, service, CRUD)    `DONE`
- Springboot3 & RabbitMQ (librarry, application.yml, config, publisher, listener, message header, message body, exchange, route, queue)   `DONE`
- Springboot3 & Kafka (librarry, application.yml, config, publisher, listener, broker, group, topic)   `DONE`
- Springboot3 & elastic (librarry, application.yml, config, elastic CRUD service)    `DONE`

| Status | Name | Desc |
|--|--|--|
| Done | sb3-spring-security | spring security 6, security configuration, jwt, authentication, authorization, middleware, UserDetail Spring|
| Done | sb3-redis | spring data redis, config yml, RedisConfig, redis Expired TTL, redis for auth & authorization |
| Done | sb3-cors | CorsConfig.java, allow request header, allow response header, allow origins url, allow http method |
| Done | sb3-rabbitmq | spring rabbit, config yml, publish, listen, exchange, route, queue  |
| Done | sb3-kafka | spring kafka, config yml, publish, listen, broker, group, topic |
| Done | sb3-elastic | spring elastic, config yml, listen data from rabbitmq, crud elastic, searching |

## Advance
- Springboot3 & Rollback Transaction (@Transactional, rollbackfor, @ControllerAdvice, @ExceptionHandler) `Done`
- Springboot3 & Connection Pooling (Tomcat Connection Pooling, set max pooling, active pooling, idle pooling, lock pooling)
- Springboot3 & Concurrency (@Transactional, Optimistic Locking, Pesimistic Locking, Versioning)
- Springboot3 & @Async (annotation, bean registration, implement async been on function )
- Springboot3 & @Scheduler (annotation, execute the scheduler)
- Springboot3 & RateLimmiter (resilent4j librarry, config, implement on controller)
- Springboot3 & Metric API (spring actuator lib, config, permitall url metric, testing generate metric)
- Springboot3 & Prometheus-Grafana (librarry, config, prometheus connection status check, prometheus execute sraping api, grafana datasource config, prometheus.yml, grafana dataource.yml)

| Status | Name | Desc |
|--|--|--|
| Done | sb3-rollback-transaction | @Transactional, rollbackfor, @ControllerAdvice, @ExceptionHandler |
|  | sb3-connection-pooling | librarry tomcat jdbc, hikariCP |
| | sb3-connection-pooling | |
| | sb3-concurrency-racecondition | |
| | sb3-async | |
| | sb3-scheduler  | |
| | sb3-ratelimmiter | |
| | sb3-metric-api | |
| | sb3-prometheus-grafana | |


### Deployment
- learn how to config using spring profile (dev, staging)    `DONE`
- learn how to set value from environtment value for .yml file `DONE`
- learn how to dockerize project (Dockerfile, docker compose, docker image, docker container, expose port, docker network, connection) 
- learn how to ci/cd (github action, pipeline, vps)

| Status | Name | Desc |
|--|--|--|
| | sb3-spring-profile | |
| | sb3-environtment-variable | |
| | sb3-dockerize-project | |
| | sb3-cicd-github-action-vps | |

## Server
- install portainer for docker management on vps

| Status | Name | Desc |
|--|--|--|
| | portainer | |


## Microservices
- Registry Service (librarry, config, registry server, registry client)
- Spring cloud gateway (librarry, application.yml, config, routing, filtering)
- Spring Cloud gateway CORS
- Auth service with feature (user, role, permission, menu, authentication, authorization, jwt, redis  auth)
- Main Service with features (product API for CRUD into mysql, publish into kafka)
- Search Service with features (product API for search data into elastic, listen data from `kafka` and CRUD to `elastic`)
- RateLimmiter with Resilent4j
- Monitoring with Prometheus and Grafana

| Status | Name | Desc |
|--|--|--|
| | sb3-ms-registry| discovery service, eureka|
| | sb3-ms-gateway | spring cloud gateway, redis, rate limmiter, routing, filter, cors, metric, prometheus, grafana, logger|
| | sb3-ms-auth | spring security, jwt, oauth1, redis, authentication, authorization, midleware, logger |
| | sb3-ms-main | crud product api, jpa, mysql, rabbitmq, internal token, logger |
| | sb3-ms-search | search product, elastic, rabbitmq , internal token, logger|



