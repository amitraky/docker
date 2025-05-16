# docker

## Create Images Command
 Syntax :  `docker build -t imageName:version DockerFileLocation`
 
 Example:  ```docker build -t nginx:1.0 Dockerfile```

## Create container Commond
 Syntax :  `docker run -d -p externalPort:internalPort imageName` 
 
 Example : `docker run -d -p 8080:80 nginx:1.0` 
