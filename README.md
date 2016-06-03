# docker-vagrant

# Introduction


It provides a template Vagrantfile to create an Ubuntu 14.04 LTS virtual machine using the VirtualBox software hypervisor.
After setup is complete you will have a single Ubuntu virtual machine running on your local machine.

## Setup

1) Install dependencies

* [VirtualBox][virtualbox] 5.0.1 or greater.
* [Vagrant][vagrant] 1.8 or greater.

2) Clone this project and get it running!

```
git clone https://github.com/amartellone/docker-vagrant/
cd docker-vagrant
```

3) Startup and SSH

There are two "providers" for Vagrant with slightly different instructions.
Follow one of the following two options:

**VirtualBox Provider**

The VirtualBox provider is the default Vagrant provider. Use this if you are unsure.

```
vagrant up
vagrant ssh
```
