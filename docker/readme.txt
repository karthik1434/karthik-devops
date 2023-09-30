sudo dnf install docker -y
docker --version
sudo systemctl enable docker
sudo systemctl start docker
sudo systemctl status docker
docker images
docker servive stop
service docker stop
service docker start
docker pull httpd
docker images
docker pull ubuntu:latest
docker images
docker run -it -d -p 80:80 httpd
docker ps
docker run -it -d -p 9000:9000 sonarqube
docker rmi my-image:tag-to-remove
