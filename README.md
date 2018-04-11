Run docker container with mysql -
docker run -d --name mysql1 -p 3306:3306 -e MYSQL_ROOT_PASSWORD=secret -e MYSQL_DATABASE=todoapp mysql
