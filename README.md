# Sporting Goods Catalog app - Amazon AWS Server information
This project contains information on how an Amazon AWS instance was configured to host a [Sporting Goods Catalog app](https://github.com/prestononeal/sporting_goods_catalog_app), developed for a previous project. The goal of this project was to configure a Linux web server to securely host a web app.

## IP address
`52.38.237.92`

## Port
80

## Server software installed and configuration changes
These Ubuntu packages were installed in order to get server functionality up:

1. `finger`
2. `apache2`
3. `libapache2-mod-wsgi`
4. `postgresql`
5. `git`
5. `python-pip`
6. `python-virtualenv`
7. `libpq-dev`
8. `python-dev`

## Python package dependencies for the catalog app
These packages were installed in order to run the catalog app:

7. `flask`
8. `sqlalchemy`
9. `oauth2client`
10. `requests`
11. `bleach`

## Third party resources
1. SSH configuration: https://help.ubuntu.com/community/SSH/OpenSSH/Configuring
2. A virtual environment was created and configured using the steps here: http://askubuntu.com/questions/244641/how-to-set-up-and-use-a-virtual-python-environment-in-ubuntu. A new virtual environment was created called `catalogenv` was created in the Apache root, along with the cloned Catalog app.
3. For installing the `psycopg2` python package, I needed to install as specified here: http://stackoverflow.com/questions/5420789/how-to-install-psycopg2-with-pip-on-python