Bamboo basic vagrant
==============

This vagrant has a basic installation of lamp platform to run bamboo e-commerce


Installation
------------

To provisioning virtual machines this vagrant uses ansible. Installation documentation of [ansible](http://docs.ansible.com/intro_installation.html) and to install [vagrant](http://docs.vagrantup.com/v2/installation/).

	
Usage
-----

To create virtual machine:

	vagrant up

To only provisioning virtual machine:

	vagrant provision
	

Modules installed
-----------------

* composer
* git
* mysql
* nginx
* php5
    - php-pear
    - php5-cli
    - php5-gd
    - php5-fpm
    - php5-mysql
    - php5-imagick
    - php5-redis
    - php5-curl
    - php5-intl
* redis