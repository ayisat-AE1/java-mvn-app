# java-mvn-app


clone repo from nana gitlab.com/nanuchi/java-maven-app.git

#what can  you do with jenkins 
- Run test 
- build artifacts
- publish artifacts
- deploy artiacts
- send notification

#integration with other tecnologies 
- Docker 
- build tool
- Repositories
- Deployment servers

#Install jenkins on server
- install jenkins directly on OS 
- Run jenkins as Docker container -- Better way/easier way
- 
create a droplet (project) from digital ocean 
add ssh key 
ssh root@ip.address
apt update
apt install docker.io
docker run -p 8080:8080 -p 50000:50000 -d -v jenkins_home:/var/jenkins_home jenkins/jenkins:its
docker ps 

#open jenkins on the browser - droplet.ip.address:8080


#initialize jenkins
- docker exec -it [containerID] bash
- jenkins@containerIID: copy command from jenkins page
- copy password and go with suggested plugins 
- follow instruction on jenkins page

