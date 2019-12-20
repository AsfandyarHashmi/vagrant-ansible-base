# Vagrant Ansible Base

## Description

Just a simple setup of Vagrant with Ansible. Based on [Andre Lohmann's](https://github.com/andrelohmann) setup.

## Usage

### Configuration

Rename ```config.yml.example``` to ```config.yml``` and edit the variables (if you need to).

Rename ```ansible_vagrant/custom_vars.yml.example``` to ```ansible_vagrant/custom_vars.yml``` and edit the variables (if you need to).

### Usage

Bring up the machine with ```vagrant up```.

If you do not change the variable in ```config.yml```, the virtual machine can be accessed at ```http://vagrant.local``` or ```192.168.213.213```.

You can SSH into the machine and start development by using ```vagrant ssh```.