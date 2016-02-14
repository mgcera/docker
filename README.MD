
#Docker Basic
Please read this two article in sequence (to refresh)

https://docs.docker.com/engine/installation/mac/   
Concept
Installation and 
Basic Command
https://spring.io/guides/gs/spring-boot-docker/     
Spring Boot application run,
Containerize
Create a Docker file
Build a Docker image with Maven
Add build section in POM
$ mvn package docker:build
$ docker push mritunjay/docker-hello
After the Push
$ docker run -p 8080:8080 -t mritunjay/docker-hello
$ docker ps
$ docker stop <container id>
$ docker rm <container sid>





Develop a tutorial - https://github.com/mgcera/docker    // Self learn steps


Docker solr
https://hub.docker.com/_/solr/

