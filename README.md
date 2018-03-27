# gs-spring-boot-docker
.\mvnw package

java -jar target/gs-spring-boot-docker-0.1.0.jar

docker build  -t gs-spring-boot-docker:latest --rm=true .

docker run -p 8080:8080 -d --rm -t gs-spring-boot-docker:latest

----------------------------------------------------------------

docker pull rayh001/postclient





