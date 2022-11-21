## Jenkins

#### commands:

```bash
docker build . -t localjenkins:latest
```

```bash
docker network create jenkins
```

```bash
docker run -p 8080:8080 -p 50000:50000 -v jenkins_home:/var/jenkins_home localjenkins:latest
```