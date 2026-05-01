# nginx-docker-deployment
# Nginx Web Server Deployment on Docker

## Project Overview
For my semester project, I deployed a simple Nginx web server using Docker. Nginx is a high-performance, open-source web server used for serving static content and acting as a reverse proxy.

## Official Resource
- **Docker Hub:** [Nginx Official Image](https://hub.docker.com/_/nginx)

## Deployment Steps
1. **Access Google Cloud Shell:** Navigate to [shell.cloud.google.com](https://shell.cloud.google.com).
2. **Run the Container:** Execute the following command:
   `docker run -d -p 8080:80 --name my-nginx nginx`
3. **Verify Status:** Use `docker ps` to ensure the container is running.
4. **Web Preview:** Click the Web Preview icon in Cloud Shell and select port 8080.
