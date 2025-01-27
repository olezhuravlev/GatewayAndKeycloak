## Получение от Keycloak токенов клиента "Ostock":

### Для пользователя "illary.huaylupo":

```bash
$ curl -kX POST https://keycloak:8443/realms/spmia-realm/protocol/openid-connect/token \                                                                                                                                                                                                                                                                                Keycloak2| ✭1
-H "content-type: application/x-www-form-urlencoded" \
-d "client_id=ostock&client_secret=OwLrgbbSGI3X6IMzxY0ra0OfMr4eVt27" \
-d "username=illary.huaylupo&password=illary&grant_type=password" \
| jq
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  2213  100  2089  100   124  56065   3327 --:--:-- --:--:-- --:--:-- 59810
{
  "access_token": "eyJhbGciOiJSUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICJ6aHZmTVk4RWcwTHhLeHdsWnRxQkRtMU9mR3FxS2pTaF92Wks3cmFyZ3BJIn0.eyJleHAiOjE3MzQyNjYwOTEsImlhdCI6MTczNDI2NTc5MSwianRpIjoiN2Q3YjA3YzMtMWZkNy00MzY1LThiODktMmJmMzYwYzI0OWM5IiwiaXNzIjoiaHR0cHM6Ly9rZXljbG9hazo4NDQzL3JlYWxtcy9zcG1pYS1yZWFsbSIsInN1YiI6IjVmYzAyZmMxLWVkMDgtNDRkNy1hY2M0LTM3NTBmMDI5OTYxOSIsInR5cCI6IkJlYXJlciIsImF6cCI6Im9zdG9jayIsInNlc3Npb25fc3RhdGUiOiIyZjY0YzMyMi1kNTNhLTQzNGEtYmM2YS0xZjE0MGM5NTlmNWUiLCJhY3IiOiIxIiwiYWxsb3dlZC1vcmlnaW5zIjpbIioiXSwicmVhbG1fYWNjZXNzIjp7InJvbGVzIjpbIm9mZmxpbmVfYWNjZXNzIiwidW1hX2F1dGhvcml6YXRpb24iLCJvc3RvY2stYWRtaW4iXX0sInJlc291cmNlX2FjY2VzcyI6eyJvc3RvY2siOnsicm9sZXMiOlsiQURNSU4iXX19LCJzY29wZSI6InByb2ZpbGUgZW1haWwiLCJzaWQiOiIyZjY0YzMyMi1kNTNhLTQzNGEtYmM2YS0xZjE0MGM5NTlmNWUiLCJlbWFpbF92ZXJpZmllZCI6dHJ1ZSwicHJlZmVycmVkX3VzZXJuYW1lIjoiaWxsYXJ5Lmh1YXlsdXBvIiwiZ2l2ZW5fbmFtZSI6IiIsImZhbWlseV9uYW1lIjoiIn0.frGfN_hzz9IhRuKC2hDLd9J24WNuT5nQKwR_Fva9niCe2eFUmYN1zttEb41lmVb38dkcjkEgqnZMt6Gmwzh08fsE_pjxfWSoPXK23stu9if7WBhXJf9NwlcVH1dPqIk5NgtGEgWHR62LIFyh32rD29dGc1YogW3Fi9mLrL33qbQvlsGVG8VuuiNsZF69lshdsNbHazhel234iF_lIkNtaE0nINuTm1fPrkZQUtGdO69e8z9IO_xjGnWlgJqgxYLK6DyrL3Hqfr28PxOvOeELjsY43tD6AaWcDKin7ckSUztsLoKOyud4Uqpr4FckEgkRWnYVMcRbjBeCoGs1uP8T8g",
  "expires_in": 300,
  "refresh_expires_in": 1800,
  "refresh_token": "eyJhbGciOiJIUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICI2Mjc3YTIwMi0wNGRjLTQwNDEtYTVjYS0zMTZiZmNlMzI5MWIifQ.eyJleHAiOjE3MzQyNjc1OTEsImlhdCI6MTczNDI2NTc5MSwianRpIjoiMjllOThhZDQtNTBmMC00YzEwLWEwM2EtNTcxMTcxNDhkNjRhIiwiaXNzIjoiaHR0cHM6Ly9rZXljbG9hazo4NDQzL3JlYWxtcy9zcG1pYS1yZWFsbSIsImF1ZCI6Imh0dHBzOi8va2V5Y2xvYWs6ODQ0My9yZWFsbXMvc3BtaWEtcmVhbG0iLCJzdWIiOiI1ZmMwMmZjMS1lZDA4LTQ0ZDctYWNjNC0zNzUwZjAyOTk2MTkiLCJ0eXAiOiJSZWZyZXNoIiwiYXpwIjoib3N0b2NrIiwic2Vzc2lvbl9zdGF0ZSI6IjJmNjRjMzIyLWQ1M2EtNDM0YS1iYzZhLTFmMTQwYzk1OWY1ZSIsInNjb3BlIjoicHJvZmlsZSBlbWFpbCIsInNpZCI6IjJmNjRjMzIyLWQ1M2EtNDM0YS1iYzZhLTFmMTQwYzk1OWY1ZSJ9.kRYML7FcjRGK0TFYcdVg2bENc9jTsEAOYeqhBodjmRQ",
  "token_type": "Bearer",
  "not-before-policy": 0,
  "session_state": "2f64c322-d53a-434a-bc6a-1f140c959f5e",
  "scope": "profile email"
}
```

