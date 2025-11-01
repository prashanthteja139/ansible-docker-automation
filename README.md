# Ansible Docker Automation

## Overview
This Ansible playbook automates the installation and configuration of Docker Engine across multiple Linux hosts.

## Features
- Installs Docker and dependencies
- Adds Docker’s official GPG key and repository
- Starts and enables the Docker service
- Verifies Docker installation

## Usage
1. Clone the repository  
   ```bash
   git clone https://github.com/<your-username>/ansible-docker-automation.git

2. Update your inventory file:

[all]
server1 ansible_host=<IP_ADDRESS> ansible_user=<USER>


3.Run the playbook:

ansible-playbook -i inventory/hosts.ini playbooks/docker-install.yml
