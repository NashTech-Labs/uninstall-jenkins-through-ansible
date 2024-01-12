# Uninstall Jenkins Ansible Playbook

This Ansible playbook is designed to uninstall Jenkins from a specified server.

## Prerequisites

- Ansible installed on the machine where you plan to execute the playbook.
- SSH access to the target server.
- Appropriate privileges to execute commands with sudo.
## Playbook Details
The Ansible playbook (uninstall_jenkins.yaml) consists of the following tasks:

1. Stop Jenkins Service
2. Remove Packages
3. Remove Files
## Usage 
1. Clone this repository to your local machine:

   ```bash
   git clone <repository-url>
2. Change directory:
   
   ```bash
   cd <playbook-directory>
4. Run playbook:
   
   ```bash
   ansible-playbook -i <path-to-inventory-file> <path-to-playbook-file>
