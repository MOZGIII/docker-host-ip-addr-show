# docker-host-ip-addr-show

Image will print docker host's IP addresses (using `ip addr show`).

This is useful when you're working with Docker for Mac and need to know the Docker VM's IP address to connect to it.

## Usage

```shell
docker run -it --rm --privileged --pid=host mozgiii/docker-host-ip-addr-show
```
