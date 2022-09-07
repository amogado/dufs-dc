# Installation
. To get the DUFS server running you just have to run the following command.
docker-compose -f production.docker-compose.yml up -d
## Informations
. The DUFS server will be available through the port number 5000.
. If you don't have a firewall up, running and configured the right way, this port 5000 will be available from your network. DUFS access is not securized by default (just need configation).
. You can read here for more informations: https://github.com/sigoden/dufs#access-control .
