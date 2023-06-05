# Use a Maven base image
FROM maven:3.8.4-openjdk-11-slim

# Set the working directory
WORKDIR /app

# Copy the project files to the container
COPY . /app

# Build the project using Maven
RUN mvn clean package

# Set the entry point to execute Maven commands
ENTRYPOINT ["mvn"]
