#### To run this project
1. [Install Docker and docker-compose](https://docs.docker.com/docker-for-mac/install/#install-and-run-docker-for-mac) on your machine
2. Inside  the root directory of this project run `docker-compose build` to build the app
3. Run `docker-compose up` to start the docker containera

Or just run `docker-compose up -d --build` - this is shorthand for building and running the app

The application lives at `http://localhost:8080/`
The Node server lives at `http://localhost:3000/`
Elasticsearch lives at `http://localhost:9200/`