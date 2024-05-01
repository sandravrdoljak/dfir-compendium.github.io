---
title: Windows Tools
type: docs
prev: _index
next: macos_tools
toc: true
---

When analyzing Windows desktop systems, the right tools can greatly simplify the digital forensic analysis process. From initial data collection to investigation and final analysis, each step is important to uncover valuable insights. This guide provides a list of some important forensic analysis tools, organized by their application in the forensic process, with a brief description and additional links to further how-to guides.

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

For more information on how to use and create disk images or clone a disk please [visit the official site!](https://guymager.sourceforge.io)

### FTK Imager 

FTK Imager is a popular tool in digital forensics for acquiring and analysing disk images. It supports a variety of image formats and is capable of creating forensic images of local drives, external storage media and memory. FTK Imager's robust features include the ability to preview files and folders within disk images, facilitating a quick assessment of their relevance to the investigation.

For more information on how to use FTK Imager please [visit the official site!](https://www.exterro.com/digital-forensics-software/ftk-imager)

{{% /steps %}}
{{% /details %}}


{{% details title="2 Examinaton" closed="true" %}}
{{% steps %}}
### Autopsy 

Autopsy is a digital forensics platform and graphical interface to "The Sleuth Kit" and other digital forensic tools. It is open-source and capable of analysing hard drives, smartphones, and media cards. Autopsy offers a user-friendly interface to perform efficient and comprehensive forensic investigations, with features such as timeline analysis, keyword searching, and web artefact analysis.

For more information on how to use Autopsy please [visit the official site!](https://www.autopsy.com)

### Arsenal Image Mounter 

Arsenal Image Mounter offers a unique capability within the forensic toolkit by allowing disk images to be mounted as complete disks in Windows, making them appear as physical drives. This feature is invaluable for forensic investigations as it enables the examination of disk images in their native environment, including the execution of applications and analysis of.

For more information on how to use Arsenal Image Mounter please [visit the official site!](https://arsenalrecon.com)

### FTK Imager

FTK Imager is a popular tool in digital forensics for acquiring and analysing disk images. It supports a variety of image formats and is capable of creating forensic images of local drives, external storage media and memory. FTK Imager's robust features include the ability to preview files and folders within disk images, facilitating a quick assessment of their relevance to the investigation.

For more information on how to use FTK Imager please [visit the official site!](https://www.exterro.com/digital-forensics-software/ftk-imager)

### Kroll Artifact Parser and Extractor (KAPE)

Kroll Artifact Parser and Extractor (KAPE) is an efficient and highly versatile command-line utility that targets the collection of forensic artifacts and files from Windows systems for analysis. KAPE allows forensic analysts to rapidly collect and process evidence by utilising predefined target and module configurations, streamlining the evidence acquisition and preliminary analysis phases of forensic investigations.

For more information on how to use KAPE please [visit the official site!](https://www.kroll.com/en/services/cyber-risk/incident-response-litigation-support/kroll-artifact-parser-extractor-kape)

{{% /steps %}}
{{% /details %}}


{{% details title="3 Analysis" closed="true" %}}
{{% steps %}}
### ArtifactCollector



### Cyber Triage



### AmcacheParser



### AppCompatCacheParser



### EvtxECmd



### JLECmd



### JumpList Explorer	



### LECmd



### PECmd



### RBCmd



### RecentFileCacheParser



### RECmd



### Registry Explorer



### SDB Explorer



### SBECmd



### ShellBags Explorer



### SrumECmd



### SumECmd



### Timeline Explorer



### WxTCmd	




{{% /steps %}}
{{% /details %}}

