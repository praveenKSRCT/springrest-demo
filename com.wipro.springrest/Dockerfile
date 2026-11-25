FROM openjdk:17-jdk-slim

WORKDIR /app

COPY target/*.jar cicd.jar

EXPOSE 8082

ENTRYPOINT ["java","-jar","cicd.jar"]