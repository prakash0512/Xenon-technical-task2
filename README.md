# Xenonstack Technical Task2
# sysopctl

sysopctl is a Bash utility script that helps manage various system operations such as service management, disk usage monitoring, process monitoring, system logs analysis, and system backups.

## Version
Current version: v0.1.0

## Features

- *Service Management*: Start, stop, and list system services using systemctl.
- *System Load Monitoring*: Check the current system load averages.
- *Disk Usage*: View disk usage in human-readable format.
- *Process Monitoring*: Monitor real-time system processes.
- *System Logs Analysis*: Display recent critical log entries.
- *Backup*: Backup files from a specified path using rsync.

## Prerequisites

Before you begin, make sure your system meets the following requirements:
- The linux system(e.g., CentOS, Ubuntu, etc.)
- `journalctl` installed(for log analysis)
- rsync installed(for backups)

## Installation

-- git clone
https://github.com/prakash0512/Xenon-technical-task2.git



## Permissions
chmod +x sysopctl.sh

## Output:

chmod +x sysopctl.sh
Usage
Run sysopctl with the appropriate options and commands.

## Section A
-- Manual page

- *Command* ./sysopctl.sh man
![WhatsApp Image 2024-10-22 at 20 39 49](https://github.com/user-attachments/assets/51c71d7a-c6d6-4da9-89db-1c68b2c6a29f)

- - Help Option
  - *command* ./sysopctl.sh --help

![WhatsApp Image 2024-10-22 at 20 40 41](https://github.com/user-attachments/assets/2456583f-acb7-48b5-8538-f4e4967972f2)
 
  - -Version Info
 
  - *Commmand* ./sysopctl.sh --version
  - ![version](https://github.com/user-attachments/assets/1427e1bf-5eb2-49b6-9b58-5f43111e4b23)
 



## Section B
## Part1
- List Running Services:
- *Command*: $./sysoptcl service list
![part1 list Running services](https://github.com/user-attachments/assets/36b5fdfa-9269-4045-8890-54b5fef9068d)


- *Command*: $./sysoptcl system load
- ![part 1 view system load](https://github.com/user-attachments/assets/eef2f6cf-dcdd-46b1-852f-300f13cb725b)
- 
## Part2
-- Manage System Services:
- *Command*: $./sysopctl.sh service start apache2

![part 2 manage system service](https://github.com/user-attachments/assets/37d13cb4-d0cc-4a3e-acaa-c5e80538b53c)
- 

-- Check Disk Usage

- *Command* $./sysopctl.sh disk usage
- ![part 2 check disk usage](https://github.com/user-attachments/assets/d6ee1486-9167-4b06-92e3-2b6f1f07ca1d)

  ## Part 3
   - Monitor System Processes
   - *Command* $./sysopctl.sh process monitor
   - 
  ![part 3 monitor system process ](https://github.com/user-attachments/assets/823b47b8-a650-4c32-b216-8aff7e2bd425)

 - Analyze Sysem Logs:
 - *Command* $./sysopctl.sh logs analyze
 - ![part 3 analyze system logs](https://github.com/user-attachments/assets/f6b42770-b65f-4c08-a1e0-27ad01754f05)

 - Backup System Files
 - *Command* ./sysopcl.sh Backup /Home/sarthak/desktop/sysopctl.sh
 - 

 - 

![part 3 backup system files](https://github.com/user-attachments/assets/699fafb5-65b0-47e9-820a-f72b4e9e8632)
