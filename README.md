# How-to-Run-Jenkins-on-Docker

```
sudo docker pull jenkins/jenkins:2.303.1-jdk8
```

### Commands
```
docker run --rm --name jenkins -p 8080:8080 -p 50000:50000 jenkins/jenkins:2.303.1-jdk8
docker run --rm --name jenkins -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home jenkins/jenkins:2.303.1-jdk8
docker run --rm --name jenkins -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home jenkins/jenkins:2.303.2-jdk8
docker run --rm --name jenkins -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home jenkins/jenkins:2.303.2-jdk11
```
