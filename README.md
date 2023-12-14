# XYZ-architecture-db-homework


## Overview
This repo contains a Docker Compose file for running a MongoDB database instance. MongoDB is used by large-scale applications like Tinder for its flexibility and scalability in managing dynamic user data.

## Prerequisites
- [Docker](https://www.docker.com)
- [Docker Compose](https://docs.docker.com/compose/install/)


## How 2 Run
**Clone the Repository**:
```bash
git clone https://github.com/borawhocodess/XYZ-architecture-db-homework.git
```
**Start the Application**:  Navigate to the project directory and run:
```bash
docker-compose up
```

## About the Compose File
- **Access**: MongoDB is accessible on `localhost:27017`.
- **Environment Variables**:
  - `MONGO_INITDB_ROOT_USERNAME`: Sets the root user's username (e.g., `root`).
  - `MONGO_INITDB_ROOT_PASSWORD`: Sets the password for the root user (e.g., `example`).
- **Persistence**: Data is persisted in the `./data` directory on the host.


## How 2 Stop
**Stop the Application**:  Navigate to the project directory and run:
```bash
docker-compose down
```

## Reference
This setup is inspired by the architecture of Tinder which also uses MongoDB. For more details:
- [TechAhead: System Design Architecture Of Tinder](https://www.techaheadcorp.com/blog/understanding-system-design-architecture-of-tinder/)
