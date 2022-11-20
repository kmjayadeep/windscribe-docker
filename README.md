# Windscribe

Docker container for running [Windscribe](https://windscribe.net/) VPN


## How to use

using docker

```
export WINDSCRIBE_USERNAME=your_username
export WINDSCRIBE_PASSWORD=your_password
docker run --rm -it --cap-add=NET_ADMIN -v windscribe:/etc/windscribe -e WINDSCRIBE_USERNAME=$WINDSCRIBE_USERNAME -e WINDSCRIBE_PASSWORD=$WINDSCRIBE_PASSWORD kmjayadeep/windscribe-docker
```
