# Docker Installation Method

+ Install Docker Desktop from the official website (Windows / macOS) or Docker Engine (Linux)
+ After installation, open a terminal or command prompt to verify Docker
+ Run `docker --version` to confirm Docker is installed correctly
+ Pull the required Docker image using:
  - `docker pull <image-name>`
+ Create a new Docker container with the required ports and environment variables:
  - Example:
    `docker run -d -p 5678:5678 --name n8n-container n8nio/n8n`
+ Verify that the container is running using:
  - `docker ps`
+ Access the application in the browser using:
  - `http://localhost:<port>`
+ Configure volumes to ensure your data persists:
  - Example:
    `-v ~/.n8n:/home/node/.n8n`
+ Restart or stop the container if needed using:
  - `docker restart n8n-container`
  - `docker stop n8n-container`
+ Update the application by pulling a new image and recreating the container
+ Once setup is complete, your app runs fully on Docker with isolated environment and persistent data

