# Vagrant PHP7 

A simple Vagrant LAMP setup running PHP7.

## What's inside?

- Ubuntu 14.04.3 LTS (Trusty Tahr)
- Vim, Git, Curl, etc.
- Apache
- PHP7 with some extensions
- MySQL 5.6
- Node.js with NPM
- RabbitMQ
- Redis
- Composer
- phpMyAdmin
- PHPUnit
- memcached
- mongoDB

## How to use
- Install VirtualBox 
- Install Vagrant 
- Clone this repository into your project
- Run ``vagrant up`` inside the folder on the command line
- Add the following lines to your hosts file:
````
192.168.100.100 app.test
192.168.100.100 phpmyadmin.test
````
- Navigate to ``http://app.test/`` 
- Navigate to ``http://phpmyadmin.test/`` (both username and password are 'root')
