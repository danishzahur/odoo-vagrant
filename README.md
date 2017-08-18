# odoo-vagrant

Vagrant Setup for Odoo 10 on Ubuntu 16.04

Dependencies
------------

* [VirtualBox](https://www.virtualbox.org/wiki/Downloads)
* [Vagrant](https://www.vagrantup.com)

Setup
-----

* Download and install Virtual Box

* Download and install Vagrant

* Clone this repo

```
git clone https://github.com/danishzahur/odoo-vagrant.git
```

* Start virtual machine

```
cd odoo-vagrant
vagrant up
```

* Login in the virtual machine

```
vagrant ssh
```

* To restart odoo service

```
sudo service odoo restart
```

* Open your browser and go http://localhost:8069

Shared folders
--------------
src/my_addons is mapped to /home/vagrant/my_addons, you can write your modules in this directory


pgAdmin 
-------
If you want manage the postgresql server from your desktop, you only have to connect to localhost, username and password is 'admin'
