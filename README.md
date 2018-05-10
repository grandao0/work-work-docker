This is a Docker study repository.

docker run -> Run a command in a new container

docker run -d -> Run container in background and print container ID

docker run -P -> Publish all exposed ports to random ports

docker run -v -> Bind mount a volume

docker run --name first-site -d -P -v ~/first-site-docker:/usr/share/nginx/html nginx -> Upload some html in nginx and start service

docker images -> List images

docker rmi <image_name> -> Removes <image_name> image

docker ps -> List containers (defaults shows just running)

docker ps -a -> List all containers

docker ps -l -> Show last created

docker ps -ls -> Display total file sizes

docker rm <id> -> Removes the <id> container

docker build -> Builds an image from a Dockerfile

docker build -t <image_name> -> Name and optionally a tag in the 'name:tag' format

docker port <container> -> List port mappings or a specific mapping for the container

docker-machine ip [arg...] -> Get the IP address of a machine

docker start <container> -> Start one or more running containers

docker stop <container> -> Stop one or more running containers

docker commit -m "<message>" -a "<hub_user>" <container_id> <hub_user/hub_name:tag> -> Commit image to Docker Hub

docker push <hub_user/hub_name:tag> -> Push the image to the Docker Hub

docker pull <hub_user/hub_name:tag> -> Pull the image from the Docker Hub

docker history <image_name> -> List image history

docker rename <container_id> -> Renames the container name

docker exec -it <container_id> <command> -> Run a command in a running container

docker exec -it 9a9610bdf2b0 /bin/bash -> Opens the bash of a running centos6 container
