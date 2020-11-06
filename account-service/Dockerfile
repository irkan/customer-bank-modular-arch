FROM openjdk:8-jdk-alpine
MAINTAINER Irkan Ahmadov <irkan.ahmadov@kapitalbank.az>
ADD target/account-service.jar account-service.jar
EXPOSE 2222
ENTRYPOINT ["java", "-jar", "/account-service.jar"]