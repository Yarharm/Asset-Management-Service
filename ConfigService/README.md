# Config-Service

Configuration server that provides endpoints 
for accessing properties of microservices via [Spring Cloud Config](https://cloud.spring.io/spring-cloud-config/reference/html/).

### Spin-up Microservice
```
./mvnw spring-boot:run
```

## Config
Configuration stored under `/resources/config/{microservice}`

Covered Microservices:
- licensing-service
- auth-service