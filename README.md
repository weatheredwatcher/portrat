# porträt
Official Repo for Porträt, a simple, open source user profile manager


## Running

This application provides a docker-compose.yml for use with docker-compose; it uses the Dockerfile provided as its base. Build and start the image using:

```$ docker-compose up -d --build```

You can run composer either from your host or from the image. The container environment is named "zf", so you will pass that value to docker-compose run:

```$ docker-compose run zf composer install```

At this point, you can visit http://localhost:8080 to see the site running.

Currently the build has no db dependencies, but once we add them, this document will reflect the change