### Для пользователя "john.carnell":

```bash
$ curl -kX POST https://keycloak:8443/realms/spmia-realm/protocol/openid-connect/token \                                                                                                                                                                                                                                                                                Keycloak2| ✭1
-H "content-type: application/x-www-form-urlencoded" \
-d "client_id=ostock&client_secret=OwLrgbbSGI3X6IMzxY0ra0OfMr4eVt27" \
-d "username=john.carnell&password=john&grant_type=password" \
| jq
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100  2201  100  2082  100   119  59216   3384 --:--:-- --:--:-- --:--:-- 62885
{
  "access_token": "eyJhbGciOiJSUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICJ6aHZmTVk4RWcwTHhLeHdsWnRxQkRtMU9mR3FxS2pTaF92Wks3cmFyZ3BJIn0.eyJleHAiOjE3MzQyNjYxNDIsImlhdCI6MTczNDI2NTg0MiwianRpIjoiMzhiN2ZiOTEtMTFmYi00NTRlLTkxOTAtMDI5MGY0N2I2ZWQ1IiwiaXNzIjoiaHR0cHM6Ly9rZXljbG9hazo4NDQzL3JlYWxtcy9zcG1pYS1yZWFsbSIsInN1YiI6IjNmMGU2ZWMyLWY4ODUtNDhhZC1iZjQ5LWY0MWYwZGRlZGRiMSIsInR5cCI6IkJlYXJlciIsImF6cCI6Im9zdG9jayIsInNlc3Npb25fc3RhdGUiOiIxNzhiNjA4My1iYTMzLTQxZjYtOWIxOS1kMjhhMWE1ZDVhOTIiLCJhY3IiOiIxIiwiYWxsb3dlZC1vcmlnaW5zIjpbIioiXSwicmVhbG1fYWNjZXNzIjp7InJvbGVzIjpbIm9mZmxpbmVfYWNjZXNzIiwidW1hX2F1dGhvcml6YXRpb24iLCJvc3RvY2stdXNlciJdfSwicmVzb3VyY2VfYWNjZXNzIjp7Im9zdG9jayI6eyJyb2xlcyI6WyJVU0VSIl19fSwic2NvcGUiOiJwcm9maWxlIGVtYWlsIiwic2lkIjoiMTc4YjYwODMtYmEzMy00MWY2LTliMTktZDI4YTFhNWQ1YTkyIiwiZW1haWxfdmVyaWZpZWQiOnRydWUsInByZWZlcnJlZF91c2VybmFtZSI6ImpvaG4uY2FybmVsbCIsImdpdmVuX25hbWUiOiIiLCJmYW1pbHlfbmFtZSI6IiJ9.mRkFPgo7v2lXwyX302bGjvkzrH8SU5DKW1lP0txnr_MqaW9U2gugoJ1g0y3PCIYJxUwEi4x98XHk9wpl3nyb1r-9Vh8Jx7736sy1gdipPaQLckctPGyEWjbZYcVAXayiFJfFdw7tAhjLuRPWXHC5fsqFQ6sC4UH5Gomv6SvjQP-DYTzcF7GNsAvc0VyWH8Lj3loeC4vhx7TUsljeQzRx1C3_SO8x9X7H1uBAalFNRnLw7eAhMTOVeJDMYJT57wkSajUzZiqdm4kjHGUtDgWprGPrV71-zz1Ud366w7AB7szvqSGEC8Xz2o1KFTW1QazBW8uEVxsKWnoilm-y4b26pg",
  "expires_in": 300,
  "refresh_expires_in": 1800,
  "refresh_token": "eyJhbGciOiJIUzI1NiIsInR5cCIgOiAiSldUIiwia2lkIiA6ICI2Mjc3YTIwMi0wNGRjLTQwNDEtYTVjYS0zMTZiZmNlMzI5MWIifQ.eyJleHAiOjE3MzQyNjc2NDIsImlhdCI6MTczNDI2NTg0MiwianRpIjoiZTkwYTk3NWEtY2Y1ZS00ODQ0LTk1ZDQtMjU1ZmRmZDU4MzZhIiwiaXNzIjoiaHR0cHM6Ly9rZXljbG9hazo4NDQzL3JlYWxtcy9zcG1pYS1yZWFsbSIsImF1ZCI6Imh0dHBzOi8va2V5Y2xvYWs6ODQ0My9yZWFsbXMvc3BtaWEtcmVhbG0iLCJzdWIiOiIzZjBlNmVjMi1mODg1LTQ4YWQtYmY0OS1mNDFmMGRkZWRkYjEiLCJ0eXAiOiJSZWZyZXNoIiwiYXpwIjoib3N0b2NrIiwic2Vzc2lvbl9zdGF0ZSI6IjE3OGI2MDgzLWJhMzMtNDFmNi05YjE5LWQyOGExYTVkNWE5MiIsInNjb3BlIjoicHJvZmlsZSBlbWFpbCIsInNpZCI6IjE3OGI2MDgzLWJhMzMtNDFmNi05YjE5LWQyOGExYTVkNWE5MiJ9.fZ0s4WS_R_AYPBO9HDvfG5Xwh3giYQhNYjYeronE0cc",
  "token_type": "Bearer",
  "not-before-policy": 0,
  "session_state": "178b6083-ba33-41f6-9b19-d28a1a5d5a92",
  "scope": "profile email"
}
```

