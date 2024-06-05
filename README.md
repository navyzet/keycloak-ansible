#Ansible script install keycloak server

Tested on Ubuntu 24.04

Installation:

- Run:

        ansible-galaxy install geerlingguy.nginx geerlingguy.certbot geerlingguy.docker  --force
        ansible-playbook -D play.yml -i inventory --ask-vault-password
