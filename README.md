# Dockerfile for PCViz

Pathway Commons PCViz source code: https://github.com/PathwayCommons/pcviz

## Local Build 
```
docker build -t cannin/pcviz .
```

## From Docker Hub 
```
docker pull cannin/pcviz
```

## Run PCViz
```
docker run --restart always --name pcviz -d -p 8080:8080 -t cannin/pcviz
docker exec -t -i pcviz /bin/bash # Interactive shell
```