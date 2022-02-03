FROM maven:3.8.4-jdk-8
EXPOSE 9002
ADD target/mcommandes.jar mcommandes.jar
ENTRYPOINT ["java", "-jar", "mcommandes.jar"]
