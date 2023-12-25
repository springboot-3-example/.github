## About
Springboot 3 Example projects

## Overview
### Basic
- learn initialize project, pom, application.yml, banner, compile, run, project structure (jdk)   `DONE`
- learn how to implement rdbms (mysql, postgres)    `DONE`
- learn how to implement memory cache (redis)    `DONE`
- learn how to implement logger (logback, sl4j)   `DONE`
- learn how to implement database migration (liquibase)    `DONE`
- learn how to implement api doc (swagger)   `DONE`

### Intermediete
- learn how to implement security api (spring security, jwt, oauth1, oauth2, api key)    `DONE`
- learn how to implement message broker (rabbit mq)  `DONE`
- learn how to implement message broker (kafka)  
- learn how to implement search engine (elastic search)
- learn how to implement clean code    `DONE`
- learn how to created unitest for (controller & service )

### Advance
- learn building backend with microservices architectures
- learn concurrency data (@Transactional, Optimistic Locking, Pesimistic Locking, Versioning)
- learn how to implement rate limmiter & circuit breaker (resillent4j)
- learn how to implement monitoring (prometheus, grafana)
- learn how to implement metrics api (spring actuator)

### Deployment
- learn how to config using spring profile (dev, staging)    `DONE`
- learn how to set value from environtment value for .yml file
- learn how to dockerize project (Dockerfile, docker compose, docker image, docker container, expose port, docker network, connection)
- learn how to ci/cd (github action, pipeline, vps)

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
| Done | sb3-rabbitmq | spring rabbit, config yml, publish, listen, queue, route, exchange |
|  | sb3-kafka | spring kafka, config yml, publish, listen, topic, message |
|  | sb3-elastic | spring elastic, config yml, listen data from rabbitmq, crud elastic, searching |
|  | sb3-ratelimmiter-circuitbreaker | resilent4j, config yml, limmiting api request |
|  | sb3-metric | spring actuator, prometheus, grafana |





