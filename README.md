Cosas
1. Crear el server en hetzner
```bash
apt update -y && apt upgrade -y

# https://docs.docker.com/engine/install/debian/

systemctl start docker
systemctl enable docker

docker network create nginx-proxy


```
