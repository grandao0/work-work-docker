This is a Docker study repository.

docker images -> list images

docker rmi <image_name> -> removes <image_name> image

docker ps -> list containers (defaults shows just running)

docker ps -a -> list all containers

docker ps -l -> show last created

docker ps -ls -> display total file sizes

docker rm <id> -> removes the <id> container

docker build -> builds an image from a Dockerfile

docker build -t <image_name> -> Name and optionally a tag in the 'name:tag' format

docker port <container> -> List port mappings or a specific mapping for the container

docker-machine ip [arg...] -> Get the IP address of a machine
