ansible-playbook-ELK Script

A playbook for setting up the ELK Stack + Filebeat

Instructions

Edit your Ansible hosts file ('/etc/ansible/hosts') and add an 'hostname' entry for the server you wish to install ELK on. You can of course name the host any way you want, this is just an example.
In the terminal on the machine hosting Ansible, clone this repo.
Cd into the directory, and run: ansible-playbook site.yml
The plays in the playbook will run on the target server, installing ELK and filebeat.
