# ghost-nginx-http3-docker-compose
[Ghost](https://hub.docker.com/_/ghost/) + Nginx + HTTP/3 powered by [Quiche](https://github.com/cloudflare/quiche) in Docker Compose

![Ghost with HTTP/3](doc_assets/ghost-with-http3.png)
(`http/2+quic/99` means HTTP/3)

## Run

1. Should set `server.crt` and `server.key` in `docker-compose.yml` properly
2. `docker-compose up`
