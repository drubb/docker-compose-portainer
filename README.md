# docker-compose-portainer
Docker Compose Quickstart for local Portainer instance

This is just a little helper for spinning up a local [Portainer](http://portainer.io) instance on Linux machines running Docker. You'll need to have installed [Docker Compose](https://docs.docker.com/compose), too.

To run a Portainer instance:

```
docker-compose up -d
```
After that you can visit the Portainer UI in your Browser, at http://localhost:8080.

To shutdown the running instance:

```
docker-compose stop
```

The Portainer data (e.g. users) is kept persistent using a Docker volume mapped to the *data* folder. 