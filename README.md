# Reskilling Hackathon: The White-Label Store Challenge

This repo contains the source code for the backend, to be deployed in Google Cloud Run Service.

It uses Java 17 + Spring Boot + Spring JDBC.

## Set up

Make sure to replace <YOUR_SQUAD> in `application.properties` file.

Make sure to add the db password there too, it will be provieded to you.

## Helpful Commands

```
docker build -t europe-docker.pkg.dev/<YOUR_SQUAD>/reskilling-hackathon-backend/backend:latest .

docker push europe-docker.pkg.dev/<YOUR_SQUAD>/reskilling-hackathon-backend/backend:latest
```
