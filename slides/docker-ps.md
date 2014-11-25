##  docker ps


    $ docker ps
    
    CONTAINER ID        IMAGE                       COMMAND                CREATED             STATUS              PORTS                                                                         NAMES
    3d5aa0dc81de        shipyard/shipyard:latest    "/app/controller"      55 minutes ago      Up 34 minutes       0.0.0.0:8080->8080/tcp                                                        goofy_meitner
    ebbc18eab4be        shipyard/rethinkdb:latest   "/usr/bin/rethinkdb    About an hour ago   Up 34 minutes       0.0.0.0:49153->28015/tcp, 0.0.0.0:49154->29015/tcp, 0.0.0.0:49155->8080/tcp   rethinkdb
    
    
