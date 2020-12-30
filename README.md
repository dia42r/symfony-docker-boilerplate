# symfony-docker-boilerplate
symfony-docker-boilerplate : begin new symfony project with docker 

docker-compose run --rm php74-service php bin/console doctrine:database:create

docker exec -it mysql8-container bash

docker exec -it php74-container bash

docker exec -it nginx-container sh

composer create-project symfony/skeleton .

docker-compose up -d --build

mysql -uroot -psecret 
