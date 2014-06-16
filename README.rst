============================
cookiecutter-vagrant-ansible
============================

Cookiecutter template to start using Vagrant + Ansible. For more info on cookiecutter
see https://github.com/audreyr/cookiecutter.

* Free software: BSD license
* Creates a stripped Vagrantfile with sensible defaults for using Ansible
* Creates a standard provisioning directory with roles, vars, handlers, etc.
* Includes a role to bootstrap an Ubuntu Server using sensible defaults. This role can be
used a basis to create your own roles. Also, check Ansible Galaxy (http://galaxy.ansible.com).

Usage
-----
* This template assumes you have a recent version of Vagrant (http://vagrantup.com) and
Ansible (http://ansibleworks.com), and you know how to use them.
* Also assumes you have a box named 'base' installed.
* If you have all that, then:

Create a directory somewhere and cd to it.

Now generate the skeleton:

    cookiecutter https://github.com/MSA-Argentina/cookiecutter-vagrant-ansible.git

Finally:

* Customize the Vagrantfile, ansible_hosts, vars.yml and the two roles: common and application
* Start the VM with vagrant up
