# Ansible 

## Prerequirements 
#### Debian distributions
Update your package list:
`sudo apt update`
Install Ansible
`sudo apt install ansible -y`
#### Redhat distributions
Enable the EPEL repository:
`sudo yum install epel-release -y`
Install Ansible:
`sudo yum install ansible -y`

#### Provide your own configuration
Fill hosts-vagrant with your own configuration

## How to run playbook 

`ansible-playbook -i hosts_vagrant docker-instalation-playbook.yml`
