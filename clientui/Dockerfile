FROM maven:3.8.4-jdk-8
VOLUME /app
ADD target/*.jar clientui.jar
EXPOSE 8080 8080
ENTRYPOINT ["java", "-jar", "/clientui.jar"]
