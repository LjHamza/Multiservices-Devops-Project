FROM maven:3.8.4-jdk-8
VOLUME /app
ADD target/*.jar mproduits.jar
EXPOSE 9001 9001
ENTRYPOINT ["java", "-jar", "mproduits.jar"]
