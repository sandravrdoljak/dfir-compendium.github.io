---
title: macOS Tools
type: docs
prev: tools/linux_tools
next: tools/windows_tools
toc: false
---

When analyzing macOS desktop systems, the right tools can greatly simplify the digital forensic analysis process. From initial data collection to investigation and final analysis, each step is important to uncover valuable insights. This guide provides a list of some important forensic analysis tools, organized by their application in the forensic process, with a brief description and additional links to further how-to guides.

{{% details title="1 Collection" closed="true" %}}
{{% steps %}}

### Computer Aided INvestigative Environment (CAINE)

CAINE is a GNU/Linux based distribution used for forensic analysis. The distribution has a user-friendly graphical interface and aims at providing easy access to user-friendly tools needed in order to perform digital forensic analysis. The distribution is popular, as it can be easily used during all four stages of the digital forensic analysis process. CAINE is open-source and possess a software write blocker, which is helpful when trying to preserve the integrity of the forensic artefacts and the underlying system. CAINE features various tools inside the distribution such as: 
* Arsenal Image Mounter,
* Guymager,
* Photorec
* and many more...

For more information on how to use and setup CAINE please [visit the official site!](https://www.caine-live.net/index.html)

### Guymager

Guymager is an open-source forensic imager. It provides a simple interface for creating forensic disk images or cloning disks with support for multiple file formats and is known for its reliability. Guymager works for Windows, macOS and Linux systems. Disk images created are either flat (dd), EWF (E01) and AFF images. The main advantage of Guymager is its speed, which is achieved by a multi-threaded and pipelined design and multi-threaded data compression. 

For more information on how to use Guymager, please [visit the official site!](https://guymager.sourceforge.io)

{{% /steps %}}
{{% /details %}}


{{% details title="2 Examinaton" closed="true" %}}
{{% steps %}}
### Autopsy 

Autopsy is a digital forensics platform and graphical interface to "The Sleuth Kit" and other digital forensic tools. It is open-source and capable of analysing hard drives, smartphones, and media cards. Autopsy offers a user-friendly interface to perform efficient and comprehensive forensic investigations, with features such as timeline analysis, keyword searching, and web artefact analysis.

For more information on how to use Autopsy, please [visit the official site!](https://www.autopsy.com)

### Arsenal Image Mounter 

Arsenal Image Mounter offers a unique capability within the forensic toolkit by allowing disk images to be mounted as complete disks in Windows, making them appear as physical drives. This feature is invaluable for forensic investigations as it enables the examination of disk images in their native environment, including the execution of applications and analysis of.

For more information on how to use Arsenal Image Mounter, please [visit the official site!](https://arsenalrecon.com)

### ewfmount 

ewfmount is a command-line tool designed specifically for mounting EWF (Expert Witness Format) image files. This tool is crucial for forensic analysts who work with disk images in the EWF format, as it allows them to mount these images as if they were physical disks. This capability is particularly useful for accessing the contents of the images for analysis or extraction without the need for conversion to other disk image formats.

For more information on how to use ewfmount, please [visit the official site!](https://manpages.debian.org/unstable/ewf-tools/ewfmount.1.en.html)

### AutoMacTC (Automated Mac Forensic Triage Collector)

AutoMacTC is a specialised tool for automating the collection of forensic artefacts from macOS systems. It is designed to quickly triage Mac endpoints, collecting valuable data including user account details, network connections, and application information, which is important for effective forensic analysis.

For more information on how to use AutoMacTC, please [visit the official site!](https://www.crowdstrike.com/blog/automating-mac-forensic-triage/)

{{% /steps %}}
{{% /details %}}


{{% details title="3 Analysis" closed="true" %}}
{{% steps %}}
### ArtifactCollector

ArtifactCollector is a tool that is designed to collect system and application artefacts from computers and mobile devices for forensic analysis. It can acquire various artefacts from Windows, macOS and Linux systems. It can collect either low-level (like \$MFT) and high-level file artefacts (like registry keys) It streamlines the collection of critical data such as browser history, email, chat logs, and system information, facilitating a quicker understanding of user actions and system events. 

For more information on how to use ArtifactCollector, please [visit the official site!](https://github.com/forensicanalysis/artifactcollector)

### CyLR

CyLR is a Live Response Collection Tool designed to simplify and expedite the process of data gathering during digital forensic investigations. It focuses on efficiently collecting critical artifacts from operating systems without the need for pre-installed agents. CyLR's capability to quickly gather essential forensic data makes it a valuable asset for forensic analysts and incident response teams, aiding in rapid response and analysis during security incidents.

For more information on how to use CyLR, please [visit the official site!](https://github.com/orlikoski/CyLR)

### FastIR

FastIR is a live forensic artifacts collector capable of operating across multiple platforms including GNU/Linux, Windows, and Mac OS X. This tool is designed to collect various artifacts rapidly and efficiently, making it an essential utility for live forensic investigations. By collecting data in real time, Fastir provides immediate insights into system activities, helping forensic analysts and incident response teams to quickly assess and respond to potential security incidents.

For more information on how to use FastIR, please [visit the official site!](https://github.com/OWNsecurity/fastir_artifacts)

### mac_apt

mac_apt is a macOS Artefact Parsing Tool that helps in the forensic analysis of macOS devices. It can extract and parse numerous artefacts from macOS systems, providing insights into user activities, system configuration, and application behaviour.

For more information on how to use mac_apt, please [visit the official site!](https://github.com/ydkhatri/mac_apt)

### Unix-like Artifacts Collector (UAC) 

Unix-like Artifacts Collector (UAC) is an open-source live analysis artefact collection tool. This tool can be used to collect artefacts from AIX, Android, ESXi, FreeBSD, Linux, macOS, NetBSD, NetScaler, OpenBSD and Solaris systems.

For more information on how to use UAC, please [visit the official site!](https://github.com/tclahr/uac)

{{% /steps %}}
{{% /details %}}

