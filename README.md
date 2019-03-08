# Spring Boot API

## Requirements

- [Java][java]
- [Apache Maven][mvn]
- [Docker][docker]

## Get Started

```bash
# lauch janus & application
docker-compose up -d && sleep 15 && mvn spring-boot:run
# application health info
curl -i localhost:8080/health
# get data from janusgraph
curl http://localhost:8080/persons/8408
```

[java]: https://www.java.com/en/
[mvn]: https://maven.apache.org/
[docker]: https://www.docker.com/

## Reference

### Spring Boot Actuator

- [47. Endpoints](https://docs.spring.io/spring-boot/docs/1.5.x/reference/html/production-ready-endpoints.html)
- [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/) spring-boot v2.x

### gremlin-driver

- [gremlin.driver](https://tinkerpop.apache.org/javadocs/3.2.4/full/) Java API