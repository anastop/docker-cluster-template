# docker-cluster-template
Spawn multiple Docker containers on the same network, that will just run SSH servers

```
docker build -t anastop/sshd .
docker-compose up -d
# do your job on the container cluster
docker-compose down 
```
