# docker-compose-nodejs-haproxy
docker compose project based on blog post [http://blog.hypriot.com/post/docker-compose-nodejs-haproxy/](http://blog.hypriot.com/post/docker-compose-nodejs-haproxy/)

To be run on a raspberry pi.  See [this post](http://blog.hypriot.com/post/hypriotos-back-again-with-docker-on-arm/) for more details.

## Installation
Make sure that you have docker-compose installed on the RPi:

```
sudo sh -c "curl -L https://github.com/hypriot/compose/releases/download/1.1.0-raspbian/docker-compose-`uname -s`-`uname -m` > /usr/local/bin/docker-compose; chmod +x /usr/local/bin/docker-compose"
```

## Running
docker-compose up -d
