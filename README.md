FROM ubuntu:20.04
RUN apt -get update && apt -get install -y\curl\&&rm -rf /var/lib/apt/lists/*
CMD ["echo", "hello-world"]


docker --version
docker login
docker pull hello-world
docker build -t exp7 "C:\Users\Patil\OneDrive\Documents
docker tag exp7:latest omomom/exp7:latest
docker push omomom/exp7:latest
docker images
docker ps
