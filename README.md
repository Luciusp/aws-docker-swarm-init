# AWS Docker Swarm Init

A port of mrjgreen's aws-swarm-init to Python3 found [here](https://github.com/mrjgreen/aws-docker-swarm/tree/master/docker/aws-swarm-init). 

Dockerhub build artifacts can be found [here](https://hub.docker.com/repository/docker/luciusp/aws-swarm-init/general).

### Notable Changes
- Updated to python3
- Support for both x64 and arm64 architectures
- S3 objects are now decoded with UTF-8 to prevent an bug where a symbol would be prepended to object reads