# Web Application with Database,Backend And Frontend

## Description

In this Application mongo db is used as database,node js for backend
and react js for frontend.

First of all we all need to create a network for our application.
Commands to create docker network.

```bash
docker network create goals_app_net
```

After that need to create mongo db container within the same network.

```bash
docker contaner run -d --name mongodb --network goals_app_net -p 27017:27017 mongo
```
