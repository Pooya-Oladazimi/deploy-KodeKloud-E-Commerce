## Deploy KodeKloud e-commerce application with Ansible

This Ansible project tends to deploy kodekloud application to a Debian server.

### Project for this Udemy course:

Ansible for the Absolute Beginner - Hands-On - DevOps 

https://www.udemy.com/course/learn-ansible/

Provided by: Mumshad Mannambeth (@mmumshad)


Application stack:

- Debian packages/libraries 
- MariaDB
- Nginx
- The application


### Run

After cloning, run this:

    ansible-playbook playbook.yml  -i inventory.yml -e "ansible_python_interpreter=/usr/bin/python3"


**Note**: the target machine has to be Debian based.