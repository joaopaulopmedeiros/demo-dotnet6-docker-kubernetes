# How to push to docker hub?

Use Docker CLI for Login 
```
docker login
```

Build your image
```
docker build . -t username/demo-dotnet-6-docker-kubernetes:latest
``` 

Finally publish it
```
docker push username/demo-dotnet-6-docker-kubernetes:latest
```

## More info
- https://docs.docker.com/
