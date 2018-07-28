# SpringBootExample in Docker
Build jar:
mvn package

Test jar:
java -jar docker_spring_boot.jar

Build docker image:
docker build -t firstspringboot .

Start one Container:
docker run -it -p 8080:8080 firstspringboot /bin/bash

visit url:
http://HOSTIP:8080/hello
