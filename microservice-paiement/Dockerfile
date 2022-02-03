FROM maven:3.8.4-jdk-8
VOLUME /app
COPY target/*.jar mpaiement.jar
EXPOSE 9003 9003
ENTRYPOINT ["java", "-jar", "mpaiement.jar"]
