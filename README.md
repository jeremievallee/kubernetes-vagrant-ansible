# kubernetes-vagrant-ansible
Install Kubernetes on Vagrant using Ansible.

## Requirements

- Vagrant
- Virtualbox
- Ansible

## Steps

First, create the machines.

```
vagrant up
```

Then, provision the machines.

```
ansible-playbook playbook.yml -i inventory -e @vars.yml
```
