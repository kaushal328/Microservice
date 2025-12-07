FROM eclipse-temurin:17-jdk
WORKDIR /app
COPY target/*.jar service-b.jar
EXPOSE 8082
ENTRYPOINT ["java", "-jar", "service-b.jar"]
