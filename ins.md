docker images
docker pull openjdk
docker ps
docker run --name JAVA -it -d  openjdk
docker exec -it JAVA jshell
/exit 
docker stop JAVA


docker build -t 2b_docker .
docker run --name js -it 2b_docker
