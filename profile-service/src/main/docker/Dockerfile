FROM openjdk:8-jdk-alpine

ARG JAR_FILE=target/profile-embedded-0.1.0.jar

COPY ./target/profile-embedded-0.1.0.jar app.jar

ENTRYPOINT ["java", "-jar","/app.jar"]

