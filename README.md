# Quake JavaScript Server in a Docker Compose

Install the Docker Engine by following the official guide: https://docs.docker.com/engine/install/

Install the Docker Compose by following the official guide: https://docs.docker.com/compose/install/

Note that `server.cfg` should be in the same directory with `quake-js-docker-compose.yml`

Edit `server.cfg` according to your requirements.

Deploy Quake JavaScript server with a Docker Compose using the command:

`docker-compose -f quake-js-docker-compose.yml -p quake up -d`

Open http://ServerNameOrIPAddress (depends on the `SERVER` parameter in `quake-js-docker-compose.yml`) to start play

# Quake JavaScript Server Management

Apply new configuration after a change in the `server.cfg` using the command:

`docker restart ContainerName`
