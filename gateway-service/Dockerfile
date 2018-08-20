FROM openjdk:8-jdk
MAINTAINER Dmitriy Spirin <spirind@gmail.com>
ADD target/gateway-service.jar gateway-service.jar
ENTRYPOINT execjava -jar /gateway-service.jar gateway
EXPOSE 8765