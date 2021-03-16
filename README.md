BANCO DE DADOS MYSQL COM DOCKER

 - docker image pulll mysql:5.7
 - docker run -e MYSQL_ROOT_PASSWORD=root mysql:5.7
 - docker container inspect "idcontainer"
 - docker exec -it "idcontainer" bash
 - mysql -u root -p
 - CREATE DATABASE "nomeDataBase";
 - USE "nomeDataBase";
 - SHOW DATABASES;