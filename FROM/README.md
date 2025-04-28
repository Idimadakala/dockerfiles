FROM is the starting step in the Dockerfile
RUN is the instruction executed at the time of image creation/building ie 
docker build -t docker.in/docker-un/image-name:image-version .
docker push docker-un/image-name:image-verion
CMD is the instruction that run the image finite time ie Image -> contianer creation
docker run -d -p <host-port>:<container-port> -v <volume> --network <network-name> <image-name> --name <container-name>