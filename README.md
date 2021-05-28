# Install Docker/Docker Compose with Ansible

Install docker/docker-compose in a SO Linux

## Test with Vagrant

Dependencies:

* Vagrant
* Virtualbox

```sh
vagrant up
```

## Install

```sh
ansible-playbook main.yml -i hosts -v
```
