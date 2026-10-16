Ansible Homelab
Overview

This project uses Ansible to configure two Amazon Linux 2023 EC2 worker nodes.

What This Project Does
Installs Git, Unzip, Tar, Apache, Nginx, and Wget.
Configures Nginx to use port 80.
Configures Apache to use port 8080.
Starts and enables services.
Deploys a custom HTML page using Ansible.

Project Structure
ansible-homelab/
├── hosts.ini.example
├── README.md
└── playbooks/
    └── install_packages.yml

Requirements
Ansible
AWS EC2 instances
SSH access to worker nodes
Usage

Check playbook syntax:

ansible-playbook --syntax-check -i hosts.ini playbooks/install_packages.yml


Run the playbook:

ansible-playbook -i hosts.ini playbooks/install_packages.yml

Technologies
Ansible
AWS EC2
Amazon Linux 2023
Nginx
Apache HTTP Server
Purpose

This project was created for learning Ansible automation and server configuration.

<img width="473" height="421" alt="Screenshot 2026-10-13 142807" src="https://github.com/user-attachments/assets/a9beadc6-c44d-4e5f-a4d3-cbc0db76f7ef" />

<img width="560" height="287" alt="Screenshot 2026-10-13 142743" src="https://github.com/user-attachments/assets/0651954c-0818-4275-9352-2a2686a1b789" />



