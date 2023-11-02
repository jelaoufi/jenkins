# jenkins
docker run -it -p 8888:8080 -p 50000:50000 -v /var/run/docker.sock:/var/run/docker.sock -v jenkins_home:/var/jenkins_home jelaoufi/jenkins-with-docker
