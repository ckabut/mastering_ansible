# mastering_ansible
This repository is used to create a full ansible environement (control, loadbalancer, web app, database) using docker.
Very usefull if you want to train yourself with ansible on your local machine in your local machine

Instructions:
1 git clone
2 docker-compose build && docker-compose up &
3 ssh control

in the control container, all playbooks are in /etc/ansible/playbooks

Playbooks:
site.yml = configure all the hosts
stack_status.yml = get the status of all hosts
stack_restart.yml = restart all servers

Enjoy !
