##  Portando

    $ docker save
    $ docker save mynewimage>/tmp/mynewimage.tar 
     
    $ docker load
    $ docker load < /tmp/mynewimage.tar
     
    $ docker export
    $ docker export 47c>sigehoscontainer.tar
     
    $ docker import
    $ docker import - {IMAGEN} <sigehoscontainer
     

