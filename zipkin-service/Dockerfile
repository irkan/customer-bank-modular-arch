FROM openjdk:8-jdk-alpine
MAINTAINER Irkan Ahmadov <irkan.ahmadov@kapitalbank.az>
ADD target/*.jar zipkin-service.jar
EXPOSE 9411
ENTRYPOINT ["java", "-jar", "/zipkin-service.jar"]
