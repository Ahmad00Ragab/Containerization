# Use a base image with JDK 17
FROM openjdk:17-jdk-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the built application JAR into the container
COPY target/Docker-1.0-SNAPSHOT.jar /app/myapp.jar 

# Expose the application's port
# Ensure your application listens on this port
EXPOSE 8080 

# Define the command to run the application
CMD ["java", "-jar", "/app/myapp.jar"]
