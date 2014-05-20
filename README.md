# Simple dnsmasq server

``` bash
sudo docker run \
-v="$(pwd)/dnsmasq.hosts:/dnsmasq.hosts" \
-name=dnsmasq \
-p='127.0.0.10:53:5353/udp' \
-d eugeneware/dnsmasq
```
