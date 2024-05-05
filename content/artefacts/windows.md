---
title: Windows Artefacts
type: docs
prev: artefacts/macos
next: artefacts/_index
toc: false
---

When analyzing Windows desktop systems, the deciding on which artefacts to look at first, can be a hard task. From "Account Usage" to "File and Folder Opening/Sharing" artefacts, choosing the right ones, that give the best insight is not always easy. This guide provides a list of 10 artefacts best suited for the getting a good initial overview of a security incident. The second subset of 10 artefacts, are the additional artefacts, which are "optional", aim to provide more in-depth insights.

## Initial Analysis

{{% steps %}}

### Windows Security Event Logs - ID 4624, ID 4625, ID 4648, ID 4720 and ID 4778

Frequent and rich in information, providing clear insights.

### Registry Hive Files

Components of the "Windows Registry" that store configuration information for the system and for applications installed on the system.

### Amcache.hve

Offers details about installed applications and executed programs, relevant for tracking unauthorized or malicious software execution.

### Prefetch Files

Frequent and informative, indicating applications that were executed, aiding in understanding user or system actions before an incident.

### Browser, Cache, Cookies, Downloads and History

Provides a comprehensive view of a user's online behaviour, relevant to a wide range of incident types.

### Antivirus Logs

Essential for investigating external device usage and potential data exfiltration or malware introduction incidents.

### System Resource Usage Monitor (SRUM)

Rich in information regarding system performance and application usage over time, aiding in anomaly detection.

### Jumplists

Crucial for analysing data flow, protocol usage, and identifying potential security threats.

### Recycle Bin \$I/\$R Files

Offers insights into deleted data, providing evidence of potential attempts to conceal actions.

### Scheduled Tasks

Reveals insights into planned activities and malware persistence mechanisms, relevant for identifying unauthorized or malicious configurations.

{{% /steps %}}



## In-Depth Analysis

{{% steps %}}

### Thumbcache

Critical for reconstructing a user's activity timeline and identifying content that may have been viewed but not modified or saved.

### ShellBags

Evidence of accessed folders, even if they have been deleted, crucial for understanding user navigation behaviour.

### Shortcut (LNK) Files

Important in understanding what applications or files were frequently used and can also indicate the presence of files that have been moved or deleted.

### Last Visited MRU (Most Recently Used)

Crucial for identifying files and commands that have been recently accessed or executed on the system. This helps in understanding the most recent user activities and pinpointing actions taken close to the time of an incident.

### Windows Security Event Logs - ID 4688, ID 7045

They can reveal unauthorised executions and modifications to system services, which are often indicators of system compromises or administrative changes.

### Run/RunOnce Keys

Analysing these keys helps identify unauthorised programs that might have been configured to launch on system start, thus providing insights into potential persistence mechanisms used in malware attacks.

### Windows Operational Event Logs - ID 4104, ID 9707

Important for tracking administrative operations and potential script-based malware execution within the system.

### Windows Timeline

Provides a comprehensive view of user activities including documents opened, applications used, and websites visited, arranged in a chronological timeline.

### System Boot & Autostart Programs

Crucial for understanding both system performance and potential security threats that leverage "Autostart" to maintain persistence.

### Windows Search Database & History

Valuable source for understanding user intent and locating artefacts that might not be directly visible in the file system, thus providing a deeper insight into user activity and interests.

{{% /steps %}}
