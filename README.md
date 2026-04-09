# Getting started

This repository is a sample application for users following the getting started guide at https://docs.docker.com/get-started/.

The application is based on the application from the getting started tutorial at https://github.com/docker/getting-started

# docker cmd
docker build -t getting-started .
# cmd to run the container 
docker run -d -p 127.0.0.1:3000:3000 getting-started