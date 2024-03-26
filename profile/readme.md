## About
Learning Springboot 3 with example project (Basic, Intermediete, Advance). 
- All repositories on this page is **private**.
- This page just share readme (table of contents)

### Requirement
```
Java        : 21
Springboot  : 3.2.0
```

## Documentation
[Link Documentation](https://github.com/springboot-3-example/sb3-documentation)

- Docker Compose
- Postman Collection
- Diagram, pdf, doc, excel, all notest etc


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
| Done | [project initiate](https://github.com/springboot-3-example/sb3-init) | init, pom.xml, banner, application.yml, spring profile (dev, prod)|
| Done | [db migration](https://github.com/springboot-3-example/sb3-db-migration) | liquibase, config, change-log.yml, .sql |
| Done | [crud mysql](https://github.com/springboot-3-example/sb3-crud-mysql) | mysql connector java, jpa, crud, query native, @Controller @Service @Repository |
| Done | [logger](https://github.com/springboot-3-example/sb3-logger) | slf4j, logback |
| Done | [swagger api doc](https://github.com/springboot-3-example/sb3-swagger-api-doc) | swagger, open api, api doc |


## Intermediete
- Springboot3 & Spring Security (librarry, config, jwt, authorization, authentication, permitall api)   `DONE`
- Springboot3 & CORS (config, set all propertiy of CORS)  `DONE`
- Springboot3 & Redis (librarry, application.yml, config, service, CRUD)    `DONE`
- Springboot3 & RabbitMQ (librarry, application.yml, config, publisher, listener, message header, message body, exchange, route, queue)   `DONE`
- Springboot3 & Kafka (librarry, application.yml, config, publisher, listener, broker, group, topic)   `DONE`
- Springboot3 & elastic (librarry, application.yml, config, elastic CRUD service)    `DONE`

| Status | Name | Desc |
|--|--|--|
| Done | [spring security](https://github.com/springboot-3-example/sb3-spring-security) | spring security 6, security configuration, jwt, authentication, authorization, middleware, UserDetail Spring|
| Done | [redis](https://github.com/springboot-3-example/sb3-redis-authentication-authorization) | spring data redis, config yml, RedisConfig, redis Expired TTL, redis for auth & authorization |
| Done | [cors](https://github.com/springboot-3-example/sb3-cors) | CorsConfig.java, allow request header, allow response header, allow origins url, allow http method |
| Done | [rabbitmq](https://github.com/springboot-3-example/sb3-rabbitmq-publish-listen) | spring rabbit, config yml, publish, listen, exchange, route, queue  |
| Done | [kafka](https://github.com/springboot-3-example/sb3-kafka-publish-subscribe) | spring kafka, config yml, publish, listen, broker, group, topic |
| Done | [elastic](https://github.com/springboot-3-example/sb3-elastic) | spring elastic, config yml, listen data from rabbitmq, crud elastic, searching |

## Advance
- Springboot3 custom librarry
- Springboot3 deploy manualy the custom librarry into github package using apache maven
- Springboot3 deploy automate the custom librarry into github package using github action
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
| Done | [custom librarry](https://github.com/springboot-3-example/sb3-custom-librarry) | Custom librarry for standarized the Controller, Service, Repository, Dto, Entity, etc |
| Done | [github package as librarry repository](https://github.com/springboot-3-example/sb3-github-package-as-librarry-repository) | Deploy custom librarry into github package, deploy manualy using maven, deploy automate using github action |
| Done | [rollback transaction](https://github.com/springboot-3-example/sb3-rollback-transaction) | @Transactional, rollbackfor, @ControllerAdvice, @ExceptionHandler |
|  | [connection pooling](https://github.com/springboot-3-example/sb3-conn-pooling) | librarry tomcat jdbc, hikariCP |
| | [concurrency racecondition](https://github.com/springboot-3-example/sb3-concurrency-racecondition) | |
| Done | [async](https://github.com/springboot-3-example/sb3-async) | |
| | [scheduler](https://github.com/springboot-3-example/sb3-scheduler)  | |
| | [ratelimmiter](https://github.com/springboot-3-example/sb3-ratelimmiter) | |
| | [metric api](https://github.com/springboot-3-example/sb3-metric-api) | |
| | [prometheus grafana](https://github.com/springboot-3-example/sb3-prometheus-grafana) | |
| Done | [Unitest service layer](https://github.com/springboot-3-example/sb3-racecondition/blob/main/README_unitest_service.md) | |
| Done | [Unitest controller layer](https://github.com/springboot-3-example/sb3-racecondition/blob/main/README_unitest_controller.md) | |


### Deployment
- learn how to config using spring profile (dev, staging)    `DONE`
- learn how to set value from environtment value for .yml file `DONE`
- learn how to dockerize project (Dockerfile, docker compose, docker image, docker container, expose port, docker network, connection) 
- learn how to ci/cd (github action, pipeline, vps)



| Status | Name | Desc |
|--|--|--|
| Done | [Springboot profile](https://github.com/springboot-3-example/sb3-dockerfile-build-dockerimage) | spring profile dev/prod on pom.xml, application.yml application-dev.yml application-prod.yml  |
| Done | [Springboot3 environtment variable](https://github.com/springboot-3-example/sb3-dockerfile-build-dockerimage) | env variable for application-prod.yml and docker-compose.yml |
| Done| [Build docker image](https://github.com/springboot-3-example/sb3-dockerfile-build-dockerimage) | Springboot 3 create, application.yml application-dev.yml application-prod.yml, docker file for build docker image, docker-compose.yml for crete and run docker container|
| Done | [Build docker image with custom setting.xml](https://github.com/springboot-3-example/sb3-dockerimage-with-custom-settingxml) | Springboot 3 create docker file for build docker image with custom setting.xml, download custom librarry from github package |
| Done | [Github Action build & push docker image to dockerhub](https://github.com/springboot-3-example/sb3-nginx/blob/main/readme-github-action.md) | Springboot 3, Dockerfile, Github Action, Dockher Hub, Secreet Variable |
| Done | [Github Action deploy to VPS](https://github.com/springboot-3-example/sb3-nginx/blob/main/readme-github-action.md) | Springboot3, Github Action, VPS, Secreet Variable |

## Server
- install portainer for docker management on vps

| Status | Name | Desc |
|--|--|--|
| Done | [nginx](https://github.com/springboot-3-example/sb3-nginx) | nginx, gateway, load balancer, round robin, vertical scalling backend service, docker , docker compose |
| Done | [portainer](https://github.com/springboot-3-example/sb3-portainer) | portainer, docker-compose, portainer configuration, container management, see logger, download logger, recreate docker container|
| Done | [argocd](https://github.com/springboot-3-example/sb3-argocd) | argocd-server, argocd-repository, ci/cd, docker compose, configuration|



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
| | [registry service](https://github.com/springboot-3-example/sb3-ms-registry)| discovery service, eureka|
| | [gateway service](https://github.com/springboot-3-example/sb3-ms-gateway) | spring cloud gateway, redis, rate limmiter, routing, filter, cors, metric, prometheus, grafana, logger|
| | [auth service](https://github.com/springboot-3-example/sb3-ms-auth) | spring security, jwt, oauth1, redis, authentication, authorization, midleware, logger |
| | [main service](https://github.com/springboot-3-example/sb3-ms-main) | crud product api, jpa, mysql, rabbitmq, internal token, logger |
| | [search service](https://github.com/springboot-3-example/sb3-ms-search) | search product, elastic, rabbitmq , internal token, logger|



