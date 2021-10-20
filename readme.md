# Keycloak service

An attempt to setup a keycloak cluster service with Docker Compose

This services includes:

- A PostGRES database managed by Keycloak
- A Nginx as Load-Balancer
- A Keycloak cluster containing 2 instances

## How to run

`docker-compose up -d`

After successfully run the command, click [here](http://localhost:8080) to open the Keycloak Admin Console.
