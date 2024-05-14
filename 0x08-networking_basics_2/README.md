Networking Basics #1
This project, part of the DevOps and SysAdmin curriculum, aims to deepen your understanding of networking fundamentals. By completing this project, you'll grasp key concepts like localhost, IP addressing, and network configuration. Let's dive in!

Project Overview
Duration: May 8, 2024, 5:00 AM - May 10, 2024, 5:00 AM
Auto Review: Scheduled upon deadline
Quality Assessment:
Mandatory: 0.0/3
Optional: 0.0/1
Total: 0.0%
Learning Objectives
By the end of this project, you should be able to explain:

The significance of localhost (127.0.0.1)
The purpose of 0.0.0.0
The role of the hosts file (/etc/hosts)
How to display active network interfaces on your machine
Resources
Before diving into the tasks, familiarize yourself with the following resources:

What is localhost?
What is 0.0.0.0?
Understanding the hosts file
Exploring Netcat examples
Requirements
Environment: Ubuntu 20.04 LTS
Editors: vi, vim, emacs
File Format: All files must end with a new line
Documentation: A README.md file at the project's root folder is mandatory
Script Execution: All Bash script files must be executable
Shellcheck: Ensure your Bash scripts pass Shellcheck (version 0.7.0)
Shebang: Start each Bash script with #!/usr/bin/env bash
Commenting: Add a comment explaining the script's purpose as the second line
Tasks
Change your home IP

Objective: Configure an Ubuntu server to meet specific IP resolution requirements for localhost and facebook.com.
Example: Before running the script, localhost resolves to 127.0.0.1 and facebook.com resolves to a different IP. After running the script, localhost resolves to 127.0.0.2 and facebook.com resolves to 8.8.8.8.
Instructions: Implement a Bash script to achieve the desired IP configurations.
Show attached IPs

Objective: Develop a Bash script to display all active IPv4 IPs on the executing machine.
Example: Upon execution, the script should display active IPv4 addresses, including localhost.
Instructions: Write a Bash script that effectively lists all active IPv4 IPs.
Repository
GitHub: alx-system_engineering-devops
Directory: 0x08-networking_basics_2
Files: 0-change_your_home_IP, 1-show_attached_IPs