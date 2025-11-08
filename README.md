# Docker
Some Important content on Docker

Why Docker is Needed (The Problem)
Docker is an essential tool, particularly when working in large organisations and with large development teams. It addresses issues encountered in the current software development process, primarily related to replicating environments.
1.	Dependency Errors: When a new team member attempts to replicate a local development environment (e.g., Node.js v16, MongoDB v4.2) on their own system (e.g., installing later versions like Node v20, MongoDB v6), they often encounter manual errors due to the sheer number of dependencies.
2.	Version Incompatibility: An application might rely on a specific version of a dependency, and if that version is not replicated, bugs may occur.
3.	The Classical Problem: This scenario often results in the famous software development problem: "It works on my machine".

Essential Docker Commands:
Command	Purpose
docker pull <image_name>	Fetches the specified image from Docker Hub to the local system.
docker images	Lists all Docker images currently available on the local system.
docker run <image_name>	Creates and executes a new container from the specified image.
docker run -it <image_name>	Runs the container in Interactive Mode, allowing the user to access the container's terminal (e.g., a running Ubuntu container's terminal).
docker ps	Lists all running containers.
docker ps -a	Lists all containers, including those that are stopped (exited).
docker start <id/name>	Starts an existing, stopped container.
docker stop <id/name>	Stops a running container.
docker rm <id/name>	Removes/deletes a container permanently.
docker rmi <id/name>	Removes/destroys a Docker image.
