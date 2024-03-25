# System Storage Configuration

1. Introduction

   This project aims to automate the management of storage configurations on remote hosts using Ansible playbooks. It includes tasks for creating and deleting logical volumes, ensuring proper partitioning, volume groups, filesystems, and mounting points.

2. Technology Used

   - Ansible

3. Features

   - Feature 1: Create logical volumes and configure storage settings.
   - Feature 2: Delete logical volumes and clean up storage configurations.
   - Feature 3: Ensure correct partitioning, volume groups, filesystems, and mounting points.

4. Usage

   To use this project, follow these steps:
   - Step 1: Ensure Ansible is installed on your system.
   - Step 2: Configure the `ansible.cfg` file as needed.
   - Step 3: Update the `inventory` file with the IP addresses of your managed hosts.
   - Step 4: Run the playbook `storage1.yml` using the command: `ansible-playbook storage1.yml`.
   - Step 5: Run the playbook `storage.yml` using the command: `ansible-playbook storage.yml`.

5. Installation

   To install and set up this project, follow these steps:
   - Step 1: Clone the repository to your local machine.
   - Step 2: Ensure Ansible is installed on your system.
   - Step 3: Configure the `ansible.cfg` file according to your requirements.
   - Step 4: Update the `inventory` file with the IP addresses of your managed hosts.
   - Step 5: You're now ready to use the project as described in the Usage section.
