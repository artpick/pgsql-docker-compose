# PGSQL DB Initialization + Grant and Roles

In this example I will create one global DB with 2 schemas, create two tables on each schema using their schema name.
Difficulty is about how to execute first the SH script, then each sql script depending on their schema.

```
cd pgsql
docker-compose up
docker ps -all
docker rm -f
```