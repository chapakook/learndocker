# Learing Docker

docker Beginner
-----
### docker install mac m1
web site
link : https://docs.docker.com/desktop/mac/install/
-----

### docker-compose

make docker-compose.yaml or docker-compose.yml file edit

docker-compose.yaml or docker-compose.yml -> mariadb up
```
vsersion: '3'

services:
  mymariadb:
    container_name: mariadb
    image: mariadb
    environment:
      - MYSQL_ROOT_PASSWORD=root
    ports:
      - 3306:3306
```
### docker-compose + DockerFile
```
```

### shellscript + docker-compose + DockerFile
```
```
-----
### DockerFile .. issue

lintk : https://velog.io/@skynet/Dockerfile에-부모-디렉토리의-파일을-복사-하는-방법
-----