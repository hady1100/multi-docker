# multi-docker

An over engineered fibbonacci calculator.

Fully containerized with CI/CD for deployment

To run

`docker-compse up`

env variables to set/modify:
```
environment:
    - REDIS_HOST
    - REDIS_PORT
    - PGUSER #postgres user
    - PGHOST #postgres host
    - PGDATABASE #postgres database
    - PGPASSWORD #postgres_password
    - PGPORT=5432 #postgres port
```
