# LibreNms

Docker Compose files for setting up Libre NMS.

## Installing

1. Go inside `/var` directory

``` sh
cd /var
```

2. Clone this repo

``` sh
git clone git@github.com:varmakarthik12/librenms.git
```

3. Move to `/var/librenms`

``` sh
cd /var/librenms
```

4. Make sure you updated the environmental varibles in `.env` files. Now, run
Docker compose to start the contianer with required Volumes
``` sh
docker-compose up -d
```
