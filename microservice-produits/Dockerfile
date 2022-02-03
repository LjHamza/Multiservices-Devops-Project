FROM maven:3.8.4-jdk-8
WORKDIR /app
COPY target/*.jar /app/mproduits.jar
EXPOSE 9001
ENTRYPOINT ["java", "-jar", "mproduits.jar"]
