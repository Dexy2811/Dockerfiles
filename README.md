# Dockerfiles

A place for all my dockerfiles and docker compose files.



EZ-Wireguard image must have these values modified:

    - WG_HOST=YourHostIP

    - PASSWORD=YourAdminPassword

    - WG_PORT=YourPortOfChoise

    - WG_ALLOWED_IPS=YourSubnet/Subnetmask

networks: YourNetwork


Default UptimeKuma image configured to run on bridge network and integrate with docker socket
