FROM openjdk:15-jdk-alpine
LABEL author="author.nda"
LABEL version="0.0.0-stable"
COPY target/app.jar /app/app.jar
WORKDIR /app
EXPOSE 8080
ENTRYPOINT ["java", "-jar", "app.jar"]
