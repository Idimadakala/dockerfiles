####Docker commands
Dockerfile is a declarative file which helps to create our own image

docker pull kubernetesui/dashboard:v2.7.0
docker run -d -p 8443:8443 kubernetesui/dashboard:v2.7.0 --name kubernetes

docker network create my-network
docker run -d -p 80:80 --network my-network nginx:latest --name nginx