# Python Flask Dockerized Application

This is a simple Python Flask application that displays a Sakarltech Website. The application is containerized using Docker, allowing it to be easily deployed and run in any environment.

## Prerequisites

Before running the application, ensure you have the following prerequisites installed on your system:

- Docker: [Install Docker](https://www.docker.com/get-started)

## Getting Started

Follow these steps to run the Flask application using Docker:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/squiz8/python-docker-app.git
   ```

2. **Navigate to the Project Directory**:
   ```bash
   cd python-docker-app
   ```
3. **Build the Docker Image:**:

   ```bash
   docker build -t my-test-app .
   ```

4. **Run the Docker Container:**:

   ```bash
   docker run -d -p 5000:5000 my-test-app
   ```

5. **Access the Application**:

Open a web browser and navigate to http://localhost:5000 to see the "Sakarltech!" website.

## Docker Commands

### Building the Docker Image

To build the Docker image, use the following command:

```bash
docker build -t my-test-app .
```

### Running the Docker Container:

To run the Docker container, use the following command:

```bash
docker run -d -p 5000:5000 my-test-app
```

### Pushing the Docker Image to Docker Hub

To push the Docker image to Docker Hub, follow these steps:

1. **Tag the Image**:

```bash
docker tag my-test-app your-dockerhub-username/my-test-app:latest
```

2. **Push the Image**:

```bash
docker push your-dockerhub-username/my-test-app:latest
```

### Pulling the Docker Image from Docker Hub

To pull the Docker image from Docker Hub, use the following command:

```bash
docker pull your-dockerhub-username/my-test-app:latest
```
