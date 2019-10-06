## **start a container**
docker start 
## **stop a running container** 
docker stop

docker restart 

## **run docker image**
docker run -p 8888:8888 imageName

## **show all images**
docker images 
## **show running containers**
docker ps
## **remove all stoped containers, dangling images, unused networks**
docker system prune

## **Docker-Compose**
docker-compose -f docker-compose-file up

docker-compose stop
