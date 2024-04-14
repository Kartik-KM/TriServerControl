#TriServerControl
Automating Server Management with Ansible
Problem Statement:
In this project, I aimed to automate the management of three servers using Ansible. The task involved setting up a master server and connecting it with three common servers on AWS EC2 instances.

Project Overview:
Server Setup: I created four virtual machines (EC2 instances) on AWS: one master server and three common servers.
Configuration: The master server housed Ansible, which served as the central control system for managing the other servers.
SSH Connection: Using a PEM file generated for me, I established SSH connections between the master server and the common servers effortlessly.
Ansible Installation: After connecting to the master server via SSH, I updated the Ubuntu machine and installed Ansible.
Host Configuration: I updated the host file in Ansible, listing the IP addresses of the three common servers, enabling seamless connections.
Variable Management: Utilizing variables, I ensured different permissions were assigned to each server without repetitive authorization.
Push-based Mechanism: Employing a push-based approach, I executed updates and installations across all servers simultaneously, saving time and effort.
Ansible Playbooks: To streamline processes, I leveraged Ansible playbooks, encapsulating predefined functions and methods for efficient server management.
Demonstration with Nginx: As a practical demonstration, I deployed a static website using Nginx and showcased its upload to one of the servers (Server-3 IPv4 address).
