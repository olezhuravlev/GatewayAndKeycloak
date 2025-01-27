# API Gateway With Token Relay

Article [Securing Services with Spring Cloud Gateway](https://spring.io/blog/2019/08/16/securing-services-with-spring-cloud-gateway).

1. Start `redis`, `redis-insight`, `keycloak-pg`, `keycloak`, `dhoster`:

```bash
$ `docker-compose up -d`
```

2. Start project `oauth2-resource-server-app`

```bash
$ ./gradlew :oauth2-resource-server-app:bootRun
```

3. Start project `api-gateway`

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
