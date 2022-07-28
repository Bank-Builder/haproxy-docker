# haproxy-docker
Demonstration of haproxy using docker

### quickstart
`docker-compose up --build`

Go to `192.1678.0.33` (or whatever IP you have set for your HAPROXY in `haproxy/haproxy.cfg` and refresh to see the loadbalancer at work.

> NOTE: It is set to `balance leastconn` in the config , which selects on least connect time, alternativeley you could try `balance roundrobin`.

---
Licensed as MIT, enjoy!
