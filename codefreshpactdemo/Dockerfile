FROM maven:3.5-jdk-8-alpine
ADD pom.xml pom.xml
EXPOSE 8080
CMD ["mvn", "clean", "install", "pact:publish", "-Dpact.broker.url=http://localhost:8500"]