# Ansible-Deployment-of-Animals-Management-App

## Install Guide w/ Ansible (On your local machine)

1. **Ansible Configuration**
In your **hosts** file write :

  [AWS]
  inv1 ansible_ssh_host=*[PUBLIC_IP_OR_DNS]*

*If you don't know where the file is, check on **/etc/ansible/ansible.cfg***

2. **Pull GIT**
On your terminal do :
git clone https://github.com/baptisteivol/Ansible-Deployment-of-Animals-Management-App.git

3. Execute Deployment (Commands)
Then, inside the correct folder (The one who was created by git) and on your terminal do :
ansible-playbook *[PATH]*/Deployment.yml

4. **How to test the app ?**
With browser, go to :
http://*[PUBLIC_IP_OR_DNS]*

Then, you can add/edit/delete Animals in/from the DB
