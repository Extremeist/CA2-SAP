$docker network create [OPTIONS] NETWORK
$ docker run --name some-mysql -e MYSQL_ROOT_PASSWORD=my-secret-pw -d mysql:tag
$docker run --name phpmyadmin -d --link mysql_db_server:db -p 8080:80 phpmyadmin