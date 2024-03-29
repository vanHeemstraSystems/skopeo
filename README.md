skopeo
# Skopeo

Based on "Skopeo" at https://github.com/containers/skopeo

Based on "Downloading Docker Images from Docker Hub without using Docker" at https://devops.stackexchange.com/questions/2731/downloading-docker-images-from-docker-hub-without-using-docker

There is a tool called [Skopeo](https://github.com/containers/skopeo) which can retrieve Docker images from a repository and save them in several formats.

For example:

- Download the image and save the layers as a tarball: skopeo copy docker://ubuntu docker-archive:/tmp/ubuntu.tar:ubuntu

- Transfer /tmp/ubuntu.tar to another machine if desired.

- Load the image on a Docker instance which does not have internet connection: docker load --input /tmp/ubuntu.tar

It is available in CentOS 7 repo with the package name skopeo. There are no Debian or Ubuntu packages at this time (but it is easy to compile).

## 100 - Introduction

See [README.md](./100/README.md)

## 200 - Requirements

See [README.md](./200/README.md)

## 300 - Building Our Application

See [README.md](./300/README.md)

## 400 - Conclusion

See [README.md](./400/README.md)
