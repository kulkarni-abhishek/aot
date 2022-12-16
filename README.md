# Ahead of time

Make sure Java 17 and docker is installed on the system.

Execute below commands
mvn -Pnative spring-boot:build-image

docker run -p8080:8080 aot-test:0.0.1-SNAPSHOT
