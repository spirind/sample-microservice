FROM openjdk:8-jdk
MAINTAINER Dmitriy Spirin <spirind@gmail.com>
ADD target/discovery-service.jar discovery-service.jar
EXPOSE 8761
ENTRYPOINT exec java -jar /discovery-service.jar discovery