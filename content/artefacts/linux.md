---
title: Linux Artefacts
type: docs
prev: artefacts/_index
next: artefacts/macos
toc: true
---

When analyzing Linux desktop systems, the deciding on which artefacts to look at first, can be a hard task. From "Account Usage" to "File and Folder Opening/Sharing" artefacts, choosing the right ones, that give the best insight is not always easy. This guide provides a list of 10 artefacts best suited for the getting a good initial overview of a security incident. The second subset of 10 artefacts, are the additional artefacts, which are "optional", aim to provide more in-depth insights.

{{% details title="Initial Analysis" closed="true" %}}
{{% steps %}}

### Authentication logs

Vital for identifying authentication attempts and security breaches. Can be found in "var/log/auth.log".

### Bash History

Offers insights into command line operations, crucial for understanding user or administrative actions.

### System Logs

Central repository for system activities, indispensable for a broad overview of system operations. Can be found in "/var/log/syslog". 

### Scheduled Tasks 

Scheduling mechanisms, key for identifying automated tasks and potential malicious activities.

### Network Configuration Files

Critical for understanding network setups and potential misconfigurations.

### Browser Downloads & History

Provides a comprehensive view of the user's online activities and interests.

### User Account Information and Passwords

Fundamental for assessing system access controls and user privileges. Can be found in  "/etc/passwd" and "/etc/shadow". 

### Audit Logs

Detailed record of system events, essential for security auditing and incident response. Can be found in "/var/log/audit/audit.log".

### Installed Programs 

Logs software installations and removals, aiding in understanding system changes and potential unauthorised software. Can be found in "/var/log/dpkg.log".

### Systemd Journal

A modern and comprehensive logging system that captures detailed system, application, and user events.

{{% /steps %}}
{{% /details %}}


{{% details title="In-Depth Analysis" closed="true" %}}
{{% steps %}}

### Package Manager Logs

Tracks package management activities, useful for identifying system updates and installations.

### Failed Login Attempts

Reveals failed login information.

### Recycle Bin

Contains deleted files, providing clues about user actions and attempts to conceal activities.

### Preloads Libraries

Can indicate alterations to standard binary executions, relevant for investigating unauthorized modifications. Can be found in "/etc/ld.so.preload" and "LD_PRELOAD".

### Kernel Logs 

Dedicated to kernel messages, important for diagnosing hardware and driver issues. Can be found in "/var/log/kern.log". 

### Startup Scripts

"Startup Scripts" are scripts that automatically start upon login. Can be found in "/etc/init.d".

### Startup Messages

Logs startup messages, useful for identifying issues during system boot. Can be found in "/var/log/boot.log" and since the Ubuntu version 16.04 "journald" is used for the logging.

### Network Connection Logs

Essential for examining incoming and outgoing connections, aiding in network traffic analysis.

### Desktop & Downloads Directories

Provides a glimpse into user saved files and download activities.

{{% /steps %}}
{{% /details %}}
