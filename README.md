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

Docker
- docker-compose up -d 
MakeFile
- make run

## entrar a mysql por consola

1) ejecutar => docker exec -it mysql bash
2) ejecutar => mysql -u database_user -p
3) ejecutar => database_password
