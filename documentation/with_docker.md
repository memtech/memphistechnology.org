# Developing Using Docker

## Install Docker
Follow the apporpriate installation guide provided by [Docker](https://docs.docker.com/installation/#installation) to get setup.

## Run a Sculpin container
From the checked out repo
```sh
#!/usr/bin/env sh
docker run -it --rm -p 8000:8000 -v `pwd`:/data -u `id -u` clue/sculpin generate --watch --server
```

## View changes in action

Browse to your running docker container.

- Linux: [http://localhost:8000](http://localhost:8000)
- Mac (as of Summer 2018): [http://localhost:8000](http://localhost:8000)

There, you did it!  Congratulations.
