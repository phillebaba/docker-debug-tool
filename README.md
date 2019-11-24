# docker-debug-tool
Docker image used to debug, perfect to get an interactive shell in a Kuberntes or Docker Swarm cluster.

**Docker**
```bash
docker run --rm -it phillebaba/docker-debug-tool:4bba3a3 bash
```

**Kubernetes**
```bash
kubectl run -i --tty --rm debug --image=phillebaba/docker-debug-tool:4bba3a3 --restart=Never -- bash
```
