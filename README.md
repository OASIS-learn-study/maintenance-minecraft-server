# Maintenance container

    docker build . -t maintenance-minecraft-server

    docker run --rm -p 25565:25565 maintenance-minecraft-server

    docker ps

    docker exec -it compassionate_brown bash

