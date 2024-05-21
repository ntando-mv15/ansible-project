# Ansible Nginx Setup Project
## Overview
This Ansible project automates the installation and configuration of Nginx on a target server. The primary objectives are to ensure Nginx is installed, verify that it is running, and copy a specified Nginx configuration file to the appropriate directory.

## Project Goals
- Install Nginx: Automate the installation of the Nginx web server.
- Verify Nginx Status: Check if Nginx is running after installation.
- Configure Nginx: Copy a custom Nginx configuration file to the target server.

## How It Works
1. **Install Nginx:** The playbook includes tasks to install Nginx using the package manager appropriate for the target system.
2. **Check Nginx Status:** The playbook verifies that the Nginx service is active and running.
3. **Copy Configuration File:** The playbook copies a pre-defined Nginx configuration file from the local system to the target server's Nginx configuration directory.

## Requirements
- Ansible 2.9+ installed on the control node.
- Target nodes should be accessible via SSH with necessary permissions for Ansible operations.
- Custom Nginx configuration file ready for deployment.