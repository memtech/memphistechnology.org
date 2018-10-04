# Developing Using Docker

## Install Docker

Follow the apporpriate installation guide provided by [Docker](https://docs.docker.com/installation/#installation) to get setup.

## Run a Sculpin container

From the checked out repo:

```sh
#!/usr/bin/env sh
docker run -it --rm -p 8000:8000 -v "$(pwd)":/data -u $(id -u) clue/sculpin generate --watch --server
```

## View changes in action

Browse to your running docker container.

- Linux: [http://localhost:8000](http://localhost:8000)
- Mac
  - Newer versions of Docker will work the same as Linux: [http://localhost:8000](http://localhost:8000)
  - Older version of Docker for Mac will have its own IP on your machine, default is: [http://192.168.99.100:8000](http://192.168.99.100:8000)
    - If that does not work, open from the command line run the following command:
    `open "http://$(docker-machine ip):8000"`

There, you did it!  Congratulations.
