# C++ Docker Example

This project demonstrates how to run a simple C++ program inside a Docker container.

## 🗂 Folder Structure
```
cpp-docker/
├── Dockerfile
└── main.cpp

```
# 🛠 Build and Run Instructions
### Build the Docker image
```
docker build -t cpp-app .
```
### Run the Docker container

```
docker run -it --name mycpp cpp-app
```
# 🧹 Clean Up
### If you want to remove the container after you're done:
```
docker rm mycpp
```

### To remove the image:
```
docker rmi cpp-app
```
