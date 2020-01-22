# Odoo 13 with Customizable Add-ons and Docker

Change the folder permission to make sure that the container is able to access the directory:
```
$ sudo chmod -R 777 addons
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