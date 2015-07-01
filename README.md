# izura/lita

Run the lita bot for slack

## Dockerfile

[**Trusted Build**](https://registry.hub.docker.com/u/izura/lita/)

This Docker image is based on the [uzyexe/lita-slack](https://registry.hub.docker.com/u/uzyexe/lita-slack/) base image.

## Using

### docker run

    docker run -d --name="some-redis" --net="host" redis
    docker run -d --name="some-lita-slack" --net="host" --env="SLACK_TOKEN=YOUR_SLACK_TOKEN" uzyexe/lita-slack

--

## lita

[Getting started](http://docs.lita.io/getting-started/)

## lita-slack

[Getting started](https://github.com/kenjij/lita-slack)


