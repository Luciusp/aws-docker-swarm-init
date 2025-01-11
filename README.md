# AWS Docker Swarm Init

A port of mrjgreen's aws-swarm-init to Python3 [found here](https://github.com/mrjgreen/aws-docker-swarm/tree/master/docker/aws-swarm-init). This was done to allow both x64 and arm64.

### Notable Changes
- Updated to python3
- Build artifacts for both x64 and arm64
- S3 objects are now decoded with UTF-8 to prevent an bug where a symbol would be prepended to object reads