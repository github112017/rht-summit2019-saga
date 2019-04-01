Saga microservices Playground
=============================

## Saga Choreography with Quarkus

### Launch on local env

```bash
cd ticket/
./mvnw compile quarkus:dev
```

### Create Native Image

Launch the script to create the native images:

```bash
cd quarkus/
./build-image.sh
```

### Deploy on OpenShift

Launch the bootstrap script to create your namespace.<br>
Images are downloaded from docker hub.

```bash
cd quarkus/
./deploy-ocp.sh
```
