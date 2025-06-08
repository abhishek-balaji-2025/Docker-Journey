# 📦 Docker Commands Cheat Sheet (Beginner Friendly)

---

## 🐳 Docker Basics

| Command | Description |
|---------|-------------|
| `docker --version` | Shows Docker version installed. |
| `docker info` | Displays Docker system info. |
| `docker help` | Lists Docker commands and help. |

---

## 📂 Images

| Command | Description |
|---------|-------------|
| `docker pull <image>` | Downloads an image from Docker Hub. |
| `docker images` | Lists all local Docker images. |
| `docker rmi <image>` | Deletes a local Docker image. |

---

## 🧱 Containers

| Command | Description |
|---------|-------------|
| `docker run <image>` | Runs a container from an image. |
| `docker run -it <image>` | Runs container interactively (with terminal). |
| `docker run -d <image>` | Runs container in background (detached mode). |
| `docker ps` | Lists running containers. |
| `docker ps -a` | Lists all containers (running & stopped). |
| `docker stop <container>` | Stops a running container. |
| `docker start <container>` | Starts a stopped container. |
| `docker restart <container>` | Restarts a container. |
| `docker rm <container>` | Removes a stopped container. |
| `docker exec -it <container> <command>` | Runs a command inside a running container. |
| `docker logs <container>` | Shows logs from a container. |

---

## 🧰 Volumes

| Command | Description |
|---------|-------------|
| `docker volume ls` | Lists Docker volumes. |
| `docker volume create <name>` | Creates a new volume. |
| `docker run -v <volume>:/path <image>` | Mounts a volume inside a container. |
| `docker volume rm <name>` | Deletes a volume. |

---

## 🛠️ Dockerfiles & Images

| Command | Description |
|---------|-------------|
| `docker build -t <name> .` | Builds an image from a Dockerfile. |
| `docker tag <image> <new-name>` | Tags an image with a new name. |
| `docker push <image>` | Pushes an image to Docker Hub. |
| `docker login` | Logs in to Docker Hub. |

---

## 🔄 Networking

| Command | Description |
|---------|-------------|
| `docker network ls` | Lists Docker networks. |
| `docker network create <name>` | Creates a new Docker network. |
| `docker run --network <name> <image>` | Runs a container on a specific network. |

---

