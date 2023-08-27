---
title: 👨🏻‍⚕数字取证大合集
---

# 数字取证

本篇翻译整合数字取证相关资源和工具（偏向于免费、开源软件），感谢原作者们:-)

- [Awesome Forensics](#awesome-forensics)
- [Collections](#collections)
- [Tools](#tools)
  - [Distributions](#distributions)
  - [Frameworks](#frameworks)
  - [Live Forensics](#live-forensics)
  - [IOC Scanner](#ioc-scanner)
  - [Acquisition](#acquisition)
  - [Imageing](#imageing)
  - [Carving](#carving)
  - [Memory Forensics](#memory-forensics)
  - [Network Forensics](#network-forensics)
  - [Windows Artifacts](#windows-artifacts)
    - [NTFS/MFT Processing](#ntfsmft-processing)
  - [OS X Forensics](#os-x-forensics)
  - [Mobile Forensics](#mobile-forensics)
  - [Docker Forensics](#docker-forensics)
  - [Internet Artifacts](#internet-artifacts)
  - [Timeline Analysis](#timeline-analysis)
  - [Disk image handling](#disk-image-handling)
  - [Decryption](#decryption)
  - [Management](#management)
  - [Picture Analysis](#picture-analysis)
- [Learn Forensics](#learn-forensics)
  - [CTFs and Challenges](#ctfs-and-challenges)
- [Resources](#resources)
  - [Books](#books)
  - [File System Corpora](#file-system-corpora)
  - [Twitter](#twitter)
  - [Blogs](#blogs)
  - [Other](#other)
- [Related Awesome Lists](#related-awesome-lists)
- [Contributing](#contributing)

---

## 合集

- [AboutDFIR – The Definitive Compendium Project](https://aboutdfir.com)
    - 用于学习和研究的取证资源集合，提供认证、书籍、博客、挑战等列表
- [DFIR.Training](https://www.dfir.training/)
    - 专注于事件、工具等的取证资源数据库
- :star:[ForensicArtifacts.com Artifact Repository](https://github.com/ForensicArtifacts/artifacts)
    - 机器可读的取证组件知识库

## 工具

- [Forensics tools on Wikipedia](https://en.wikipedia.org/wiki/List_of_digital_forensics_tools)
    - 维基百科上的取证工具整理
- [Eric Zimmerman's Tools](https://ericzimmerman.github.io/#!index.md)
    - EricZimmerman整理的取证工具大全，附带.ps1文件帮助一键安装



### 取证系统发行版

- [bitscout](https://github.com/vitaly-kamluk/bitscout)
    - 用于远程取证和分析的 LiveCD/LiveUSB
- [Remnux](https://remnux.org/)
    - 用于逆向工程和分析恶意软件的Linux发行版
- [SANS Investigative Forensics Toolkit (sift)](https://github.com/teamdfir/sift)
    - 用于取证分析的 Linux 发行版
- [Tsurugi Linux](https://tsurugi-linux.org/)
    - 用于取证分析的 Linux 发行版
- [WinFE](https://www.winfe.net/home)
    - Windows 取证环境

### 取证框架

- :star:[Autopsy](http://www.sleuthkit.org/autopsy/)
    - 图形化的数字取证工具/平台
- [dff](https://github.com/arxsys/dff)
    - 一个开源计算机取证平台，建立在API之上，为简单使用和自动化而设计
- [dexter](https://github.com/coinbase/dexter)
    - Dexter 是一个取证采集框架，旨在实现可扩展性和安全性
- 🌟[IntelMQ](https://github.com/certtools/intelmq)
    - 使用消息队列协议收集和处理安全源的解决方案，可用于：自动事件处理、态势感知、自动通知以及作为其他工具的数据收集等
- [Kuiper](https://github.com/DFIRKuiper/Kuiper)
    - 一个数字调查平台，为调查团队和个人提供解析、搜索、可视化取证的能力
- [Laika BOSS](https://github.com/lmco/laikaboss)
    - 一个对象扫描器和入侵检测系统
    - 🐞注：对象扫描器（object scanner）？
- [PowerForensics](https://github.com/Invoke-IR/PowerForensics)
    - 一个用于实时磁盘取证分析的框架
- :star: [The Sleuth Kit](https://github.com/sleuthkit/sleuthkit)
    - 用于分析 Microsoft 和 UNIX 文件系统和磁盘，能从事件响应期间或实时系统中获取的图像中识别和恢复证据
- [turbinia](https://github.com/google/turbinia)
    - 一个开源框架，用于在云平台上部署、管理和运行取证工作负载
- [IPED - Indexador e Processador de Evidências Digitais](https://github.com/sepinf-inc/IPED)
    - 巴西联邦警察的数字取证调查工具
- [Wombat Forensics](https://github.com/pjrinaldi/wombatforensics)
    - 使用C/C++构建的可视化取证工具

### 实时取证

- [grr](https://github.com/google/grr)
    - 一个Python编写的客户端，用于事件响应时的远程实时取证
- [Linux Expl0rer](https://github.com/intezer/linux-explorer)
    - 一个易于使用的实时取证工具箱，适用于Linux终端节点，使用Python&Flask编写
- [mig](https://github.com/mozilla/mig)
    - 云上的分布式、实时数字取证平台，属于Mozilla维护，现已弃用
- [osquery](https://github.com/osquery/osquery)
    - 一个SQL驱动的操作系统检测、监控和分析框架
- [UAC](https://github.com/tclahr/uac)
    - UAC（类Unix组件收集器）是事件响应的实时响应收集工具，它利用内置工具自动收集类 Unix 系统工件。支持的系统包括：AIX、FreeBSD、Linux、macOS、NetBSD、Netscaler、OpenBSD 和 Solaris

### IOC扫描器

- [Fenrir](https://github.com/Neo23x0/Fenrir)
    - 一个简单的 IOC 扫描器（Bash脚本），支持扫描 Linux/Unix/macOS系统
- [Loki](https://github.com/Neo23x0/Loki)
    - IOC/YARA扫描器，支持四种检测方法：文件名检测、YARA规则检测、哈希值检测、C2反向连接检测
- [Redline](https://www.fireeye.com/services/freeware/redline.html)
    - FireEye提供的免费终端安全工具，通过内存和文件分析以及威胁评估配置文件的开发来查找恶意活动的迹象
- [THOR Lite](https://www.nextron-systems.com/thor-lite/)
    - 免费但不开源的IOC/YARA扫描器，与Loki一家，使用Golang编写，相当于开源Loki的增强版

### 采集器

- [artifactcollector](https://github.com/forensicanalysis/artifactcollector) - A customizable agent to collect forensic artifacts on any Windows, macOS or Linux system
    - 一个可定制的代理，可用于在任何

- [ArtifactExtractor](https://github.com/Silv3rHorn/ArtifactExtractor) - Extract common Windows artifacts from source images and VSCs
- [AVML](https://github.com/microsoft/avml) - A portable volatile memory acquisition tool for Linux
- [Belkasoft RAM Capturer](https://belkasoft.com/ram-capturer) - Volatile Memory Acquisition Tool
- [CrowdResponse](https://www.crowdstrike.com/resources/community-tools/crowdresponse/) - A static host data collection tool by CrowdStrike
- [DFIR ORC](https://dfir-orc.github.io/) - Forensics artefact collection tool for systems running Microsoft Windows
- [FastIR Collector](https://github.com/SekoiaLab/Fastir_Collector) - Collect artifacts on windows
- [FireEye Memoryze](https://www.fireeye.com/services/freeware/memoryze.html) - A free memory forensic software 
- [LiME](https://github.com/504ensicsLabs/LiME) - Loadable Kernel Module (LKM), which allows the acquisition of volatile memory from Linux and Linux-based devices, formerly called DMD
- [Magnet RAM Capture](https://www.magnetforensics.com/resources/magnet-ram-capture/) - A free imaging tool designed to capture the physical memory 
- [Velociraptor](https://github.com/Velocidex/velociraptor) - Velociraptor is a tool for collecting host based state information using Velocidex Query Language (VQL) queries
- [WinTriage](https://www.securizame.com/wintriage-the-triage-tool-for-windows-dfirers/) - Wintriage is a live response tool that extracts Windows artifacts. It must be executed with local or domain administrator privileges and recommended to be done from an external drive.

---

-   [artifactcollector](https://github.com/forensicanalysis/artifactcollector) - 一个可定制的代理，用于在任何 Windows、macOS 或 Linux 系统上收集取证工件
-   [ArtifactExtractor](https://github.com/Silv3rHorn/ArtifactExtractor) - 从源图像和 VSC 中提取常见的 Windows 工件
-   [AVML](https://github.com/microsoft/avml) - 适用于 Linux 的便携式易失性内存获取工具
-   [Belkasoft RAM Capturer](https://belkasoft.com/ram-capturer) - 易失性内存采集工具
-   [CrowdResponse](https://www.crowdstrike.com/resources/community-tools/crowdresponse/) - CrowdStrike 的静态主机数据收集工具
-   [DFIR ORC](https://dfir-orc.github.io/) - 用于运行 Microsoft Windows 的系统的取证人工制品收集工具
-   [FastIR 收集器](https://github.com/SekoiaLab/Fastir_Collector)- 在 Windows 上收集工件
-   [FireEye Memoryze](https://www.fireeye.com/services/freeware/memoryze.html) - 免费的内存取证软件
-   [LiME](https://github.com/504ensicsLabs/LiME) - 可加载内核模块 (LKM)，允许从 Linux 和基于 Linux 的设备（以前称为 DMD）获取易失性内存
-   [Magnet RAM Capture](https://www.magnetforensics.com/resources/magnet-ram-capture/) - 一种免费的映像工具，旨在捕获物理内存
-   [Velociraptor](https://github.com/Velocidex/velociraptor) - Velociraptor 是一种使用 Velocidex 查询语言 (VQL) 查询收集基于主机的状态信息的工具
-   [WinTriage](https://www.securizame.com/wintriage-the-triage-tool-for-windows-dfirers/) - Wintriage 是一种实时响应工具，可提取 Windows 工件。它必须以本地或域管理员权限执行，并建议从外部驱动器执行。

###  

### Imaging

- [dc3dd](https://sourceforge.net/projects/dc3dd/) - Improved version of dd
- [dcfldd](http://dcfldd.sourceforge.net) - Different improved version of dd (this version has some bugs!, another version is on github [adulau/dcfldd](https://github.com/adulau/dcfldd))
- [FTK Imager](https://accessdata.com/product-download/ftk-imager-version-3-4-3) - Free imageing tool for windows
- :star: [Guymager](https://guymager.sourceforge.io/) - Open source version for disk imageing on linux systems

### Carving

- [bstrings](https://github.com/EricZimmerman/bstrings) - Improved strings utility
- [bulk_extractor](https://github.com/simsong/bulk_extractor) - Extracts information such as email addresses, creditcard numbers and histrograms from disk images
- [floss](https://github.com/mandiant/flare-floss) - Static analysis tool to automatically deobfuscate strings from malware binaries
- :star: [photorec](https://www.cgsecurity.org/wiki/PhotoRec) - File carving tool
- [swap_digger](https://github.com/sevagas/swap_digger) - A bash script used to automate Linux swap analysis, automating swap extraction and searches for Linux user credentials, Web form credentials, Web form emails, etc.

### Memory Forensics

- [inVtero.net](https://github.com/ShaneK2/inVtero.net) - High speed memory analysis framework
  developed in .NET supports all Windows x64, includes code integrity and write support
- [KeeFarce](https://github.com/denandz/KeeFarce) - Extract KeePass passwords from memory
- [MemProcFS](https://github.com/ufrisk/MemProcFS) - An easy and convenient way of accessing physical memory as files a virtual file system.
- [Rekall](https://github.com/google/rekall) - Memory Forensic Framework
- [volatility](https://github.com/volatilityfoundation/volatility) - The memory forensic framework
- [VolUtility](https://github.com/kevthehermit/VolUtility) - Web App for Volatility framework

### Network Forensics

- [Kismet](https://github.com/kismetwireless/kismet) - A passive wireless sniffer
- [NetworkMiner](https://www.netresec.com/?page=Networkminer) - Network Forensic Analysis Tool
- :star: [WireShark](https://www.wireshark.org/) - A network protocol analyzer

### Windows Artifacts

- [Beagle](https://github.com/yampelo/beagle) -  Transform data sources and logs into graphs
- [FRED](https://www.pinguin.lu/fred) - Cross-platform microsoft registry hive editor
- [LastActivityView](https://www.nirsoft.net/utils/computer_activity_view.html) - LastActivityView by Nirsoftis a tool for Windows operating system that collects information from various sources on a running system, and displays a log of actions made by the user and events occurred on this computer. 
- [LogonTracer](https://github.com/JPCERTCC/LogonTracer) - Investigate malicious Windows logon by visualizing and analyzing Windows event log
- [python-evt](https://github.com/williballenthin/python-evt) - Pure Python parser for classic Windows Event Log files (.evt)
- [RegRipper3.0](https://github.com/keydet89/RegRipper3.0) - RegRipper is an open source Perl tool for parsing the Registry and presenting it for analysis
- [RegRippy](https://github.com/airbus-cert/regrippy) - A framework for reading and extracting useful forensics data from Windows registry hives


#### NTFS/MFT Processing

- [MFT-Parsers](http://az4n6.blogspot.com/2015/09/whos-your-master-mft-parsers-reviewed.html) - Comparison of MFT-Parsers
- [MFTEcmd](https://binaryforay.blogspot.com/2018/06/introducing-mftecmd.html) - MFT Parser by Eric Zimmerman
- [MFTExtractor](https://github.com/aarsakian/MFTExtractor) - MFT-Parser
- [NTFS journal parser](http://strozfriedberg.github.io/ntfs-linker/)
- [NTFS USN Journal parser](https://github.com/PoorBillionaire/USN-Journal-Parser)
- [RecuperaBit](https://github.com/Lazza/RecuperaBit) - Reconstruct and recover NTFS data
- [python-ntfs](https://github.com/williballenthin/python-ntfs) - NTFS analysis

### OS X Forensics

- [APFS Fuse](https://github.com/sgan81/apfs-fuse) - A read-only FUSE driver for the new Apple File System
- [mac_apt (macOS Artifact Parsing Tool)](https://github.com/ydkhatri/mac_apt) - Extracts forensic artifacts from disk images or live machines
- [MacLocationsScraper](https://github.com/mac4n6/Mac-Locations-Scraper) - Dump the contents of the location database files on iOS and macOS
- [macMRUParser](https://github.com/mac4n6/macMRU-Parser) - Python script to parse the Most Recently Used (MRU) plist files on macOS into a more human friendly format
- [OSXAuditor](https://github.com/jipegit/OSXAuditor)
- [OSX Collect](https://github.com/Yelp/osxcollector)

### Mobile Forensics

- [Andriller](https://github.com/den4uk/andriller) - A software utility with a collection of forensic tools for smartphones
- [ALEAPP](https://github.com/abrignoni/ALEAPP) - An Android Logs Events and Protobuf Parser
- [ArtEx](https://www.doubleblak.com/index.php) - Artifact Examiner for iOS Full File System extractions
- [iLEAPP](https://github.com/abrignoni/iLEAPP) - An iOS Logs, Events, And Plists Parser
- [iOS Frequent Locations Dumper](https://github.com/mac4n6/iOS-Frequent-Locations-Dumper) - Dump the contents of the StateModel#.archive files located in /private/var/mobile/Library/Caches/com.apple.routined/
- [MEAT](https://github.com/jfarley248/MEAT) - Perform different kinds of acquisitions on iOS devices
- [MobSF](https://github.com/MobSF/Mobile-Security-Framework-MobSF) - An automated, all-in-one mobile application (Android/iOS/Windows) pen-testing, malware analysis and security assessment framework capable of performing static and dynamic analysis.
- [OpenBackupExtractor](https://github.com/vgmoose/OpenBackupExtractor) - An app for extracting data from iPhone and iPad backups.


### Docker Forensics

- [dof (Docker Forensics Toolkit)](https://github.com/docker-forensics-toolkit/toolkit) - Extracts and interprets forensic artifacts from disk images of Docker Host systems
- [Docker Explorer](https://github.com/google/docker-explorer) Extracts and interprets forensic artifacts from disk images of Docker Host systems

### Internet Artifacts

- [ChromeCacheView](https://www.nirsoft.net/utils/chrome_cache_view.html) - A small utility that reads the cache folder of Google Chrome Web browser, and displays the list of all files currently stored in the cache
- [chrome-url-dumper](https://github.com/eLoopWoo/chrome-url-dumper) - Dump all local stored infromation collected by Chrome
- [hindsight](https://github.com/obsidianforensics/hindsight) - Internet history forensics for Google Chrome/Chromium
- [unfurl](https://github.com/obsidianforensics/unfurl) - Extract and visualize data from URLs

### Timeline Analysis

- [DFTimewolf](https://github.com/log2timeline/dftimewolf) - Framework for orchestrating forensic collection, processing and data export using GRR and Rekall
- :star: [plaso](https://github.com/log2timeline/plaso) - Extract timestamps from various files and aggregate them
- [Timeline Explorer](https://binaryforay.blogspot.com/2017/04/introducing-timeline-explorer-v0400.html) - Timeline Analysis tool for CSV and Excel files. Built for SANS FOR508 students
- [timeliner](https://github.com/airbus-cert/timeliner) - A rewrite of mactime, a bodyfile reader
- [timesketch](https://github.com/google/timesketch) - Collaborative forensic timeline analysis

### Disk image handling

- [Disk Arbitrator](https://github.com/aburgh/Disk-Arbitrator) - A Mac OS X forensic utility designed to help the user ensure correct forensic procedures are followed during imaging of a disk device
- [imagemounter](https://github.com/ralphje/imagemounter) - Command line utility and Python package to ease the (un)mounting of forensic disk images
- [libewf](https://github.com/libyal/libewf) - Libewf is a library and some tools to access the Expert Witness Compression Format (EWF, E01)
- [PancakeViewer](https://github.com/forensicmatt/PancakeViewer) - Disk image viewer based in dfvfs, similar to the FTK Imager viewer
- [xmount](https://www.pinguin.lu/xmount) - Convert between different disk image formats

### Decryption

- [hashcat](https://hashcat.net/hashcat/) - Fast password cracker with GPU support
- [John the Ripper](https://www.openwall.com/john/) - Password cracker

### Management

- [dfirtrack](https://github.com/dfirtrack/dfirtrack) - Digital Forensics and Incident Response Tracking application, track systems
- [Incidents](https://github.com/veeral-patel/incidents) - Web application for organizing non-trivial security investigations. Built on the idea that incidents are trees of tickets, where some tickets are leads

### Picture Analysis

- [Ghiro](http://www.getghiro.org/) - A fully automated tool designed to run forensics analysis over a massive amount of images
- [sherloq](https://github.com/GuidoBartoli/sherloq) - An open-source digital photographic image forensic toolset

### Metadata Forensics

- [ExifTool](https://exiftool.org/) by Phil Harvey
- [FOCA](https://github.com/ElevenPaths/FOCA) - FOCA is a tool used mainly to find metadata and hidden information in the documents

### Steganography

- [Sonicvisualizer](https://www.sonicvisualiser.org)
- [Steghide](https://github.com/StefanoDeVuono/steghide) - is a steganography program that hides data in various kinds of image and audio files
- [Wavsteg](https://github.com/samolds/wavsteg) - is a steganography program that hides data in various kinds of image and audio files
- [Zsteg](https://github.com/zed-0xff/zsteg) - A steganographic coder for WAV files

## Learn Forensics

- [Forensic challenges](https://www.amanhardikar.com/mindmaps/ForensicChallenges.html) - Mindmap of forensic challenges
- [OpenLearn](https://www.open.edu/openlearn/science-maths-technology/digital-forensics/content-section-0?active-tab=description-tab) - Digital forensic course
- [Training material](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/technical-operational) - Online training material by European Union Agency for Network and Information Security for different topics (e.g. [Digital forensics](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/technical-operational/#digital_forensics), [Network forensics](https://www.enisa.europa.eu/topics/trainings-for-cybersecurity-specialists/online-training-material/technical-operational/#network_forensics))

### CTFs and Challenges

- [Champlain College DFIR CTF](https://champdfa-ccsc-sp20.ctfd.io)
- [CyberDefenders](https://cyberdefenders.org/labs/?type=ctf) 
- [DefCon CTFs](https://archive.ooo) - archive of DEF CON CTF challenges.
- [Forensics CTFs](https://github.com/apsdehal/awesome-ctf/blob/master/README.md#forensics)
- [MagnetForensics CTF Challenge](https://www.magnetforensics.com/blog/magnet-weekly-ctf-challenge/)
- [MalwareTech Challenges](https://www.malwaretech.com/challenges)
- [MalwareTraffic Analysis](https://www.malware-traffic-analysis.net/training-exercises.html)
- [MemLabs](https://github.com/stuxnet999/MemLabs)
- [NW3C Chanllenges](https://nw3.ctfd.io)
- [Precision Widgets of North Dakota Intrusion](https://betweentwodfirns.blogspot.com/2017/11/dfir-ctf-precision-widgets-of-north.html)
- [ReverseEngineering Challenges](https://challenges.re)

## Resources

### Web

- [ForensicsFocus](https://www.forensicfocus.com/)
- [Insecstitute Resources](https://resources.infosecinstitute.com/)
- [SANS Digital Forensics](https://www.sans.org/digital-forensics-incident-response/)


### Blogs

- [FlashbackData](https://www.flashbackdata.com/blog/)
- [Netresec](https://www.netresec.com/index.ashx?page=Blog)
- [roDigitalForensics](https://prodigital4n6.com/blog/)
- [SANS Forensics Blog](https://www.sans.org/blog/?focus-area=digital-forensics)
- [SecurityAffairs](https://securityaffairs.co/wordpress/) - blog by Pierluigi Paganini
- [thisweekin4n6.wordpress.com](thisweekin4n6.wordpress.com) - Weekly updates for forensics
- [Zena Forensics](https://blog.digital-forensics.it/)


### Books

*more at [Recommended Readings](http://dfir.org/?q=node/8) by Andrew Case*

- [Network Forensics: Tracking Hackers through Cyberspace](https://www.pearson.com/us/higher-education/program/Davidoff-Network-Forensics-Tracking-Hackers-through-Cyberspace/PGM322390.html) - Learn to recognize hackers’ tracks and uncover network-based evidence
- [The Art of Memory Forensics](https://www.memoryanalysis.net/amf) - Detecting Malware and Threats in Windows, Linux, and Mac Memory
- [The Practice of Network Security Monitoring](https://nostarch.com/nsm) - Understanding Incident Detection and Response

### File System Corpora

- [Digital Forensic Challenge Images](https://www.ashemery.com/dfir.html) - Two DFIR challenges with images
- [Digital Forensics Tool Testing Images](https://sourceforge.net/projects/dftt/)
- [The CFReDS Project](https://cfreds.nist.gov)
  - [Hacking Case (4.5 GB NTFS Image)](https://cfreds.nist.gov/Hacking_Case.html)

### Twitter

- [@4n6ist](https://twitter.com/4n6ist)
- [@aheadless](https://twitter.com/aheadless)
- [@AppleExaminer](https://twitter.com/AppleExaminer) - Apple OS X & iOS Digital Forensics
- [@carrier4n6](https://twitter.com/carrier4n6) - Brian Carrier, author of Autopsy and the Sleuth Kit
- [@CindyMurph](https://twitter.com/CindyMurph) - Detective & Digital Forensic Examiner
- [@forensikblog](https://twitter.com/forensikblog) - Computer forensic geek
- [@HECFBlog](https://twitter.com/HECFBlog) - SANS Certified Instructor
- [@Hexacorn](https://twitter.com/Hexacorn) - DFIR+Malware
- [@hiddenillusion](https://twitter.com/hiddenillusion)
- [@iamevltwin](https://twitter.com/iamevltwin) - Mac Nerd, Forensic Analyst, Author & Instructor of SANS FOR518
- [@jaredcatkinson](https://twitter.com/jaredcatkinson) - PowerShell Forensics
- [@maridegrazia](https://twitter.com/maridegrazia) - Computer Forensics Examiner
- [@sleuthkit](https://twitter.com/sleuthkit)
- [@williballenthin](https://twitter.com/williballenthin)
- [@XWaysGuide](https://twitter.com/XWaysGuide)
- [@inginformatico](https://twitter.com/inginformatico) - DFIR analyst and enthusiast

Vendors:

- [@Belkasoft](https://twitter.com/Belkasoft)
- [@blackbagtech](https://twitter.com/blackbagtech)

### Other

- [/r/computerforensics/](https://www.reddit.com/r/computerforensics/) - Subreddit for computer forensics
- [/r/LearnDigitalForensics](https://www.reddit.com/r/LearnDigitalForensics/) - Subreddit for learning Digital Forensics
- [ForensicPosters](https://github.com/Invoke-IR/ForensicPosters) - Posters of file system structures
- [SANS Posters](https://www.sans.org/posters/) - Free posters provided by SANS

## Related Awesome Lists

- [Android Security](https://github.com/ashishb/android-security-awesome)
- [AppSec](https://github.com/paragonie/awesome-appsec)
- [CTFs](https://github.com/apsdehal/awesome-ctf)
- [Hacking](https://github.com/carpedm20/awesome-hacking)
- [Honeypots](https://github.com/paralax/awesome-honeypots)
- [Incident-Response](https://github.com/meirwah/awesome-incident-response)
- [Infosec](https://github.com/onlurking/awesome-infosec)
- [Malware Analysis](https://github.com/rshipp/awesome-malware-analysis)
- [Pentesting](https://github.com/enaqx/awesome-pentest)
- [Security](https://github.com/sbilly/awesome-security)
- [Social Engineering](https://github.com/v2-dev/awesome-social-engineering)
- [YARA](https://github.com/InQuest/awesome-yara)
