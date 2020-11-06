FROM openjdk:8-jdk-alpine
MAINTAINER Irkan Ahmadov <irkan.ahmadov@kapitalbank.az>
ADD target/gateway-service.jar gateway-service.jar
EXPOSE 8765
ENTRYPOINT ["java", "-jar", "/gateway-service.jar"]
