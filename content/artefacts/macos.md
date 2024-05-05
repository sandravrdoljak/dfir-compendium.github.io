---
title: macOS Artefacts
type: docs
prev: artefacts/linux
next: artefacts/windows
toc: false
---

When analyzing macOS desktop systems, the deciding on which artefacts to look at first, can be a hard task. From "Account Usage" to "File and Folder Opening/Sharing" artefacts, choosing the right ones, that give the best insight is not always easy. This guide provides a list of 10 artefacts best suited for the getting a good initial overview of a security incident. The second subset of 10 artefacts, are the additional artefacts, which are "optional", aim to provide more in-depth insights.

{{% details title="Initial Analysis" closed="true" %}}
{{% steps %}}

### Application Directory

Offer comprehensive insights into the applications installed on the system.

### Launch Agents and Daemons

Identifies agents and daemons that runs automatically, crucial for uncovering persistence mechanisms.

### Users & Accounts

Lists all users and accounts configured on this system, revealing possible new user accounts being created.

### Browser Downloads and History

Offers insights into user online behaviour, crucial for investigations involving internet usage.

### Quarantine Event Database

Provides details on potentially malicious files, essential for initial threat assessment.

### Application Permissions – TCC

Critical for understanding application access to system resources and user data.

### Installation Log

Records of system and software installations, useful for tracking system changes over time.

### Terminal History – Executed Commands

Reveals commands entered, crucial for understanding administrative tasks or malicious activities.

### Recent Items

Provides insight into the most recently accessed applications and files, helpful for understanding recent user activities.

### UTMPX

Records active logins and logouts, providing a history of system access.

{{% /steps %}}
{{% /details %}}


{{% details title="## In-Depth Analysis" closed="true" %}}
{{% steps %}}

### Hidden Directories and Files

Reveals directories and files that are hidden from the users.

### Quick Look

Provides information about thumbnails which have been created for applications/files on the system.

### Autoruns

Shows which programs and software runs automatically upon user login.

### File System Events Store Database

Logs file system changes, key for tracking file creation, modification, and deletion.

### Search: Spotlight

Spotlight's indexing and search functionality used to understand user search habits and behaviour.

### Apple System Log (ASL)

Provides all system log messages and errors.

### Audit Logs

Security-related log that tracks detailed records of system events.

### Unified Logs

Lists detailed system, application, and user-related event log messages.

### Recycle Bin

Provides information on deleted files or files marked for deletion.

### Pslist

List of current processes running on the system.

{{% /steps %}}
{{% /details %}}