# dockerkolos
zadanie 1
docker pull httpd
docker run -d -p 8090:80 --name apache httpd
docker ps
docker logs apache 
docker stop apache
docker rm apache
docker rmi httpd

zadanie2
docker build app.
docker run -d --name aplikacja app