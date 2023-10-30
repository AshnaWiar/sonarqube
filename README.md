## Sonarqube compose.yml

## Docker images
This project will be using the following docker images.
- [sonarqube](https://hub.docker.com/_/sonarqube) ``sonarqube:comunity``
- [postgresql](https://hub.docker.com/_/postgres) ``postgres:12``

## Setup
Follow these steps below to start a local sonarqube instance.

```zsh
$ git clone git@github.com:AshnaWiar/sonarqube.git

$ cd sonarqube

$ cp .env.example .env

$ docker compose up
```

Sonarqube will be available on http://localhost:9000.<br>
Use the default credentials to login [docs.sonarqube.com.](https://docs.sonarsource.com/sonarqube/latest/instance-administration/security/#:~:text=Default%20admin%20credentials,Password%3A%20admin)
