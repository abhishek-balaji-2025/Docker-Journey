# 🚀 Pushing a Docker Image to Docker Hub

> **Prerequisite:** You must have a Docker Hub account and Docker installed locally.

---

## 🛠️ Step-by-step Guide

### ✅ Step 1: Create a Docker image from a running container  
Use `docker commit <running-container-name> <custom-image-name>:<tag>` to save the current container state as an image.

---

### ✅ Step 2: Create a repository on Docker Hub  
Go to [hub.docker.com](https://hub.docker.com) and manually create a new repository.

---

### ✅ Step 3: Tag the image for Docker Hub  
Use `docker tag <custom-image-name>:<tag> <dockerhub-username>/<repository-name>:<tag>` to prepare the image for upload.

---

### ✅ Step 4: Log in to Docker Hub from your terminal  
Run `docker login -u <dockerhub-username>` and enter your password when prompted.

---

### ✅ Step 5: Push the image to Docker Hub  
Use `docker push <dockerhub-username>/<repository-name>:<tag>` to upload your image to the repository.

---

Happy Docking! 🐳