**Где:**

- `access_token` – токен доступа, который будет передаваться с каждым вызовом защищенного ресурса;
- `expires_in` – количество секунд до истечения срока действия токена доступа. По умолчанию токен авторизации в Spring действует 12 ч;
- `refresh_token` – токен обновления можно повторно передать серверу авторизации для повторной выдачи токена доступа после истечения срока
  его действия;
- `token_type` – спецификация авторизации позволяет определить несколько типов токенов. Чаще всего используется токен «bearer» – токен на
  предъявителя (мы не будем рассматривать другие типы токенов в этой главе);
- `scope` – определяет область действия токена доступа.

---

### Как экспортировать реалм

1. Залогиниться в шелл Docker-контейнера Keycloak:

```text
$ docker exec -it keycloak bash
```

2. Перейти в директорию `/opt/keycloak/bin`;

3. Запустить процедуру экспорта `./kc.sh export --file <FILE_NAME> --realm <REALM_NAME>`:

```text
bash-5.1$ ./kc.sh export --file myrealm-exported.json --realm myrealm
2024-08-23 08:36:06,423 INFO  [org.keycloak.quarkus.runtime.hostname.DefaultHostnameProvider] (main) Hostname settings: Base URL: <unset>, Hostname: <request>, Strict HTTPS: false, Path: <request>, Strict BackChannel: false, Admin URL: <unset>, Admin: <request>, Port: -1, Proxied: false
2024-08-23 08:36:07,353 WARN  [io.quarkus.agroal.runtime.DataSources] (main) Datasource <default> enables XA but transaction recovery is not enabled. Please enable transaction recovery by setting quarkus.transaction-manager.enable-recovery=true, otherwise data may be lost if the application is terminated abruptly
2024-08-23 08:36:07,641 WARN  [org.infinispan.PERSISTENCE] (keycloak-cache-init) ISPN000554: jboss-marshalling is deprecated and planned for removal
2024-08-23 08:36:07,703 INFO  [org.infinispan.CONTAINER] (keycloak-cache-init) ISPN000556: Starting user marshaller 'org.infinispan.jboss.marshalling.core.JBossUserMarshaller'
2024-08-23 08:36:07,967 INFO  [org.keycloak.connections.infinispan.DefaultInfinispanConnectionProviderFactory] (main) Node name: node_822364, Site name: null
2024-08-23 08:36:08,271 INFO  [org.keycloak.broker.provider.AbstractIdentityProviderMapper] (main) Registering class org.keycloak.broker.provider.mappersync.ConfigSyncEventListener
2024-08-23 08:36:08,580 INFO  [org.keycloak.services] (main) KC-SERVICES0034: Export of realm 'myrealm' requested.
2024-08-23 08:36:08,580 INFO  [org.keycloak.exportimport.singlefile.SingleFileExportProvider] (main) Exporting realm 'myrealm' into file /opt/keycloak/bin/myrealm-exported.json
2024-08-23 08:36:08,965 INFO  [org.keycloak.services] (main) KC-SERVICES0035: Export finished successfully
2024-08-23 08:36:09,001 INFO  [io.quarkus] (main) Keycloak 22.0.0 on JVM (powered by Quarkus 3.2.0.Final) started in 3.178s. Listening on: 
2024-08-23 08:36:09,001 INFO  [io.quarkus] (main) Profile import_export activated. 
2024-08-23 08:36:09,001 INFO  [io.quarkus] (main) Installed features: [agroal, cdi, hibernate-orm, jdbc-h2, jdbc-mariadb, jdbc-mssql, jdbc-mysql, jdbc-oracle, jdbc-postgresql, keycloak, logging-gelf, micrometer, narayana-jta, reactive-routes, resteasy, resteasy-jackson, smallrye-context-propagation, smallrye-health, vertx]
2024-08-23 08:36:09,024 INFO  [io.quarkus] (main) Keycloak stopped in 0.021s
```

