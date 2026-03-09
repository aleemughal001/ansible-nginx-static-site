# Ansible Nginx Static Site Deployment

## Overview
This project demonstrates how to use Ansible to:
- Configure a master node and connect to multiple servers
- Install and start Nginx on target servers
- Deploy a static HTML page to a production environment

## Inventory
- `servers`: general purpose nodes
- `prod`: production node hosting the static site

## Usage
```bash
ansible-playbook install_nginx_play.yml
ansible-playbook deploy_static_page_play.yml

## Result
The production server serves the static site:

<img width="1851" height="851" alt="Screenshot" src="https://github.com/user-attachments/assets/7e8bd066-bec5-4dc4-be00-e9ee51e6f5ed" />
