# Gestion letsencrypt, server linux
## certbot
### installation
```sh
add-apt-repository ppa:certbot/certbot
apt-get install certbot python-certbot-apache
```
### test fake
```sh
certbot --apache --test-cert --dry-run
```
