# docker-django-wsgi-nginx
A demo of containerizing  django and nginx with self-signed cert and wsgi.

## Quick start

```
chmod +x gen_cert.sh
./gen_cert.sh # Generate Self-signed ssl cert for nginx
sudo docker-compose up
```

## Features

#### Self sign cert generation:

```
./gen_cert.sh
```

#### WSGI with Gunicorn.

#### Nginx reverse proxy.

#### Static script serving with nginx in `./nginx_files/scripts/`
