# ui
1) Clone this repo.
2) Build the service image in the service folder:
    $ cd service
    $ docker build . -tmusic-service:latest
3) run the image
    $ docker run -p5000:80 music-service 
4) Test the service
    $ curl localhost:5000/albums
