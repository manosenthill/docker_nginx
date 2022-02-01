# Run nginx in Docker
~~~ 
docker run -p 8080:80 -d nginx
~~~
- option -p which port needs to be run
- option -d run docker in detach mode
- nginx use nginx:latest image

run `docker ps` to get the container details something like below
~~~
CONTAINER ID        IMAGE               COMMAND                  CREATED             STATUS              PORTS                  NAMES
31e7cb130a5f        nginx               "/docker-entrypoin..."   4 seconds ago       Up 3 seconds        0.0.0.0:8080->80/tcp   ecstatic_thompson
~~~

open browser and enter http://localhost:8080 which brings the page like below

[nginx](/doc/docker_nginx.png)
