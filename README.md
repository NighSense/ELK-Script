ansible-playbook-ELK Script

A script for setting up the ELK clusters on AWS Servers

###Instructions###

1 Install Ansible on Host Machine
  Follow this link for instruction:https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html#intro-installation-   guide
  
2 Setup 5 remote EC2 CentOS Instances on AWS (Three for Elastic Search and 1 each for Kibana and Logstash)

3 Connect host machines through SSH with ansible command line. Please follow the instruction of ssh setup on remote hosts provided in ssh connection file.

4 On host machine edit your Ansible hosts file ('/etc/ansible/hosts') and replace the hostname or IP Address  of EC2 Instances. Edit the inventory file provided with this script and put the content into the host file located on  ('/etc/ansible/hosts').

In the terminal on the machine hosting Ansible, clone this repo.
cd into the directory, and run: ansible-playbook deploy.yml

The plays in the playbook will run on the target server, installing ELK.
