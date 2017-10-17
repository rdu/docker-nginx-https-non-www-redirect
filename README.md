## docker-nginx-https-non-www-redirect

A simple nginx container that redirects http requests to https without the www (if present).

Useful to be used as a default backend for Load Balancers (like the Rancher one).

[Docker Hub](https://hub.docker.com/r/iamfreee/docker-nginx-https-non-www-redirect/)

Very small size: ~7 MB (alpine based). Uses about 2 MB RAM when running.

## Instructions

**Image:**

Use the this image: `iamfreee/docker-nginx-https-non-www-redirect:latest` as the container image.

## License
MIT
