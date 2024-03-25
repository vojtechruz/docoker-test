FROM amazoncorretto:21-alpine-jdk
COPY target/docker-test-0.0.1-SNAPSHOT.jar docker-test-0.0.1-SNAPSHOT.jar
EXPOSE 8080

ENTRYPOINT ["java", "-jar", "docker-test-0.0.1-SNAPSHOT.jar"]