FROM openjdk:17-jdk-slim
ARG JAR_FILE=target/projectERP-0.0.1-SNAPSHOT.jar
COPY ${JAR_FILE} erp.jar
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "erp.jar"]