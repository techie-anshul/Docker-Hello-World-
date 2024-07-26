# Docker-Hello-World-
We will create a sample Hello World Docker image from scratch

# Sample Flask Web Application with Python 3.12

This project demonstrates how to deploy a simple Flask web application using Docker with Python 3.12.

## App Functionality

The web application is a simple Flask app that displays "Hello, World!" when accessed on the main page.

## Author

**Roll Number**: G23AI2066

## How to Build and Run

### Prerequisites

- Docker installed on your system

### Steps to Build and Run the Application

1. **Clone the Repository**

   Clone the repository to your local machine:

   ```bash
   git clone [repository-url]
   cd [repository-name]
   ```

2. **Build the Docker Image**

   Run the following command to build the Docker image:

   ```bash
   docker build -t my-flask-app:3.12 .
   ```

3. **Run the Docker Container**

   Use the following command to run the Docker container:

   ```bash
   docker run -p 5000:5000 my-flask-app:3.12
   ```

4. **Access the Application**

   Open a web browser and visit `http://localhost:5000` to see the application in action.

## Explanation of the Process

1. **Dockerfile Creation**

   We created a Dockerfile that builds a Docker image using Python 3.12-slim. This image includes the minimal Debian-based environment needed to run Python 3.12.

2. **Building the Docker Image**

   We used the `docker build` command to create an image named `my-flask-app:3.12`.

3. **Running the Docker Container**

   We used the `docker run` command to start a container from the image and map the container's port to the host.

## Conclusion

This project demonstrates how to deploy a simple web application using Docker, creating images using Python 3.12. The process includes setting up a basic Flask application, writing a Dockerfile, building the image, and running the application inside a Docker container.
