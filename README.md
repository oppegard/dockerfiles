```bash
docker build -t oppegard/rpi-airsonos
docker run --net=host --privileged -ti -p 1400:1400 -p 1900:1900 -p 1900:1900/udp oppegard/rpi-airsonos
docker run --net=host --privileged -ti oppegard/rpi-airsonos
```
