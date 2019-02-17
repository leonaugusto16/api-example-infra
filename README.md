# api-example-infra

Automated infrastructure example project for local environments with Vagrant + Docker + Compose + Ansible.

## Environment execution 

* Vagrant 2.2.3
* Ansible 2.5.2

```
vagrant up
ansible-playbook --private-key=.vagrant/machines/default/<YOUR_PROVIDER>/private_key -i setup/hosts setup/server.yml
```
NOTE: The infrastructure is configured for Centos 7, when not using the box vagrant it is necessary to execute ansible in similar environment.

## Provider

The centos 7 vagrant box has the following providers:

* virtualbox
* vmware_desktop
* libvirt
* hyperv 

The default of the project is virtualbox. For more information https://app.vagrantup.com/centos/boxes/7
