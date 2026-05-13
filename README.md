# Linux & Python Automation Labs

Hands-on Linux and Python automation lab focused on operational troubleshooting, service validation, monitoring, and automation tasks commonly used in IT support and infrastructure environments.

This repository documents practical exercises designed to strengthen Linux administration, scripting, and operational problem-solving skills through simulated real-world scenarios.

---

# Objectives

- Practice Linux administration and troubleshooting fundamentals
- Automate repetitive operational tasks using Python and Bash
- Simulate monitoring and service validation workflows
- Develop troubleshooting and log analysis skills
- Build foundational knowledge for Infrastructure, IT Operations, and DevOps-oriented roles

---

# Lab Environment

- Ubuntu 22.04 virtual machines
- CLI-based troubleshooting and diagnostics
- Local service simulations
- Cron-based task scheduling
- Git & GitHub for version control

---

# Project Structure

## 🟢 Level 1 — Linux & Automation Fundamentals

### Welcome Script
Basic Python input/output and terminal interaction.

### Basic Calculator
Functions, conditionals, and basic arithmetic operations.

### Bulk File Renaming
Automation script for batch file renaming operations.

### Duplicate File Detector
Script to identify duplicate files within directories.

### Local Backup with Logs
Automated local backup process with logging functionality.

---

## 🟡 Level 2 — Monitoring & Operational Tasks

### Multi-Host Connectivity Checker
Ping-based connectivity validation for multiple hosts.

### Disk Space Monitor
Disk usage validation and threshold monitoring.

### REST API Consumer
Interaction with public APIs using Python and JSON parsing.

### Scheduled Tasks with Cron
Automation of recurring operational tasks using cron jobs.

### Log File Analyzer
Regex-based log analysis for identifying errors, warnings, and operational anomalies.

---

## 🔴 Level 3 — Linux Operations & Troubleshooting

### Service Status Checker
Validation of Linux services such as Nginx, MySQL, and SSH.

### Bulk Git Repository Cloner
Automation tool for cloning multiple Git repositories.

### Configuration File Comparator
Script for identifying differences between configuration files.

### Secure Password Generator
Randomized password generation using Python.

### Service Connectivity Validator
Port validation and connectivity testing for simulated services.

---

# Technologies & Tools

- Python 3
- Bash scripting
- Linux (Ubuntu 22.04)
- Git & GitHub
- Cron
- CLI networking tools

### Python Libraries

- os
- subprocess
- shutil
- logging
- re
- requests
- json
- psutil

---

# Example Outputs

## Log Analyzer

```txt
Log stats:
ERROR: 44
INFO: 99
WARNING: 42
DEBUG: 15

ERROR lines:

2025-09-20 13:00:00 ERROR OverflowError en cálculo de cuotas (request_id=9845)
2025-09-20 13:01:09 ERROR Timeout en servicio externo
2025-09-20 13:01:32 ERROR OverflowError en cálculo de cuotas
2025-09-20 13:05:22 ERROR No se pudo conectar a la base de datos (request_id=8977)
2025-09-20 13:12:16 ERROR Excepción en módulo auth: IndexError


OK: nginx service is active

FAIL: mysql service is inactive. Attempting restart...
Failed to restart mysql.service: Unit mysql.service not found.
Unable to restart mysql service in test environment.

FAIL: ssh service is inactive. Attempting restart...
Failed to restart ssh.service: Unit ssh.service not found.
Unable to restart ssh service in test environment.

## About
This repository was created as part of my personal learning roadmap to DevOps/SRE.
It demonstrates progression from Python fundamentals to system monitoring, service reliability, and automation tasks.
The goal is to showcase practical exercises that build the foundation for a career in DevOps/Site Reliability Engineering (SRE).

Author: Marco Antonio Morales Suárez


