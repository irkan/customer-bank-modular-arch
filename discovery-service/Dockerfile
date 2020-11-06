FROM openjdk:8-jdk-alpine
MAINTAINER Irkan Ahmadov <irkan.ahmadov@kapitalbank.az>
ADD target/discovery-service.jar discovery-service.jar
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "/discovery-service.jar"]
