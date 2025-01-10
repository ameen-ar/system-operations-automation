# System Operations Automation

## Overview
This project demonstrates a comprehensive Linux-based system operation solution using bash scripts. Developed for Sy Institute, it covers resource monitoring, log auditing, automated email alerts for disk usage, and FTP server implementation. The solution enhances system resource management, automates critical tasks, and simplifies file transfer operations.

## Features
- **Real-Time Resource Monitoring**: Track CPU, RAM, disk usage, processes, and more with a 1-second refresh interval.
- **Log Auditing**: Record and analyze user sessions, process details, and login history for system security.
- **Disk Usage Email Alerts**: Notify administrators when disk usage exceeds 50%, leveraging SMTP protocol.
- **FTP Server Implementation**: Set up a secure FTP server for seamless file transfer and storage.

## Technologies
- **Shell Scripting**: Automates tasks like monitoring, auditing, and email alerts.
- **SMTP Protocol**: Sends email notifications.
- **Linux Tools**: Includes `htop`, `pydf`, and `auditd` for monitoring and auditing.
- **FTP Daemon**: Configured using VSFTPD.

## Limitations
- The solution is tailored for Linux-based systems.
- SMTP configurations require manual setup for email alerts.
- FTP server lacks encryption for sensitive data.

## Future Enhancements
- Add support for monitoring additional metrics like network traffic.
- Integrate secure FTP (SFTP) for sensitive data handling.
- Create a web-based GUI for system monitoring.
