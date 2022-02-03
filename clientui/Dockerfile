FROM maven:3.8.4-jdk-8
EXPOSE 8080
ADD target/clientui.jar clientui.jar
ENTRYPOINT ["java", "-jar", "clientui.jar"]
