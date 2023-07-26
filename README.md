# Example of dockerized Apache server

Hosting example Slick demo webpage on APACHE server that is running inside docker container

## HOW TO USE IT

Install [Docker](https://www.docker.com/)

### DOCKER hub

Pull image from [docker hub](https://hub.docker.com/repository/docker/blagoja95/dockerized-static-site-apache/general):

   - `docker run -p 7777:80 blagoja95/dockerized-static-site-apache`


### Make your own container

Clone this repo and run your own container:

1. GIT CLONE
2. cd root of this project
3. build image => `docker build -t example`
4. run container => `docker run -p 8080:80 example`
5. In browser search bar type `localhost:8080` and then hit ENTER key