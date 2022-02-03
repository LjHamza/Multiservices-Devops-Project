FROM maven:3.8.4-jdk-8
VOLUME /app
COPY . /app
WORKDIR /app
RUN ["mvn", "clean install"]
ADD target/*.jar clientui.jar
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "clientui.jar"]
