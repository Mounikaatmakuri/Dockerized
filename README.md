## 🚀 Flask App Dockerized
This is a simple Flask web application containerized using Docker. The app runs on port 5000 and displays a "Hello, World!" message.

# 📦 Requirements
Docker installed on your system

# 🛠️ Build and Run
1. Build the Docker Image
docker build -t welcome-app .
2. Run the Docker Container
docker run -d -p 5000:5000 flask-app
Visit http://localhost:5000 in your browser.

# 🧼 Stop and Remove the Container
docker ps           # Get the container ID
docker stop <id>    # Stop the container
docker rm <id>      # Remove the container

# Pull my docker image from Docker hub
docker pull mounika7docker/welcome-app:latest
