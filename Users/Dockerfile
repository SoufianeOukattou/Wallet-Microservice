FROM openjdk:17-oracle
WORKDIR /app
COPY target/Users-0.0.1-SNAPSHOT.jar /app
EXPOSE 8081
ENTRYPOINT ["java", "-jar", "Users-0.0.1-SNAPSHOT.jar"]