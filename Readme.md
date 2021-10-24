# Postgres & PGAdmin4 script

This docker-compose script creates a container for postgres and onother one for pgadmin4.

## Setup
Change the values in the .env files to your liking before running ```docker-compose up -d```

## Useful commandline commands

Access docker container from commandline

```docker-compose run postgres bash```

Connect to postgres from inside of the container

```psql --host=database --username=postgres -- dbname=postgres```
