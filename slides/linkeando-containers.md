##  Linkeando containers

    $ sudo docker run -d --name db training/postgres
    $ sudo docker run -d -P --name web --link db:db training/webapp python app.py


