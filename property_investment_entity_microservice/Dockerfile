FROM openjdk:11-jre
VOLUME /tmp
ADD target/entity-service.jar entity-service.jar
ENTRYPOINT ["java","-jar","/entity-service.jar"]