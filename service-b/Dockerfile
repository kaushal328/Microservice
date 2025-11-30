FROM openjdk:17
WORKDIR /app
COPY target/*.jar service-b.jar
EXPOSE 8082
ENTRYPOINT ["java", "-jar", "service-b.jar"]
