Here are all of my ansibles projects.

1. tp_playbooks: How to set up a playbook
2. tpvar: How to set up variables
3. tproles: How to insert roles
4. tploop: How to automate my task
5. tpsecret: How to crypt my files.
6. tpapache: How to set up an apache server with ansible
7. ansible_lamp: A project which goal is to set up an apache server, a mysql database server and a php server, 
bind them together, and using ansible to do it.


# ansible_lamp

use this command from tpapache

Commande:

ansible-playbook --vault-id @prompt --vault-password-file=playbooks/vars/secret.yml -i host3 playbooks/main.yml

Vault password: toto

