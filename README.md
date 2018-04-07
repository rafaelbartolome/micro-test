# micro-test

Microservices in GO based on <https://ewanvalentine.io/microservices-in-golang-part-1/>

## Build

```docker-compose build```

## Run

```docker-compose up```

## Create a user

```docker

docker-compose run user-cli command \
  --name="Ewan Valentine" \
  --email="ewan.valentine89@gmail.com" \
  --password="Testing123" \
  --company="BBC"

```