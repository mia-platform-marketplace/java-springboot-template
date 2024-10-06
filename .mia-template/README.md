# mia_template_service_name_placeholder

Welcome to Java Spring Boot template

## How to develop this service

This example just expose an "Hello World" endpoint. You can start from this template and build your microservice.

### Run locally

To run locally this example just run the following command

```bash
mvn spring-boot:run
```

To change server port

```bash
mvn spring-boot:run -Dspring-boot.run.arguments=--server.port=3000
```

To launch tests locally

```bash
mvn test
```

To build it

```bash
mvn clean package
```

To force mvn package update

```bash
mvn clean install -U
```

### Routes

The following routes are exposed

- [http://localhost:8080/hello]()

## API

The Open API Documentation is exposed at the following path

```sh
/v3/api-docs
```
