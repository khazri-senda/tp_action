
FROM eclipse-temurin:11-jre

VOLUME /tmp

EXPOSE 8081

ARG JAR_FILE=springboot/app/target/demo-0.0.1.jar

COPY ${JAR_FILE} /app.jar

ENTRYPOINT ["java","-jar","/app.jar"]
