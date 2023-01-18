Check if docker is Installed

```bash
    docker --version
```

See All Images

```bash
    docker images
```

List Running Conatiners

```bash
    docker ps
```

List All containers

```bash
    docker ps -a
```

Build Image From Docker File

```bash
    docker build -t node-example .
```

Build container from image. 

```bash
    docker run -d -p 5000:5000 node-example 
```

