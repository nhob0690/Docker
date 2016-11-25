# Docker

To build the images;
docker build -t ssh-image .

To run the images :

docker run -P -d -p xx ssh-image

Copy the key
docker cp containerid:/root/.ssh/id_rsa containerid
