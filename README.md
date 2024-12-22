# User Management and Backup Shell Script

## Overview

This shell script automates user management tasks and backup processes in a Linux environment. It provides a menu-driven interface to perform operations such as adding, deleting, or modifying users, managing groups, and backing up directories with a rotation policy. The primary goal is to enable efficient management of user accounts and secure backup of specified directories.

## Features

### User Management
- Add new user accounts.
- Delete existing user accounts.
- Modify user account attributes (password, shell, home directory, lock/unlock).
- Create and delete groups.
- Add users to groups or remove users from groups.

### Backup Management
- Compress and archive a specified directory into a `.zip` file.
- Automatically manage backups using a rotation policy to keep only the latest 5 backups.

### User-Friendly Interface
- Interactive menu-driven command-line interface.
- Clear prompts and instructions for each operation.

## Requirements

### Functional Requirements
- Perform user and group management tasks.
- Backup directories with automation and rotation policies.

### Non-Functional Requirements
- **Performance**: Swift and efficient execution.
- **Security**: Requires `sudo` privileges for critical operations.
- **Portability**: Compatible with most Linux distributions.

## Prerequisites
- Linux OS with Bash shell.
- `sudo` privileges for user and group management.
- `zip` package installed (the script can install it automatically if missing).

## Usage

To use the script, follow these steps:
```bash
# 1. Clone the repository:
   git clone https://github.com/<your-username>/<repo-name>.git
#2. Navigate to the project directory:
    cd <repo-name>
#3. Make the script executable:
    chmod +x script.sh
#4. Run the script:
    ./script.sh
```
