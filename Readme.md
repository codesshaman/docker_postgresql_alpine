# Official postgresql image inside of docker container

Install:

``git clone https://github.com/codesshaman/docker_postgresql_alpine.git``

Create environment file:

``make env``

Change postgres password:

``nano .env``

Build:

``make build``

or

``docker-compose up -d --build``

Connect in pgadmin to:

``http://your_host:5432``

Down:

``make down``

or

``docker-compose down``

Up:

``make``

or

``docker-compose up -d``

### Command to connect:

```
docker exec -it --user postgres postgresdb psql
```
