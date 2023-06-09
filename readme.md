```
docker image build -t vanghm/jenkins .
```

```
docker run -it --name my_jenkins -p 8080:8080 -p 50000:50000 -v /var/run/docker.sock:/var/run/docker.sock -v jenkins_home:/var/jenkins_home vanghm/jenkins
```