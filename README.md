## Getting Started

```sh
# Clone using SSH
git clone git@github.com:Charans97/cp-docker.git
```
## Generate ClusterId
```sh
docker run --rm confluentinc/cp-server:7.9.5 kafka-storage random-uuid
```
## Run the docker compose file

```sh
docker compose up -d
```

### Verify if the containers are up

```sh
docker compose ps -a
```

## Access the C3 UI in browser
```sh
http://<ip-address>:9021
```
