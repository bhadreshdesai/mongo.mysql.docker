# e-commerce application using microservices architecture

## Server startup

```shell
cd docker
docker-compose up -d
```

## phpMyAdmin

phpMyadmin url http://localhost:8001/

## mongo-express

mongo-express url http://localhost:8002/

## Note

when changing environment variable for mongo-express make sure you remove the attached volume first

```shell
docker-compose down -v
```
