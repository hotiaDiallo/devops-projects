# Docker

## Projects
- Hello World - Java, JavaScript and Python
- Microservices 


# Commands

## build images and run containers

```
cd hello-world/hello-world-python 
docker build -t selftaugh/hello-world-python:0.0.1.RELEASE . 
docker run -p 5000:5000 -d selftaugh/hello-world-python:0.0.1.RELEASE

cd hello-world/hello-world-nodejs/
docker build -t selftaugh/hello-world-nodejs:0.0.1.RELEASE . 
docker container run -d -p 5001:5000 selftaugh/hello-world-nodejs:0.0.1.RELEASE

cd hello-world/hello-world-java/
docker build -t selftaugh/hello-world-java:0.0.1.RELEASE . 
docker run -d -p 5002:5000 selftaugh/hello-world-java:0.0.1.RELEASE

```