# spring-cloud-gw-service
A sample project to try Spring cloud gateway implementation

> Includes
* Spring Cloud Gateway
* resilience4j
* contract-stub-runner



> Start Application
```
./gradlew bootrun
```

> Test Application
```
./gradlew test
```

> Success Request
```shell
curl http://localhost:8080/get
```

> Fallback Request
```shell
curl --dump-header - --header 'Host: www.circuitbreaker.com' http://localhost:8080/delay/3
```

* [Tutorial from](https://spring.io/guides/gs/gateway/)


