FROM maven:3.8.4-jdk-8
WORKDIR /app
COPY target/*.jar /app/mcommandes.jar
EXPOSE 9002
ENTRYPOINT ["java", "-jar", "mcommandes.jar"]
