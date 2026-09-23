What is Container ?
- A way to package application with all the necessary dependencies and configuration
- Portable artifact easily shared and moved around
- Makes deployment and development more efficient
- own isolated environment
- packaged with all needed configuration
- one command to install the app
- run same app with 2 different versions
- No environmental configuration needed on server - except docker runtime
- Layers of images
- Mostly Linux base image
- Application image on top

What is Container repository ?
- private reporsitories 
- public repository for Docker

What is Docker Image ?
- The actual package
- artifact, that can be moved around

What is Doctor container ?
- actually start the application

Docker vs Virtual Machine

OS Kernel - Applications run on Kernal layer
- Docto virtualizes the application layer 
- Host OS kernel
- Docker images are much smaller
- Docker containers start much faster
- VM of any OS can run on any os host
- Linux Docker image can not run in windows os, but we can use Docker toolbox is required
