# K1S
- https://hub.docker.com/_/httpd

# Build & Run
```bash
$ sudo docker build -t my-apache
$ sudo docker run -dit --name my-running-app -p 8765:80 my-apache2
$ sudo docker exec -it my-apache2 bash 
```
