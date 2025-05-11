Write a dockerfile

Build docker image using docker file
docker build -t <imagename:tag>
example : docker build -t java:v1

push the image to docker hub
docker push <dockerhub ID/imagename:tag>
Example : docker push mohammr1/javaapp:v1
Pull the image to cloud console and run the container
docker pull mohammr1/javaapp:v1


