FROM openjdk:8-jdk-alpine
MAINTAINER Irkan Ahmadov <irkan.ahmadov@kapitalbank.az>
ADD target/customer-service.jar customer-service.jar
EXPOSE 3333
ENTRYPOINT ["java", "-jar", "/customer-service.jar"]
