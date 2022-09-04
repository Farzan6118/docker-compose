## docker-compose
> the compose file contains:
> **RDBMS** : MySQL, Postgresql, pgadmin & adminer

dont forget to run the following command before you start the docker-compose

- docker volume create --name=postgres_data
- docker volume create --name=pgadmin_data
- docker volume create --name=mysql_data