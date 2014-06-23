fake-s3
=======

Dockerfile for
[lphoward/fake-s3](https://registry.hub.docker.com/u/lphoward/fake-s3/)
on [Docker Hub](https://registry.hub.docker.com).

Deploys [fake-s3](https://github.com/jubos/fake-s3) in a Docker container.

To create a deployment:

        docker run --name my_s3 -d lphoward/fake-s3

Service exposed on port 4567.  Credentials on connection requests are ignored.
See [fake-s3](https://github.com/jubos/fake-s3) README for details/limitations.
