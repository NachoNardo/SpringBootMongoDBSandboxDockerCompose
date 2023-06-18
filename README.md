# docker-compose-mongodb
Simple MongoDB docker-compose tudo use with the MongoDB Sandbox project.

To run the composer you need to install docker verion 3.7 or higher.

Link for Windows: https://docs.docker.com/desktop/previous-versions/3.x-windows/
Link for Ubuntu 22.04: https://www.digitalocean.com/community/tutorials/how-to-install-and-use-docker-compose-on-ubuntu-20-04
Link for Ubuntu 18.04: https://www.digitalocean.com/community/tutorials/how-to-install-docker-compose-on-ubuntu-18-04
Link for Mac: https://docs.docker.com/desktop/previous-versions/3.x-mac/

Them open the file directory with your terminal and send these commands:

```
// build with no cache
docker-compose build --no-cache
// start the services
docker-compose up
// list the services
docker-compose ps
// list the containers
docker ps
// stop services
docker-compose stop
```

For more informations check: https://github.com/NachoNardo/SpringBootMongoDBSandbox
