# Use an official OpenJDK runtime as the base image
FROM openjdk:17

# Set the working directory in the container to /app
WORKDIR /app

# Copy the jar file into the container
COPY build/libs/auth-management-0.0.1-SNAPSHOT.jar ./app.jar

# Expose port 8080 for the application
EXPOSE 8080

# Define the command to run the application
ENTRYPOINT ["java", "-jar", "/app/app.jar"]