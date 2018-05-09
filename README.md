This is a Docker study repository.

docker run -> Run a command in a new container

docker run -d -> Run container in background and print container ID

docker run -P -> Publish all exposed ports to random ports

docker run -v -> Bind mount a volume

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

docker stop <container> -> Stop one or more running containers
