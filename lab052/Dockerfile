FROM amazoncorretto:22
LABEL version="1.0"
EXPOSE 8080:8080
WORKDIR /app
COPY target/hworld-0.0.1-SNAPSHOT.jar /app/hworld-0.0.1-SNAPSHOT.jar
ENTRYPOINT ["java", "-jar", "hworld-0.0.1-SNAPSHOT.jar"]