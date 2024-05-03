# Dockerfiles

A place for all my docker files.



All images are restart=always

The satisfactory image is based on: [wolveix/satisfactory-server:latest](https://github.com/wolveix/satisfactory-server "https://github.com/wolveix/satisfactory-server")


The Authentic stack image is from Ibracrop and modified a bit to be more stable: [IBRACORP website](https://docs.ibracorp.io/authentik/authentik/docker-compose/docker-compose-install)


Homarr image is default not configured


EZ-Wireguard image must have these values modified:

    - WG_HOST=YourHostIP

    - PASSWORD=YourAdminPassword

    - WG_PORT=YourPortOfChoise

    - WG_ALLOWED_IPS=YourSubnet/Subnetmask

networks: YourNetwork


Default UptimeKuma image configured to run on bridge network and integrate with docker socket
