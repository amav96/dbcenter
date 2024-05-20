## Centralizar bases de datos

## En el proyecto a conectar la base de datos

.env

DB_CONNECTION=mysql

DB_HOST=mysql

DB_PORT="${MYSQL_PORT}"

DB_DATABASE=nameDatabase

DB_USERNAME=root

DB_PASSWORD=dbrootpassword

## Levantar database

docker-compose up -d


## entrar por bas

docker container exec -it mysql bash
y adentro
mysql -u root -p

## entrar a mysql por consola

1) ejecutar => docker exec -it mysql bash
2) ejecutar => mysql -u database_user -p
3) ejecutar => database_password
