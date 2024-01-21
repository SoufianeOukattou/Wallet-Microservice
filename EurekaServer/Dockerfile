FROM openjdk:17-oracle
WORKDIR /app
COPY target/EurekaServer-0.0.1-SNAPSHOT.jar /app
EXPOSE 8761
ENTRYPOINT ["java", "-jar", "EurekaServer-0.0.1-SNAPSHOT.jar"]