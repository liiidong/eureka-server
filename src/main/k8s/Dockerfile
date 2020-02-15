FROM openjdk:8
MAINTAINER gafci "liiidong@126.com"
VOLUME /tmp
ADD eureka-server-0.0.1-SNAPSHOT.jar app.jar
EXPOSE 8761
ENTRYPOINT ["java","-Djava.security.egd=file:/dev/./urandom","-jar","/app.jar","--spring.profiles.active=prod"]