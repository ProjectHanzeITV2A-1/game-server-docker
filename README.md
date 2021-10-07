# Game server docker

> Put everything in a docker container

## Building local version

1. Download the StrategicGameServer1.1.0.zip (or any newer version) and put it inside the local folder
2. Run the following command: `docker build --pull --rm -f "local\DockerFile" -t gameserverlocal:latest`

## Building online version

1. Download all the files from blackboard for the new game server
2. Edit the `server.properties` files with your own information
3. Run the following command: `docker build --pull --rm -f "online\DockerFile" -t gameserveronline:latest`

## License

The dockerfiles are licensed under MIT. All the server files are owned by the Hanze University of Applied Sciences.
