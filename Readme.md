# Project Name
Uniconnect

## Prerequisites
- [Docker](https://docs.docker.com/get-docker/) must be installed on your system.

## Running the Project with Docker

Follow these steps to build and run the project in a Docker container.

### Step 1: Clone the Repository
clone the project repository to your local machine:
git clone https://github.com/AshishRaturi8680/sit725-2024-t2-prac8.git


#### building docker file
docker build -t UniConnect .

#### Run the docker container
docker run -p 3000:3000 Uniconnect


#### list all the running instances
docker ps
docker-compose up

####  Stopping and removing container
####  docker stop <container-id>
####  docker rm <container-id>


