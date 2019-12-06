# Ansible-Deployment-of-Animals-Management-App

## Install Guide w/ Ansible (On your local machine)

1. Ansible Configuration
* In your **hosts** file write :

  [app]
  inv1 ansible_ssh_host=*PUBLIC_IP_OR_DNS*


* In **group_vars** file write :

  \---
  ansible_ssh_user: ubuntu

*If you don't know where the files are check on **/etc/ansible/ansible.cfg***

2. Create a folder

3. Download all the file in :
https://github.com/baptisteivol/Animals_Management/tree/master/ansible

4. Commands
* ansible-playbook app.yml
