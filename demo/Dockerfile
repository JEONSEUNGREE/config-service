FROM openjdk:17-ea-11-jdk-slim
VOLUME /tmp
COPY /build/libs/demo-0.0.1-SNAPSHOT.jar ConfigServer.jar
ENTRYPOINT ["java", "-jar", "ConfigServer.jar"]