#start with a base image containing the java run time

FROM openjdk:21-jdk-slim

MAINTAINER chinmayJain03

# Copy from target to docker maching
COPY target/accounts-1.0.0.jar accounts-1.0.0.jar

ENTRYPOINT ["java", "-jar", "accounts-1.0.0.jar"]
