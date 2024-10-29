# PRISMA_WITH_DOCKER
# Project Setup Instructions

## Running the Docker Container

To start the backend server in a Docker container, use the following command:

```bash
docker run -p 3000:3000 backend

```

#### 3000:3000: This maps port 3000 on the host machine to port 3000 inside the Docker container.

#### -p: This flag is used for port mapping between the host and the container.

#### backend: The name of the Docker image for the backend server.

#### open localhost:3000 on browser. You will see the messsage healthy server
