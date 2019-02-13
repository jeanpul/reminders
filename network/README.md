# Gestion letsencrypt, server linux
## certbot
### installation
```sh
add-apt-repository ppa:certbot/certbot
apt-get install certbot python-certbot-apache
```
### docker update
```sh
docker pull certbot/certbot
```
### test fake
```sh
certbot --apache --test-cert --dry-run renew
```
