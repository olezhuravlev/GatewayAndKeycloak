# API Gateway With Token Relay

Article [Securing Services with Spring Cloud Gateway](https://spring.io/blog/2019/08/16/securing-services-with-spring-cloud-gateway).

1. run `oauth2-resource-server-app`

```bash
$ ./gradlew :oauth2-resource-server-app:bootRun
```

2. `docker-compose up -d`

3. run `api-gateway`

```bash
$ ./gradlew :api-gateway:bootRun
```

## APIs:

Credentials: `illary.huaylupo`/`illary.huaylupo`

```bash
http://localhost:8091/test
```

```bash
http://localhost:8091/access-token
```

```bash
http://localhost:8091/id-token
```
