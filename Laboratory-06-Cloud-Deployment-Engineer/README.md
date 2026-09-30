# Laboratory 06 - Cloud Deployment Engineer

## Mission Overview

This laboratory is about setting up a private cloud storage system using Nextcloud, MariaDB, and Docker Compose. The main goal is to build a simple two-tier setup where the Nextcloud application connects to a separate MariaDB database container.

## Objectives

* Learn the basic idea of two-tier architecture.
* Create and use a Docker Compose file.
* Run multiple containers as one application.
* Connect the Nextcloud application to MariaDB.
* Open and check the Nextcloud web interface.
* Practice starting and stopping multiple containers.
* Create documentation for the deployment process.

## Commands Executed

```bash
mkdir nextcloud-deployment
cd nextcloud-deployment
nano docker-compose.yml
docker-compose up -d
docker-compose ps
docker-compose down
```

## Skills Learned

In this laboratory, I learned how Docker Compose can help manage several containers together. I also practiced writing a YAML configuration file, connecting the application container to the database, setting environment variables, and checking if the services are running properly.

## Architecture

The deployment has two main services:

* **Nextcloud App** - provides the web interface where users can access the private cloud and handles their requests.
* **MariaDB Database** - stores the information and data needed by the Nextcloud application.
