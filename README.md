## Getting started

Download repository

```
git clone https://github.com/crusher-destroyer/environment.git
```

## Init project

Make sure that you already install "make"
```
cd environment
make init_folder
git clone https://github.com/crusher-destroyer/orders.git
```
## Configure Hosts
Just add this to hosts file
```
127.0.0.1   traefik.local
127.0.0.1   postgres.local
127.0.0.1   portainer.local
127.0.0.1   redis.local
127.0.0.1   symfony.local
127.0.0.1   rabbitmq.local
```

## Run project

```
make up
cd orders
make build
```

## Swagger

```
http://symfony.local/api/doc
```