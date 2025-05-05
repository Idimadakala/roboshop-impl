Roboshop is sample microservices architecture which includes multiple modules build on multiple programming languages.

Roboshop inclues multiple services(aka modules)
--static content--
web
--backend compute --
catalogue
user
cart
payment
shipping
--data store --
mysql - default port: 3306
mongodb - default port: 27017
redis - default port: 6379
rabbitMQ - default port: 5672, 15672

docker-compose build
docker-compose push
# to run locally 
docker-compose pull
# run docker-compose in detach mode
docker-compose up -d
$ docker-compose -f docker-compose.yaml -f docker-compose-load.yaml up
