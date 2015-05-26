# Developing Using Docker
## Install Docker
Follow the apporpriate installation guide provided by [Docker](https://docs.docker.com/installation/#installation) to get setup.

## Run a Sculpin contain
From the checked out repo
```sh
docker run -d -p 8000:8000 -v "$PWD:/data" clue/sculpin generate --watch --server
```

## View changes in action

Browse to your running docker container.

- Linux: [http://localhost:8000](http://localhost:8000)
- Mac: prbably [http://192.168.59.103:8000](http://192.168.59.103:8000)

There, you did it!  Congratulations.
