# Laravel Docker Base Image

### CMD to build a new image
```
docker image build \
-f docker/Dockerfile \
-t a3mercury/laravel-docker-base-image:latest \
.
```

### CMD to push to Dockerhub
```
docker image push a3mercury/laravel-docker-base-image:latest
```

### References
- [Tutorial reference](https://adevait.com/laravel/containerizing-laravel-applications-with-docker)
- [NGINX alpine stable](https://github.com/nginxinc/docker-nginx/blob/master/stable/alpine/Dockerfile)
- [Dockerhub link](https://hub.docker.com/repositories/a3mercury)