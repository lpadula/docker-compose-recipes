# Pi Hole
Pi-hole is a DNS sinkhole that protects your devices from unwanted content without installing any client-side software.

* Official repo: https://github.com/pi-hole/docker-pi-hole/

## Installation

```
cd pihole
docker-compose pull && docker-compose up -d
```

## Logs
```
docker logs -f pihole
```