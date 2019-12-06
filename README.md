# Ansible-Deployment-of-Animals-Management-App

## Install Guide w/ Ansible (On your local machine)

1. Ansible Configuration
* In your **hosts** file write :

  [AWS]
  inv1 ansible_ssh_host=*PUBLIC_IP_OR_DNS*

*If you don't know where the files are check on **/etc/ansible/ansible.cfg***

2. git clone

4. Commands
* ansible-playbook *PATH*/Deployment.yml
