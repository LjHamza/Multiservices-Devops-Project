FROM maven:3.8.4-jdk-8
VOLUME /app
ADD target/*.jar mcommandes.jar
EXPOSE 9002 9002
ENTRYPOINT ["java", "-jar", "mcommandes.jar"]
