# **** Postgres SQL 14.2 ****

    docker build -t danilo55555/postgres:14.2 .
    docker push danilo55555/postgres:14.2 

## Subir container docker
    docker run --name postgres-teste -e POSTGRES_PASSWORD=testeteste -p 5432:5432 -v /home/danilo/postgres/data-5432:/var/lib/postgresql/data -d danilo55555/postgres:14.2