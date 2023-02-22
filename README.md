# Config server

Spring cloud config server implementation

### How to run

```shell
./gradlew bootRun --args="--spring.cloud.config.server.git.uri=<config repository> --encrypt.key=<encrypt key> --spring.cloud.config.server.git.passphrase=<passphrase>"
```

### Running locally

```shell
./gradlew bootRun --args="--encrypt.key=<encrypt key> --spring.profiles.active=native --spring.cloud.config.server.native.search-locations=file:<config location>"
```

### Release and versioning:

I used [uplift](https://upliftci.dev/)

#### 1) Release
```shell
uplift release
```
