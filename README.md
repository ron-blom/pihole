# pi-Hole
This project is part of my [homeserver](https://github.com/ron-blom/homeserver) project and will deploy pi-Hole with it's own ip address on my homeserver. Change address in values.yaml to fit your own network.

IP address used:
```
192.168.110.11
```

persistent storage:
```
/etc/pihole
/etc/dnsmasq.d/
```

Images used in this project:
```
pihole/pihole (https://hub.docker.com/r/pihole/pihole)
```

### Deploy 

helm upgrade --install pihole-chart ./pihole-chart
