# SpringBootExample in Docker
Build jar:
mvn package

Build docker image:
docker build -t firstspringboot .

Start one Container:
docker run -it -p 8080:8080 firstspringboot /bin/bash

visit url:
http://<container ip>:8080/hello
