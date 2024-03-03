## car-service-spring
---
### Mysql
#### Image:
```
docker pull mysql:8.0.26
```
Container:
```
docker run -d --name mysql-container -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=car -e MYSQL_PASSWORD=root mysql:8.0.26
```
### Redis
#### Image:
```
docker pull redis:bullseye
```
Container:
```
docker run -d --name redis -p 6379:6379 redis:bullseye
```
## My dockerhub
https://hub.docker.com/repository/docker/talespalma/car-service/general
