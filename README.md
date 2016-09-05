# docker-cluster-template
Spawn multiple Docker containers that will run with SSH servers

```
docker build -t sshd .
docker-compose up -d
# do your job on the container cluster
docker-compose down 
```
