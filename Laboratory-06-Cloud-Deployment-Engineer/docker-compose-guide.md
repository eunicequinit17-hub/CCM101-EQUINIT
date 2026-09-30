# Docker Compose Guide

## What Does the `services:` Block Do?

The `services:` block is where we list the containers that will be used in the project. In this setup, we have two services: `database` for MariaDB and `app` for Nextcloud. Each service has its own image and settings that are needed to run the containers.

## How Does the Nextcloud App Find the Database?

The Nextcloud app uses the `MYSQL_HOST` variable to know where the database is located.

The Compose file has:

```yaml
- MYSQL_HOST=database
```

The word `database` is the name of the MariaDB service. Docker Compose allows the containers to communicate with each other, so Nextcloud can connect to MariaDB using this service name.

## `docker run` vs `docker-compose up -d`

The `docker run` command is usually used to start one container at a time. If we need several containers, we may have to type and configure different commands for each one.

The `docker-compose up -d` command is different because it uses the `docker-compose.yml` file to start multiple containers together. The `-d` means the containers will run in the background, so we can still use the terminal for other commands.
