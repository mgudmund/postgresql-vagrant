postgresql-vagrant
==================

PostgreSQL Vagrant files
------------------------

My vagrant files for postgres boxes.

To get started download Virtualbox and Vagrant.

The get the Vagrantfile of choice and run:
> vagrant up

And the box will be downloaded and started as a virtual machine.

To login to the box, do:
> vagrant ssh

To get PostgreSQL up and running:

> sudo su -
> service postgresql-9.3 initdb
> service postgresql-9.3 start
> su - postgres
> export PATH=$PATH:/usr/pgsql-9.3/bin

After this you shouls have a PostgreSQL instance up and running.

