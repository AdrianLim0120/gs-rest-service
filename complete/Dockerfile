FROM eclipse-temurin:17-jdk-alpine
ARG JAR=target/rest-service-complete-0.0.1-SNAPSHOT.jar
COPY ${JAR} app.jar
ENTRYPOINT ["java","-jar","/app.jar"]