##  docker run

    $ docker run -d -p 8005:80 --name nginx_prueba dockerfile/nginx


Opciones:

* -d Correr proceso detachado
* -i Correr proceso interactivamente
* -v directorio_local:volumen_docker
* -net=bridge|none|container:NAME_or_ID|host
* --dns=IP_ADDRESS

