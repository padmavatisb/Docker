# Docker
Some Important content on Docker

Why Docker is Needed (The Problem)
Docker is an essential tool, particularly when working in large organisations and with large development teams. It addresses issues encountered in the current software development process, primarily related to replicating environments.
1.	Dependency Errors: When a new team member attempts to replicate a local development environment (e.g., Node.js v16, MongoDB v4.2) on their own system (e.g., installing later versions like Node v20, MongoDB v6), they often encounter manual errors due to the sheer number of dependencies.
2.	Version Incompatibility: An application might rely on a specific version of a dependency, and if that version is not replicated, bugs may occur.
3.	The Classical Problem: This scenario often results in the famous software development problem: "It works on my machine".

Essential Docker Commands:
1️⃣ docker pull <image_name>
→ Fetches (downloads) the specified image from Docker Hub to your local system.

2️⃣ docker images
→ Lists all Docker images currently available on the local system.

3️⃣ docker run <image_name>
→ Creates and executes a new container from the specified image.

4️⃣ docker run -it <image_name>
→ Runs the container in interactive mode, allowing you to access the container’s terminal (e.g., Ubuntu shell).

5️⃣ docker ps
→ Lists all currently running containers.

6️⃣ docker ps -a
→ Lists all containers, including those that have stopped (exited).

7️⃣ docker start <container_id/name>
→ Starts an existing, stopped container.

8️⃣ docker stop <container_id/name>
→ Stops a running container.

9️⃣ docker rm <container_id/name>
→ Permanently removes (deletes) a container.

🔟 docker rmi <image_id/name>
→ Removes (deletes) a Docker image from the system.
