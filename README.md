# Assumptions
1. You have installed docker
I had to use postgres rather than mysql because the docker image requires a platform/
os that I do not currently have (I am using a very new macbook pro).

# Steps to Install Postgres
1. Run docker command
```shell
    docker run --name postgres-db -e POSTGRES_PASSWORD=p4ssw0rd -p 5432:5432 -d postgres
```
2. Sign in using psql or a database client like [pgAdmin](https://www.pgadmin.org/download/) where ther username is `postgres`

