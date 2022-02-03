FROM maven:3.8.4-jdk-8
WORKDIR /app
COPY target/*.jar /app/mpaiement.jar
ENTRYPOINT ["java", "-jar", "mpaiement.jar"]
EXPOSE 9003
