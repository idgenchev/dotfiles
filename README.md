# Dotfiles
My environment configuration (only Vim and ZSH for now:)

# Install

## Try it out with [Vagrant](https://www.vagrantup.com/) 

```
vagrant up   # creates and provisions a guest machine, using the ansible_local provisioner
vagrant ssh  # ssh to the guest machine and play around with the environment
```

## Install locally

Prerequisites - [Ansible](https://www.ansible.com/)
```
ansible-playbook playbook.yaml
```
