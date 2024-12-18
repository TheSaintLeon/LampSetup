![Bash Script](https://img.shields.io/badge/bash_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)![Proxmox](https://img.shields.io/badge/proxmox-proxmox?style=for-the-badge&logo=proxmox&logoColor=%23E57000&labelColor=%232b2a33&color=%232b2a33)![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
# LAMP Setup Repository

## Overview
This repository contains bash scripts to automate the installation and setup of a LAMP (Linux, Apache, MySQL, PHP) stack, making it easy to quickly set up a web development environment.

## Repository Contents
- `setup_lamp.sh`: Main script for installing LAMP stack components
- `makexec.sh`: Script to make other scripts executable
- `runcode.sh`: Execution script for the LAMP setup process

## Prerequisites
- Linux operating system (Ubuntu/Debian recommended)
- Sudo or root access
- Internet connection
- Git 

## Installation
1. Clone the repository
```bash
git clone https://github.com/TheSaintLeon/LampSetup.git
```
2. Navigate to the repository directory
```bash
cd LampSetup
```
3. Make the scripts executable
```bash
chmod +x ./makexec.sh && ./makexec.sh
```
4. Make the scripts executable
```bash
chmod +x ./runcode.sh && ./runcode.sh
```

## Components Installed
- Apache Web Server
- MySQL Database
- phpMyAdmin
- PHP

## Troubleshooting
- Ensure you have sudo privileges
- Check internet connection
- Verify no conflicting web servers are running

## Contributing
Contributions are welcome. Please open an issue or submit a pull request.
