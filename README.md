ansible-playbook-ELK Script

A script for setting up the ELK clusters on AWS Servers

###Instructions###

1 Install Ansible on Host Machine
  Follow this link for instruction:https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#intro-installation-   guide
  
2 Setup 5 EC2 CentOS Instances on AWS (Three for Elastic Search and 1 each for Kibana and Logstash)

3 Connect host machines through SSH with ansible command line

4 On host machine edit your Ansible hosts file ('/etc/ansible/hosts') and replace with inventory file provided with this script. You can of course name the host any way you want, this is just an example.

In the terminal on the machine hosting Ansible, clone this repo.
Cd into the directory, and run: ansible-playbook deploy.yml

The plays in the playbook will run on the target server, installing ELK.
