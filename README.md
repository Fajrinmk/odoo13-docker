# Odoo 13 with Customizable Add-ons and Docker

Clone this repository
```
$ git clone https://github.com/Fajrinmk/odoo13-docker.git
```
Change the folder permission to make sure that the container is able to access the directory:
```
$ cd odoo13-docker
$ sudo chmod -R 777 addons
$ sudo chmod -R 777 etc
```
Start the container:
```
$ docker-compose up
```
* Then open `localhost:8069` to access Odoo 13.0
* Log file is printed @ **etc/odoo-server.log**

To run in detached mode, execute this command:

```
$ docker-compose up -d
```

# Custom addons

The **addons** folder contains custom addons. Just put your custom addons if you have any.

# Odoo configuration

To change Odoo configuration, edit file: **etc/odoo.conf**.