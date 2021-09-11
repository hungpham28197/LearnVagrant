Tham khảo [Learn Docker Swarm with Vagrant](https://levelup.gitconnected.com/learn-docker-swarm-with-vagrant-47dd52b57bcc)

```
docker swarm init --listen-addr 192.168.207.142:2377 --advertise-addr 192.168.207.142:2377
```

docker swarm join --token SWMTKN-1-13kva8zods98t8cx4fgg5qtyu999lugomau4lht2u1ys4kzmz1-7vnbl8jg7jv4j19yz9iapbf3q 192.168.207.142:2377