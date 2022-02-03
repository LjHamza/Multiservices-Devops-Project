FROM maven:3.8.4-jdk-8
WORKDIR /app
COPY target/*.jar clientui.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "clientui.jar"]
