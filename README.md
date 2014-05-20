# Simple dnsmasq server

``` bash
docker run \
-name dnsmasq \
-v=/etc/dnsmasq.hosts:/dnsmasq.hosts \
-p='53:5353/udp' \
-d eugeneware/dnsmasq
```
