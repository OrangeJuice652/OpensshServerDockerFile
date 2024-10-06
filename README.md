# OpensshServerDockerFile
Dockerfile for hosting an SSH server

## container setup

### docker build
```
docker build -t <container name> -f <Dockerfile name>
```

### docker run

```
docker run -p 127.0.0.1:<port dokcer host>:22 -d <container name>
```

- -d
  - docker run as a demon process

## ssh connect

```
docker -p <port docker host> <ssh user>@127.0.0.1
```
