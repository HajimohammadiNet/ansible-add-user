# ansible-add-user

# Create User With Ansible
Supported OS: 
  Ubuntu

# Ansible Playbook Command Syntax:
ansible-playbook create-user.yml -l <host_IP> -u <User_Name> -kK --extra-vars "username= fullname="

# How to Set Password?
For set password you must add hash of your password in the tasks file (in password attribute). You can use mkpasswd tool for create you password hash.
