FROM openjdk:17
WORKDIR /app
COPY target/*.jar service-a.jar
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "service-a.jar"]
