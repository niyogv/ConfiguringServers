# ConfiguringServers
This repo is an example of how to configure the servers using ansible software. Using this software we can install the dependencies, execute the commands, run scripts.

# About ansible
Ansible is an open source IT automation engine that automates provisioning, configuration management, application deployment, orchestration, and many other IT processes. It is free to use, and the project benefits from the experience and intelligence of its thousands of contributors.

# How it works
It can configure systems, deploy software, and orchestrate advanced workflows to support application deployment, system updates, and more.

Ansible’s main strengths are simplicity and ease of use. It also has a strong focus on security and reliability, featuring minimal moving parts. It uses OpenSSH for transport (with other transports and pull modes as alternatives), and uses a human-readable language that is designed for getting started quickly without a lot of training.

# Requirements
We need two file such as inventory file and the yml file. The inventory file holds the details of hosts such as ip, ssh, username and passwords. The yml file is the main file where we can tell ansible to perform the actions on the machines

# Command to execute
The command to execute ansible 'ansible-playbook -i >inventory file< file name.
This command uses the inventory file to access the machine and execute the commands which we mention in yml file.
