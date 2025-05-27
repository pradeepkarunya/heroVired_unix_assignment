# Task2
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
