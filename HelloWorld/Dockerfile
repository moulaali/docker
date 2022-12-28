#FROM alpine:latest
FROM openjdk:19-jdk-alpine
ADD HelloWorld.class HelloWorld.class
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "HelloWorld"]            
