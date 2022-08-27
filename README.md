# PHP and NODEJS with NGINX

Created with this [tutorial](https://adamtheautomator.com/nginx-reverse-proxy-docker/).

## what are we doing?

proxy both a PHP-FPM and NodeJS at the same time with nginx

## bring it up/down

### up

```bash
docker-compose up -d
```

### down

```bash
docker-compose down
```

## make changes

```bash
docker-compose build web
docker-compose up -d
```

## test it

```bash
curl http://localhost:8080/index.js
curl http://localhost:8080/index.php
```
