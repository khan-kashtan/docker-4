## Building micorservices application

##### To install docker compose via link:
https://docs.docker.com/compose/install/#install-compose

* Setup  username and other environments (optional) at .env.example
* Rename .env.example to .env

* To build and run services:
``` bash
docker-compose up -d
```

* To build and run puma in debug mode:
``` bash
docker-compose -f docker-compose.yml -f docker-compose.debug.yml up -d
```

* To stop and remove containers use:
``` bash
docker-compose down
```
