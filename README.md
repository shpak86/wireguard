# Wireguard server config

Wireguard server configuration.

## Configuration

To create a container and start the wireguard server run `docker-compose up -d`. Visit https://www.wireguard.com/ to download a client.
To generate a QR code for a new peer run `docker exec -it wireguard /app/show-peer N` where `N` is a number of the peer.