Для сохранения файла на локальной машине возможны два подхода:

- напрямую найти экспортированный файл на локальной машине;
- либо, если есть подключенные тома Docker, то скопировать файл в папку Docker-контейнера, соответствующую такому тому.

4. Найти на локальной машине экспортированный файл:

```text
$ sudo find / -name "myrealm-exported.json" -type f
/var/snap/docker/common/var-lib-docker/overlay2/.../diff/opt/keycloak/bin/myrealm-exported.json
```

5. Скопировать файл в требуемую директорию:

```text
$ sudo cp /var/snap/docker/common/var-lib-docker/overlay2/10208ebe783a5c88abdd50a8b9503c5c9dc812c05016f17758af4edcff6ebcdb/diff/opt/keycloak/bin/myrealm-exported.json /home/oleg/MyProjects/keycloak-iam/keycloak/config
```

6. Изменить владельца файла:

```text
$ ls -la
total 76
drwxrwxr-x 2 oleg oleg  4096 авг 23 11:42 .
drwxrwxr-x 3 oleg oleg  4096 авг 23 09:31 ..
-rw-r--r-- 1 root root 66617 авг 23 11:42 myrealm-exported.json

 11:43:05  oleg@oleg-desktop-linux  ...keycloak-iam/keycloak/config  ⬡ v20.16.0 
$ sudo chown oleg:oleg myrealm-exported.json 
[sudo] password for oleg: 

 11:43:21  oleg@oleg-desktop-linux  ...keycloak-iam/keycloak/config  ⬡ v20.16.0 
$ ls -la
total 76
drwxrwxr-x 2 oleg oleg  4096 авг 23 11:42 .
drwxrwxr-x 3 oleg oleg  4096 авг 23 09:31 ..
-rw-r--r-- 1 oleg oleg 66617 авг 23 11:42 myrealm-exported.json
```

---

> При старте Keycloak импортирует все файлы из папки `/opt/keycloak/data/import

---

> Если при импорте данных возникла ошибка "Script upload is disabled", то следует из импортируемого json-файла удалить секцию
`authorizationSettings`: https://howtodoinjava.com/devops/keycloak-script-upload-is-disabled/

---

