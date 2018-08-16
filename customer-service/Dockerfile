FROM openjdk:8-jdk
MAINTAINER Dmitriy Spirin <spirind@gmail.com>
ADD target/customer-service.jar customer-service.jar
ENTRYPOINT ["java", "-jar", "/customer-service.jar"]
EXPOSE 3333