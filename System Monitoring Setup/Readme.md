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
