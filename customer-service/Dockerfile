FROM openjdk:8-jdk
MAINTAINER Dmitriy Spirin <spirind@gmail.com>
ADD target/customer-service.jar customer-service.jar
ENTRYPOINT exec java -jar /customer-service.jar customer
EXPOSE 3333