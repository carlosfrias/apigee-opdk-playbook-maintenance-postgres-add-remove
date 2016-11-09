Apigee Maintenance Playbook - Add or Remove a Postgresql Node
=============================================================

This playbook provides maintenance assistance for the tasks of 
adding or removing a postgresql node. Two playbooks are provided. The first 
playbook called postgresql-add.yml will register a postgresql node with analytics. 
The second playbook called postgresql-remove.yml will de-register a postgresql node
with analytics. 


Usage Instructions
==================

These are ansible playbooks and require ansible.

1. Please install and configure ansible as indicated in [opdk-setup-ansible](https://github.com/carlosfrias/apigee-setup-ansible).
1. `ansible-galaxy install -f -r requirements.yml`
1. `ansible-playbook -i <inventory file or folder> [postgresql-add.yml | postgresql-remove.yml] -e hosts=<qpid host>`

