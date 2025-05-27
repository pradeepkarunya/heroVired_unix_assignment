# heroVired_unix_assignment

# Task 1
# System Monitoring Setup

## Tools Installed
- htop
- nmon
- df, du
- ps

## Log Directory
Logs saved under `/var/log/devops`

## Scripts
- `/usr/local/bin/system_monitor.sh` – Collects and logs CPU, memory, disk, and process usage

## Automation
- Cron runs the script hourly to track system metrics

## Usage
Run `htop` or `nmon` for live view. Use logs for historical analysis.

# Task 2
# User Management and Access Control

## Users Created
- Sarah
- mike

## Home and Workspace Directories
- Sarah: /home/Sarah/workspace
- mike: /home/mike/workspace

## Directory Permissions
- Owner: User
- Permissions: 700 (full access to owner only)

## Password Policy
- Expiry: Every 30 days
- Complexity Rules:
  - Minimum length: 10
  - Must contain uppercase, lowercase, digit, and special character

## Commands Used
- useradd, passwd
- mkdir, chown, chmod
- chage
- Edited: /etc/security/pwquality.conf and /etc/pam.d/common-password
