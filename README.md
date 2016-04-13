# Sporting Goods Catalog app - Amazon AWS Server information
This project contains information on how an Amazon AWS instance was configured to host a [Sporting Goods Catalog app](https://github.com/prestononeal/sporting_goods_catalog_app), developed for a previous project. The goal of this project was to configure a Linux web server to securely host a web app.

## IP address
`52.38.237.92`

## Port

## Software installed and configuration changes
1. Installed package `finger`
2. Installed package `apache2`
3. Installed package `libapache2-mod-wsgi`
4. Installed package `postgresql`
5. Installed package `git`
5. Installed setuptools
6. Installed pip

## Third party resources
1. SSH configuration: https://help.ubuntu.com/community/SSH/OpenSSH/Configuring
2. A virtual environment was created and configured using the steps here: http://askubuntu.com/questions/244641/how-to-set-up-and-use-a-virtual-python-environment-in-ubuntu. A new virtual environment was created called `catalogenv` was created in the Apache root, along with the cloned Catalog app.