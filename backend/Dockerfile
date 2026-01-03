FROM eclipse-temurin:17-jdk-jammy

WORKDIR /app

COPY . .

ENV JAVA_OPTS="-Dspring.devtools.restart.enabled=true"

ENTRYPOINT ["java", "-jar", "build/libs/java-app-backend-0.0.1-SNAPSHOT.jar"]
