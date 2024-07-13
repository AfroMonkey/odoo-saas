Cosas
1. Crear el server en hetzner
```bash
apt update -y && apt upgrade -y
apt install -y \
    git \
    vim

# https://docs.docker.com/engine/install/debian/

systemctl start docker
systemctl enable docker


docker network create nginx-proxy


git clone https://github.com/AfroMonkey/odoo-saas

cd odoo-saas/nginx-proxy

docker-compose up -d

cd ../odoo

cp .env-template .env

vim .env

docker-compose up -d
```
