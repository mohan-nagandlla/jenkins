# Agent with Docker

Installation the docker to the existed agent 

**Step 1**

Build Dockerfile which contian docker installtion to run dokcer inside agent

**Step 2**

Build the image

```
docker build -t docker_agent:v1 .
```

**Step 3**

add the volumemout paths like below for agent pod 

```
- type: HostPath
  hostPath: /var/run/docker.sock
  mountPath: /var/run/docker.sock
```

**Step 4**

make 666 permision to /var/run/docker.sock to inside all worker nodes
