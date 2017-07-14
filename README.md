# icinga2-api-ansible-playbook
This playbook work as follow
- copy bash scripts to remote system
- set icinga2 api environmental variables
- execute bash script

To check icinga2-api go to https://github.com/pkhadka56/icinga2-api

It can be run for one host as

$ ansible-playbook -i inventory.ini -l web2 sites.yml
