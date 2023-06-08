# docker-unifi-controller

Refer to: https://docs.linuxserver.io/images/docker-unifi-controller


### Install Instructions
```bash
git clone git@github.com:FinchTechSoCal/docker-unifi-controller.git ~/docker-files/unifi-controller
cd  ~/docker-files/unifi-controller
mkdir ~/appdata/unifi-controller

ln -s /home/finchtech/docker-files/env/ft-cloud-1.prod.env /home/finchtech/docker-files/unifi-controller/.env

docker-compose up -d
```