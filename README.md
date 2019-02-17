# api-example-infra

Automated infrastructure example project for local environments with Vagrant + Docker + Compose + Ansible.

## Environment execution 

```
vagrant up
ansible-playbook --private-key=.vagrant/machines/default/virtualbox/private_key -i setup/hosts setup/server.yml
```
NOTE: The infrastructure is configured for Centos 7, when not using the box vagrant it is necessary to execute ansible in similar environment.
