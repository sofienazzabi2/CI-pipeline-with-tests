# CI Pipeline with Tests

This project is a simple Node.js application that includes a Continuous Integration (CI) pipeline.

## CI Pipeline Steps

1. **Checkout Code**: Clones the repository to the runner.
2. **Install Node.js**: Sets up the specified Node.js version.
3. **Install Dependencies**: Installs npm packages required for the application.
4. **Wait for MySQL**: Ensures the MySQL service is ready for connections.
5. **Create Database Table**: Initializes the database schema by creating necessary tables.
6. **Run Tests**: Executes tests to ensure code quality and functionality.
7. **Build Docker Image**: Creates a Docker image for the application using a Dockerfile.
8. **Log in to Docker Hub**: Authenticates with Docker Hub using provided credentials.
9. **Tag and Push Docker Image**: Tags the Docker image with the workflow version and pushes it to Docker Hub for deployment.


