FROM openjdk:8-jdk
MAINTAINER Dmitriy Spirin <spirind@gmail.com>
ADD target/account-service.jar account-service.jar
ENTRYPOINT exec java -jar /account-service.jar account
EXPOSE 2222