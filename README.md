# Born2beRoot

## Project Description

The `born2beroot` project is part of the School 42 curriculum, aimed at introducing students to system administration concepts and practices. The goal of this project is to set up a virtual machine (VM) with a specific operating system, configure it securely, and manage it as a server, applying various system administration tasks.

## What It Does

The `born2beroot` project involves setting up a virtual machine, configuring its network and security settings, and ensuring it operates as a stable and secure server. You will learn to manage users, configure SSH, set up firewalls, and apply other essential sysadmin practices.

## Implementation Details

- **Operating Systems**:
  - The project can be implemented on Debian-based or Red Hat-based distributions.
- **Virtualization**:
  - Use of virtualization software such as VirtualBox or VMware to create the VM.
- **Key Configurations**:
  - **User Management**: Create and manage users and groups.
  - **SSH Configuration**: Set up and secure SSH access.
  - **Firewall Setup**: Configure firewall rules using `ufw` (for Debian) or `firewalld` (for Red Hat).
  - **Automated Tasks**: Use `cron` jobs for task scheduling.
  - **System Monitoring**: Implement tools to monitor system performance and security.

### How It Works

1. **Setting Up the VM**:
   - Install a chosen Linux distribution on a virtual machine using VirtualBox or VMware.
   - Update and upgrade the system packages to ensure the latest security patches are applied.

2. **User and Group Management**:
   - Create a new user with sudo privileges.
   - Implement strong password policies and manage user permissions.

3. **SSH Configuration**:
   - Install and configure the OpenSSH server.
   - Disable root login and configure key-based authentication.
   - Change the default SSH port to enhance security.

4. **Firewall Setup**:
   - Install and configure `ufw` or `firewalld` to allow only necessary traffic.
   - Set up rules to allow SSH connections and other required services while blocking all other incoming connections.

5. **Automated Tasks with Cron**:
   - Schedule regular system updates and backups using `cron` jobs.
   - Implement monitoring scripts to check system health and resource usage.

6. **System Monitoring**:
   - Install monitoring tools such as `top`, `htop`, or `glances` to observe system performance.
   - Set up log monitoring to track system events and potential security issues.

7. **Documentation**:
   - Document all configurations and settings applied to the VM.
   - Create a comprehensive report detailing the steps taken, configurations applied, and rationale behind each decision.

This project provides hands-on experience with essential system administration tasks, focusing on security, user management, and system monitoring, which are critical skills for managing and maintaining secure and stable server environments.
