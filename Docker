# Start with a base image
FROM openjdk:11

# Set the working directory in the container
WORKDIR /app

# Copy the packaged Spring Boot application JAR file into the container
COPY target/demo-0.0.1-SNAPSHOT.jar app.jar

# Specify the command to run the Spring Boot application
CMD ["java", "-jar", "app.jar"]
