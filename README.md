# mysql-docker
MySQL 5.6 docker

Install docker and excute following commands.

Usage
-----

docker build -t mysql .

docker run --name mysql -e MYSQL_ROOT_PASSWORD=root -d mysql 

docker exec -it mysql bash






