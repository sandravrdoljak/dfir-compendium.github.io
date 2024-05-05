---
title: Linux Artefacts
type: docs
prev: artefacts/_index
next: artefacts/macos
toc: false
---

When analyzing Linux desktop systems, the deciding on which artefacts to look at first, can be a hard task. From "Account Usage" to "File and Folder Opening/Sharing" artefacts, choosing the right ones, that give the best insight is not always easy. This guide provides a list of 10 artefacts best suited for the getting a good initial overview of a security incident. The second subset of 10 artefacts, are the additional artefacts, which are "optional", aim to provide more in-depth insights.

{{% details title="Initial Analysis" closed="true" %}}
{{% steps %}}

### Authentication logs (/var/log/auth.log)

Vital for identifying authentication attempts and security breaches.

### Bash History

Offers insights into command line operations, crucial for understanding user or administrative actions.

### System logs (/var/log/syslog)

Central repository for system activities, indispensable for a broad overview of system operations.

### Cron jobs and systemd timers

Scheduling mechanisms, key for identifying automated tasks and potential malicious activities.

### Network Configuration Files

Critical for understanding network setups and potential misconfigurations.

### Browser, Cache, Cookies, Downloads and History

Provides a comprehensive view of the user's online activities and interests.

### User Account Information and Passwords (/etc/passwd and /etc/shadow)

Fundamental for assessing system access controls and user privileges.

### Audit logs (/var/log/audit/audit.log)

Detailed record of system events, essential for security auditing and incident response.

### Installed Programs (/var/log/dpkg.log)

Logs software installations and removals, aiding in understanding system changes and potential unauthorised software.

### Systemd journal

A modern and comprehensive logging system that captures detailed system, application, and user events.

{{% /steps %}}
{{% /details %}}


{{% details title="In-Depth Analysis" closed="true" %}}
{{% steps %}}

### Package Manager Logs

Tracks package management activities, useful for identifying system updates and installations.

### Scheduled Tasks (/etc/cron.d/)

Details periodic tasks, revealing insights into system maintenance routines or malware persistence.

### PAM Configuration (/etc/pam.d/)

Key for understanding authentication mechanisms and security policies.

### Stored Credentials

Reveals saved login information, indicating user accounts and services utilized.

### Recycle Bin

Contains deleted files, providing clues about user actions and attempts to conceal activities.

### Preloads Libraries (/etc/ld.so.preload and LD_PRELOAD)

Can indicate alterations to standard binary executions, relevant for investigating unauthorized modifications.

### .Xauthority files

Pertinent for session authentication, especially in graphical user environments.

### /var/log/boot.log

Logs startup messages, useful for identifying issues during system boot.

### Network Connection Logs

Essential for examining incoming and outgoing connections, aiding in network traffic analysis.

### Desktop and Downloads Directories

Provides a glimpse into user saved files and download activities.

{{% /steps %}}
{{% /details %}}