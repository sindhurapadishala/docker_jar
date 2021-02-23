FROM openjdk:8
EXPOSE 8080
ADD target/docker-demo-jar.jar docker-demo-jar.jar
ENTRYPOINT["java","-jar","/docker-demo-jar.jar"]