# cookiecutter-vagrant-ansible

[Cookiecutter](https://github.com/audreyr/cookiecutter) template to start using [Vagrant](http://vagrantup.com) + [Ansible](http://ansible.com).

* Free software: BSD license
* Creates a basic Vagrantfile with sensible defaults for using Ansible
* Creates a standard provisioning directory with roles, vars, handlers, etc.

## Usage

* This template assumes you have a recent version of [Vagrant](http://vagrantup.com) and
[Ansible](http://ansible.com), and you know how to use them.
* Uses the 'centos/7' box by default.

```
cookiecutter gh:inhumantsar/cookiecutter-vagrant-ansible
```

Finally:

* Customize the `Vagrantfile` as needed.
* Update `vars.yml` and `playbook.yml` as needed.
* Add roles directly or with `roles/requirements.yml`.
* Start the VM with `vagrant up`

## Credits

Originally forked from https://github.com/MSA-Argentina/cookiecutter-vagrant-ansible