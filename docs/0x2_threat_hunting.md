---
title: 🏹️ 威胁狩猎大合集
---

# Awesome Threat Detection and Hunting

威胁检测及威胁狩猎的工具、资源大合集，翻译和修改自[awesome-threat-detection](https://github.com/0x4D31/awesome-threat-detection)项目，感谢原作者的整理 :-)

## 目录


[TOC]


## 工具

- [MITRE ATT&CK Navigator](https://mitre.github.io/attack-navigator/enterprise/)([source code](https://github.com/mitre/attack-navigator)) 
    - ATT&CK Navigator是旨在提供ATT＆CK矩阵的基本导航和注释，有点类似于Excel表格的形式
- [HELK](https://github.com/Cyb3rWard0g/HELK)
    - 一个用于威胁狩猎的ELK (Elasticsearch, Logstash, Kibana)框架，集成了高级分析功能
- [osquery-configuration](https://github.com/palantir/osquery-configuration)
    - 一个使用osquery进行事件检测和响应的存储库，是[osquery Across Enterprise](https://medium.com/@palantir/osquery-across-the-enterprise-3c3c9d13ec55)一文的配套内容
    - 注：osquery是一个由FaceBook开源用于对系统进行查询、监控以及分析的一款软件。
        支持`MacOS`、`CentOS`、`Ubuntu`、`Windows`等操作系统[1]
- [DetectionLab](https://github.com/clong/DetectionLab/)
    - 使用Vagrant＆Packer脚本，来构建包含安全工具和日志记录的实验环境，主要从防御者的角度进行设计，帮助快速构建一个具有安全工具的域环境
    - 注：Vagrant＆Packer脚本，可以用于自动化虚拟机的安装和配置流程，用来管理虚拟机
- [Sysmon-DFIR](https://github.com/MHaggis/sysmon-dfir)
    -   一个用于学习Microsoft Sysmon来进行威胁检测的资源清单
    -   补：Microsoft Sysmon，是一个轻量级的系统监控工具，通过系统服务和驱动程序实现记录进程创建、文件访问以及网络信息的记录，并把相关的信息写入并展示在windows的日志事件里[2]
- [sysmon-config](https://github.com/SwiftOnSecurity/sysmon-config)
    - 一个Microsoft Sysmon配置文件模板，带有默认的高质量事件追踪
- [sysmon-modular](https://github.com/olafhartong/sysmon-modular)
    - 一个Microsoft Sysmon配置模块的存储库，包括从Sysmon配置到MITER ATT&CK技术框架的[映射](https://github.com/olafhartong/sysmon-modular/blob/master/attack_matrix/README.md)
- [Revoke-Obfuscation](https://github.com/danielbohannon/Revoke-Obfuscation)
    - 一个Powershell的混淆检测框架
- [Invoke-ATTACKAPI](https://github.com/Cyb3rWard0g/Invoke-ATTACKAPI)
    - 一个PowerShell脚本，可通过其自己的API和MITER ATT&CK框架进行交互
- [Unfetter](https://github.com/unfetter-analytic/unfetter)
    - 提供了一个框架，用于从客户端计算机（Windows 7）收集事件（进程创建，网络连接，窗口事件日志等），并执行[CAR](https://car.mitre.org/)分析来检测潜在的攻击者活动
    - 补：[CAR](https://github.com/mitre-attack/car)，Cyber Analytics Repository，网络行为分析库，"是MITER基于MITER ATT＆CK对手模型开发的分析知识库，可以作为组织作为ATTCK进行行为检测分析的起点"[2]。
- [Flare](https://github.com/austin-taylor/flare)
    - 一个网络流量和行为的分析框架
- [RedHunt-OS](https://github.com/redhuntlabs/RedHunt-OS)
    - 专门用于攻防对抗仿真（Adversary Emulation）和威胁狩猎的虚拟机。RedHunt的目标是通过整合攻击者的武库和防御者的工具包来主动识别环境中的威胁，来提供威胁仿真（Threat Emulation）和威胁狩猎所有需求的一站式服务
- [Oriana](https://github.com/mvelazc0/Oriana)
    - 基于Django构建的Windows环境下横向移动及威胁狩猎工具，提供Docker镜像。
- ~~[Bro-Osquery](https://github.com/bro/bro-osquery)~~
    - 将Osquery的集成于Bro
    - 该项目现已被[Zeek Agent](https://github.com/zeek/zeek-agent)取代，包含前者的功能
- [Brosquery](https://github.com/jandre/brosquery)
    - 一个帮助osquery加载Bro日志到osquery表中的模块
- [DeepBlueCLI](https://github.com/sans-blue-team/DeepBlueCLI)
    - 一个PowerShell模块，用于从Windows事件日志中进行威胁狩猎
- [Uncoder](https://uncoder.io)
    - 一个在线的搜索/查询转换器，帮助SIEM转换和保存搜索、过滤器、查询语句、API请求、关联和Sigma规则
- 🌟[Sigma](https://github.com/Neo23x0/sigma)
    - 一个对SIEM系统的通用签名格式，帮助基于SIEM的威胁检测规则转换
- [CimSweep](https://github.com/PowerShellMafia/CimSweep)
    - 一套基于CIM / WMI的工具集，用于跨Windows系统版本来远程执行事件响应和威胁狩猎操作
- [Dispatch](https://github.com/Netflix/dispatch)
    - 一个开源的安全威胁事件管理框架，由Netflix开源
- [EQL](https://github.com/endgameinc/eql)(Event Query Language)
    - 事件查询语句
    - [EQLLib](https://github.com/endgameinc/eqllib)(The Event Query Language Analytics Library)
        - 事件查询语言分析库（EQLLib）是基于事件的分析库，使用EQL编写，可以检测基于MITER ATT＆CK™框架来识别攻击者行为。
- [BZAR](https://github.com/mitre-attack/bzar) (Bro/Zeek ATT&CK-based Analytics and Reporting) 
    - 一个用于检测ATT&CK技术的Zeek脚本集合
    - 补：Zeek是一个网络安全监控工具，类似于Bro
- [Security Onion](https://github.com/Security-Onion-Solutions/security-onion)
    - 一个开源的Linux发行版，用于威胁狩猎，安全监视和日志管理。该发行版集成了ELK，Snort，Suricata，Zeek，Wazuh，Sguil和许多其他安全工具
- [Varna](https://github.com/endgameinc/varna)
    - 一个快速、便宜的AWS无服务（注：Serverless）云安全工具，使用事件查询语言（EQL）对CloudTrail日志进行解析和告警
- [BinaryAlert](https://github.com/airbnb/binaryalert)
    - 一个服务器的开源AWS pipeline，用于实施的恶意软件检测溯源和告警
- [hollows_hunter](https://github.com/hasherezade/hollows_hunter)
    - 可用于扫描运行的全部进程，识别并转储其中各种潜在的恶意植入物，例如：已被替换/植入的PE、shellcode、hooks及内存布丁
- [ThreatHunting](https://github.com/olafhartong/ThreatHunting)
    - 一个可以映射MITRE ATT&CK框架的Splunk APP，可以用于指导威胁狩猎
- [Sentinel Attack](https://github.com/BlueTeamLabs/sentinel-attack)
    - 用于简化Sysmon和ATT&CK框架在Azure Sentinel上进行威胁狩猎的快速部署
- [Brim](https://github.com/brimsec/brim) - A desktop application to efficiently search large packet captures and Zeek logs
    - 一个桌面应用程序，可以高效地搜索、查询大型网络数据包和Zeek日志信息
- [YARA](https://github.com/virustotal/yara)
    - 用于规则匹配的瑞士军刀
- [Intel Owl](https://github.com/intelowlproject/IntelOwl)
    - 一种开源情报解决方案，可从单个API大规模获取特定文件，IP或域名的相关威胁情报数据
- [Capa](https://github.com/fireeye/capa)
    - 一个用于识别可执行文件功能的开源工具

### 告警引擎

- [ElastAlert](https://github.com/Yelp/elastalert)
    - 基于ELK的框架，用于从Elasticsearch中的数据中发出异常、峰值或其他设定规则的警报
- [StreamAlert](https://github.com/airbnb/streamalert)
    - 一个无服务器的实时数据分析框架，帮助使用自定的数据源和逻辑从任何环境中提取，分析和告警数据

### 端点监控

- [osquery](https://osquery.io) ([github](https://github.com/osquery/osquery)) 
    -   SQL语句驱动的操作系统编排、监控和分析工具
- [Kolide Fleet](https://github.com/kolide/fleet)
    - 一个弹性的、用于osquery队列的控制服务器
- [Zeek Agent](https://github.com/zeek/zeek-agent)
    - 用于对Zeek提供主机活动信息的端点监控agent
- [Velociraptor](https://github.com/Velocidex/velociraptor)
    - 用于端点可视化和收集的工具
- [Sysdig](https://github.com/draios/sysdig)
    - 一个用于深度挖掘Linux系统可见性的工具，支持容齐的原生支持。可以将其认为是strace + tcpdump + htop + iftop + lsof +...的整合
- [go-audit](https://github.com/slackhq/go-audit)
    -   一个Linux auditd守护进程的替代方法
- [Sysmon](https://docs.microsoft.com/en-us/sysinternals/downloads/sysmon) 
    - 一个Windows系统服务（设备驱动程序），用于监视系统活动并将其日志到Windows的事件日志中
- [OSSEC](github.com/ossec/ossec-hids)
    - 一个开源的、基于主机的入侵检测系统（HIDS）
- 🌟[WAZUH](https://github.com/wazuh/wazuh)
    - 一个开源的综合安全平台，用于威胁预防、检测和响应。可以用于保护本地、虚拟机、容器及云端环境的工作负载
    - 支持的功能：入侵检测、日志数据分析、文件完整性监控、漏洞检测、配置评估、事件响应、合规性、云安全、Docker安全

### 网络监控

- [Zeek](https://github.com/zeek/zeek)
    - 一个网络安全监控工具，前身为Bro
- [ntopng](https://github.com/ntop/ntopng)
    - 一个基于Web的网络流量监控工具
- [Suricata](https://suricata-ids.org)
    - 一个网络威胁监测引擎
- [Snort](https://snort.org) ([github](https://github.com/snort3/snort3))
    - 一个网络入侵检测工具 
- [Joy](https://github.com/cisco/joy)
    - 可用于网络流量抓取、分析的整合包，可用于网络调查、取证和安全监控
- [Netcap](https://github.com/dreadl0ck/netcap)
    - 可用于安全和可扩展性的网络流量数据分析工具
- [🌿Arkime](https://github.com/aol/moloch)
    -   一个开源的、大型全流量数据包捕获、搜索工具，前身为Moloch
- [Stenographer](https://github.com/google/stenographer)
    - 一个全流量网络数据包捕获工具

#### 指纹工具

- [JA3](https://github.com/salesforce/ja3)
    - 一种分析 SSL/TLS 客户端和服务器的方法
- [HASSH](https://github.com/salesforce/hassh)
    - SSH 客户端和服务器的分析方法
- [RDFP](https://github.com/yahoo/rdfp)
    - 基于[FATT](https://github.com/0x4D31/fatt)（Fingerprint All The Things）的Zeek 远程桌面指纹识别脚本
- [FATT](https://github.com/0x4D31/fatt) 
    - 基于 pyshark 的脚本，用于从 pcap 文件和实时网络流量中提取网络元数据和指纹
- [FingerprintTLS](https://github.com/LeeBrotherston/tls-fingerprinting)
    - 一种 TLS 指纹识别方法
- [Mercury](https://github.com/cisco/mercury) 
    - 网络指纹识别和数据包元数据捕获
- [GQUIC_Protocol_Analyzer](https://github.com/salesforce/GQUIC_Protocol_Analyzer)
    - 适用于 Zeek 的 GQUIC 协议分析器
- [Recog](https://github.com/rapid7/recog)
    - 通过将指纹与从各种网络探测器返回的数据进行匹配来识别产品、服务、操作系统和硬件的框架
- [Hfinger](https://github.com/CERT-Polska/hfinger) 
    - 用于恶意软件识别的HTTP请求指纹





## 数据集

-   [Security Datasets](https://github.com/Cyb3rWard0g/mordor)
    -   以模拟攻防对抗技术出发，以JSON文件格式生成的各类安全事件数据集。数据按 Miter ATT&CK 框架定义的平台、对手组、策略和技术进行分类
    -   相关项目：[The ThreatHunter-Playbook](https://github.com/OTRF/ThreatHunter-Playbook)
-   [SecRepo.com](https://www.secrepo.com/)
    -   安全相关的数据样本
    -   [Github repo](https://github.com/sooshie/secrepo) 
-   [SOC (BOTS) 数据集v1](https://github.com/splunk/botsv1)
-   [SOC (BOTS) 数据集v2](https://github.com/splunk/botsv2)
-   [SOC (BOTS) 数据集v3](https://github.com/splunk/botsv3)
-   [EMBER](https://github.com/endgameinc/ember)
    -   PE文件特征集，可作为研究人员的基准数据集
    -   [相关论文](https://arxiv.org/abs/1804.04637)
-   [theZoo](https://github.com/ytisf/theZoo) 
    -   实时恶意软件的存储库
-   [CIC Datasets](https://www.unb.ca/cic/datasets/index.html)
    -   加拿大网络安全研究所的数据集
-   [Netresec's PCAP repo list](https://www.netresec.com/?page=PcapFiles)
    -   公共网络数据包存储库列表
-   [PCAP-ATTACK](https://github.com/sbousseaden/PCAP-ATTACK)
    -   用于不同 ATT&CK 技术的网络数据包样本
-   [EVTX-ATTACK-SAMPLES](https://github.com/sbousseaden/EVTX-ATTACK-SAMPLES) 
    -   与 ATT&CK技术相关的Windows 事件样本 ([EVTX-ATT&CK Sheet](https://docs.google.com/spreadsheets/d/12V5T9j6Fi3JSmMpAsMwovnWqRFKzzI9l2iXS5dEsnrs/edit#gid=164587082))  





## 资源

- [Huntpedia](assets/huntpedia.pdf)
    -   威胁狩猎知识纲领
    
- [Hunt Evil](assets/hunt-evil.pdf)
    - 威胁狩猎实用指南
    
- [The Hunter's Handbook](assets/The-Hunters-Handbook.pdf)
  
    - Endgame公司的威胁狩猎手册（Handbook）
    
- [ThreatHunter-Playbook](https://github.com/Cyb3rWard0g/ThreatHunter-Playbook)
  
    - 威胁猎人的演练脚本，可以帮助开发用于威胁狩猎活动的技术和理论假设
    
- 🌟[The ThreatHunting Project](https://github.com/ThreatHuntingProject/ThreatHunting) 
    - 大量的[狩猎案例](https://github.com/ThreatHuntingProject/ThreatHunting/tree/master/hunts)和狩猎资源
    
- [CyberThreatHunting](https://github.com/A3sal0n/CyberThreatHunting)
  
    - 威胁猎人的资源集合
    
- [Hunt-Detect-Prevent](https://github.com/MHaggis/hunt-detect-prevent)
  
    - 用于追捕、检测和阻止攻击者的资源与实用工具
    
- [Alerting and Detection Strategy Framework](https://medium.com/@palantir/alerting-and-detection-strategy-framework-52dc33722df2)
    - 一个用于事件响应与威胁检测的的警报、检测策略框架
    
- [Generating Hypotheses for Successful Threat Hunting](https://www.sans.org/reading-room/whitepapers/threats/generating-hypotheses-successful-threat-hunting-37172)
    - 探究自动化威胁狩猎的论文
    
- [Expert Investigation Guide - Threat Hunting](https://github.com/Foundstone/ExpertInvestigationGuides/tree/master/ThreatHunting)
    - 威胁狩猎指南
    
- [Active Directory Threat Hunting](https://adsecurity.org/wp-content/uploads/2017/04/2017-BSidesCharm-DetectingtheElusive-ActiveDirectoryThreatHunting-Final.pdf)
    - 基于活动目录的威胁狩猎
    
- [Threat Hunting for Fileless Malware](https://www.countercept.com/our-thinking/threat-hunting-for-fileless-malware/)
    - 对无文件攻击技术的威胁狩猎方法
    
- [Windows Commands Abused by Attackers](http://blog.jpcert.or.jp/.s/2016/01/windows-commands-abused-by-attackers.html)
    - 被攻击者滥用的Windows命令
    
- [Deception-as-Detection](https://github.com/0x4D31/deception-as-detection)
  
    - 与MITRE的ATT&CK框架对应的基于欺骗的检测技术
    
- [On TTPs](http://ryanstillions.blogspot.com.au/2014/04/on-ttps.html)
    - 深入浅出地讲解什么是TTPs
    
- 🌟Hunting On The Cheap（[YouTube](https://www.youtube.com/watch?v=RtG-cGr_wZI&ab_channel=SANSDigitalForensicsandIncidentResponse)）
    - Endgame 的威胁研究团队展示如何利用免费或几乎免费的数据源和开源工具来进行”便宜的“的威胁狩猎，主要包括蜜罐、开源沙箱、被动DNS数据的使用等
    
- 🐞[Threat Hunting Techniques - AV, Proxy, DNS and HTTP Logs](https://www.cyberhuntz.com/2016/08/threat-hunting-techniques-av-proxy-dns.html)

    - 对AV、代理、DNS 和 HTTP 日志进行威胁狩猎的技术

- [Detecting Malware Beacons Using Splunk](https://pleasefeedthegeek.wordpress.com/2012/12/20/detecting-malware-beacons-using-splunk/)

    - 使用Splunk检测恶意软件信标

    -   信标（Beacon）：定义为定期而非一次性的异常流量

- 🌟[Data Science Hunting Funnel](http://www.austintaylor.io/network/traffic/threat/data/science/hunting/funnel/machine/learning/domain/expertise/2017/07/11/data-science-hunting-funnel/)

    -   基于数据科学的威胁狩猎“漏斗”，用于说明数据科学在安全研究中的工作流程和应用方式

- [Use Python & Pandas to Create a D3 Force Directed Network Diagram](http://www.austintaylor.io/d3/python/pandas/2016/02/01/create-d3-chart-python-force-directed/)

    - 使用Python和Pandas创建D3力有向网络图

- [Syscall Auditing at Scale](https://slack.engineering/syscall-auditing-at-scale-e6a3ca8ac1b8)

    - 大规模系统调用的审计方法

- [Catching attackers with go-audit and a logging pipeline](https://summitroute.com/blog/2016/12/25/Catching_attackers_with_go-audit_and_a_logging_pipeline/)

    - 使用go-audit和日志记录管道文件捕获攻击者
    - 注：go-audit是auditd守护进程的一种替代方案，[GitHub](https://github.com/slackhq/go-audit)
    - 注：该篇文章中的日志记录管道文件指logstash与filebeat中的

- [The Coventry Conundrum of Threat Intelligence](https://summitroute.com/blog/2015/06/10/the_conventry_conundrum_of_threat_intelligence/)

    - 威胁情报中的“考文垂”难题，指情报分析人员是有应该对所获取的情报采取行动时面临的问题，因为采取相应行动会向攻击者暴露其所拥有的情报和相应能力
    - 注：考文垂（Coventry Conundrum） 一词来自二战中的一次事件，据推测，英国情报部门了解到考文垂市将遭到德国的大规模空袭。他们可以将即将到来的袭击通知考文垂市并拯救该市的人民，但德国人会意识到这座城市已被疏散，这将通知他们英国人知道即将到来的袭击，这可能使他们意识到英国人破解了 Enigma 密码，这将导致他们使用 Enigma 以外的其他东西，这最终可能导致英国输掉战争

- [Signal the ATT&CK: Part 1](https://www.pwc.co.uk/issues/cyber-security-data-privacy/research/signal-att-and-ck-part-1.html)

    - 使用Tanium构建实时威胁检测功能，专注于记录的对抗技术

- SANS Summit Archives ([DFIR](https://www.sans.org/cyber-security-summit/archives/dfir), [Cyber Defense](https://www.sans.org/cyber-security-summit/archives/cyber-defense)) 

    - 威胁狩猎、蓝队和DFIR峰会的PPT

- [Bro-Osquery](https://svs.informatik.uni-hamburg.de/publications/2018/2018-05-31-Haas-QueryCon-Bro-Osquery.pdf)

    - 使用开源软件进行大规模主机和网络监控

- [Malware Persistence](https://github.com/Karneades/malware-persistence)

    - 收集有关[恶意软件持久性](https://github.com/Karneades/malware-persistence)的各种信息：检测技术、响应方法、陷阱和日志收集（工具）

- [Threat Hunting with Jupyter Notebooks](https://posts.specterops.io/threat-hunting-with-jupyter-notebooks-part-1-your-first-notebook-9a99a781fde7)

    - 使用 Jupyter Notebook 进行威胁狩猎

- [How Dropbox Security builds tools for threat detection and incident response](https://dropbox.tech/security/how-dropbox-security-builds-better-tools-for-threat-detection-and-incident-response)

    - Dropbox Security 如何构建用于威胁检测和事件响应的工具

- [Introducing Event Query Language](https://www.elastic.co/blog/introducing-event-query-language)

    - 对事件查询语言的介绍

- [The No Hassle Guide to Event Query Language (EQL) for Threat Hunting](https://www.varonis.com/blog/guide-no-hassle-eql-threat-hunting/) ([PDF](assets/varonis.com-EQLforThreatHunting.pdf))

    - 用于威胁搜寻的事件查询语言 (EQL) 无障碍指南

- [Introducing the Funnel of Fidelity](https://posts.specterops.io/introducing-the-funnel-of-fidelity-b1bb59b04036) ([PDF](assets/specterops-IntroducingtheFunnelofFidelity.pdf))

    - SpecterOps的威胁情报漏斗：Fidelity，用于描述检测和相应过程的各个阶段

- [Detection Spectrum](https://posts.specterops.io/detection-spectrum-198a0bfb9302) ([PDF](assets/specterops-DetectionSpectrum.pdf))

    - SpecterOps的检测光谱，侧重于在Fidelity中的检测检测

- [Capability Abstraction](https://posts.specterops.io/capability-abstraction-fbeaeeb26384) ([PDF](assets/specterops-CapabilityAbstraction.pdf))

    - SpecterOps的能力抽象，用于帮助了解们整体检测程序的上下文

- [Awesome YARA](https://github.com/InQuest/awesome-yara)

    - 精选 YARA 规则、工具和资源列表

- [Defining ATT&CK Data Sources](https://medium.com/mitre-attack/defining-attack-data-sources-part-i-4c39e581454f)

    - 一个由两部分组成的博客系列，概述了扩展ATT&CK当前数据源的新方法



### 框架/模型

- [MITRE ATT&CK](https://attack.mitre.org/wiki/Main_Page)
    - 针对行为的精心设计的知识库和模型，反映了攻击者生命周期的各个阶段以及他们已知的目标
- [MITRE CAR](https://car.mitre.org/wiki/Main_Page)
    - Cyber Analytics Repository (CAR) 是 MITRE 基于 Adversary Tactics, Techniques, and Common Knowledge (ATT&CK™) 对手模型开发的分析知识库
- [Alerting and Detection Strategies Framework](https://github.com/palantir/alerting-detection-strategy-framework)
    - 用于开发告警和检测策略的框架
- [A Simple Hunting Maturity Model](http://detect-respond.blogspot.com.au/2015/10/a-simple-hunting-maturity-model.html)
    - 狩猎成熟度模型描述了组织狩猎能力的五个级别，范围从 HMM0（最低能力）到 HMM4（最高能力）
- [The Pyramic of Pain](http://detect-respond.blogspot.com.au/2013/03/the-pyramid-of-pain.html)
    - 可用于检测对手活动的指标类型之间的关系、评估情报价值
- [A Framework for Cyber Threat Hunting](assets/Framework-for-Threat-Hunting-Whitepaper.pdf)
    - 狩猎成熟度模型的介绍手册
- [The PARIS Model](http://threathunter.guru/blog/the-paris-model/)
    - PARIS威胁狩猎模型
    - 注：因为其模型形状类似于巴黎埃菲尔铁塔而得名
- [Cyber Kill Chain](https://www.lockheedmartin.com/us/what-we-do/aerospace-defense/cyber/cyber-kill-chain.html)
    - 杀伤链模型，是Intelligence Driven Defense® 模型的一部分，用于识别和预防网络入侵活动。该模型确定了对手必须完成哪些任务才能实现其目标，定义攻击里程碑
- [The DML Model](http://ryanstillions.blogspot.com.au/2014/04/the-dml-model_21.html)
    - 检测成熟度级别 (DML) 模型是一种能力成熟度模型，用于参考检测网络攻击的成熟度
- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
    - 美国国家标准暨技术研究院（NIST）的网络安全模型
- [OSSEM](https://github.com/hunters-forge/OSSEM) (Open Source Security Events Metadata)
    - 一个开源社区主导的项目，专注于来自不同数据源和操作系统的安全事件日志的文档和标准化
- [MITRE Shield](https://shield.mitre.org)
    - 与ATT&CK模型相对应的主动防御技术和战术的知识库（[Active Defense Matrix](https://shield.mitre.org/matrix/), [主动防御矩阵](https://shield.mitre.org/matrix/)）



### 基于DNS数据的威胁狩猎

- [Detecting DNS Tunneling](https://www.sans.org/reading-room/whitepapers/dns/detecting-dns-tunneling-34152)
    - 检测DNS隐蔽隧道
- [Hunting the Known Unknowns (with DNS)](https://www.splunk.com/pdfs/events/govsummit/hunting_the_known_unknowns_with_DNS.pdf)
    - 使用DNS数据发现已知与未知的安全威胁
- 🌟[Detecting dynamic DNS domains in Splunk](https://www.splunk.com/blog/2015/08/04/detecting-dynamic-dns-domains-in-splunk.html)
    - 在Splunk中检测使用动态DNS服务的域名
- [Random Words on Entropy and DNS](https://www.splunk.com/blog/2015/10/01/random-words-on-entropy-and-dns.html)
    - 介绍在威胁狩猎过程中对DNS数据中的具有相对较高熵的域和子域进行检测的过程
- [Tracking Newly Registered Domains](https://isc.sans.edu/diary/Tracking+Newly+Registered+Domains/23127)
    - 监测新注册域名
- [Suspicious Domains Tracking Dashboard](https://isc.sans.edu/forums/diary/Suspicious+Domains+Tracking+Dashboard/23046/)
    - 可疑域名监测面板
- [Proactive Malicious Domain Search](https://isc.sans.edu/forums/diary/Proactive+Malicious+Domain+Search/23065/)
    -   借助证书透明度项目进行主动的恶意域名发现
- [DNS is NOT Boring](https://www.first.org/resources/papers/conf2017/DNS-is-NOT-Boring-Using-DNS-to-Expose-and-Thwart-Attacks.pdf)
    - 使用DNS数据发现和组织恶意攻击
- [Actionable Detects](https://prezi.com/vejpnxkm85ih/actionable-detects-dns-keynote/)
    - 使用DNS数据进行防守的蓝队策略



### 命令与控制（C2）相关

- [Rise of Legitimate Services for Backdoor Command and Control](assets/legit-services.pdf)
    -   使用合法的互联网服务作为命令和控制 (C2) 模式一部分的恶意软件技术
- [Watch Your Containers](https://www.intezer.com/container-security/watch-your-containers-doki-infecting-docker-servers-in-the-cloud/)
    -  一种使用基于 DogeCoin的DGA生成 C2 域名的恶意软件

- [Hiding in Plain Sight](https://blog.huntresslabs.com/hiding-in-plain-sight-part-2-dfec817c036f)
    - 一种滥用 Google DoH 的恶意软件
- [All the DoH](https://twitter.com/stvemillertime/status/1196788709292687360)
    - 使用DNS-over-HTTPS 的恶意软件，Twitter贴文



### Osquery

-   注：Osquery一个 SQL 驱动的操作系统检测、监控和分析框架
-   [osquery Across the Enterprise](https://medium.com/@palantir/osquery-across-the-enterprise-3c3c9d13ec55)
    -   使用Osquery进行企业安全检测和威胁狩猎
-   [osquery for Security — Part 1](https://medium.com/@clong/osquery-for-security-b66fffdf2daf)
    -   Osquery教程-Part 1，本篇主要讲解在企业安全环境下部署
-   [osquery for Security — Part 2](https://medium.com/@clong/osquery-for-security-part-2-2e03de4d3721)
    -   Osquery教程-Part 2，本篇主要讲解高级 osquery 功能、文件完整性监控、进程审计等
-   [Tracking a stolen code-signing certificate with osquery](https://blog.trailofbits.com/2017/10/10/tracking-a-stolen-code-signing-certificate-with-osquery/)
    -   使用Osquery追踪被窃取的证书签名
-   [Monitoring macOS hosts with osquery](https://blog.kolide.com/monitoring-macos-hosts-with-osquery-ba5dcc83122d)
    -   使用Osquery监控macOS主机
-   [Threat hunting with Kolide and osquery](https://resources.infosecinstitute.com/topic/threat-hunting-with-kolide-and-osquery/)
    -   使用使用[Kolide Fleet](https://kolide.com/fleet/)进行威胁狩猎
    -   注：Kolide Fleet 是一个灵活的控制服务器，可用于管理Osquery队列

### Windows

- [Threat Hunting via Windows Event Logs](https://www.sans.org/summit-archives/file/summit-archive-1524493093.pdf)
    - 通过 Windows 事件日志进行威胁追踪
- [Windows Logging Cheat Sheets](https://www.malwarearchaeology.com/cheat-sheets/)
    -   调查受感染系统时可以重点关注的的Windows日志路径，备忘清单
- [Active Directory Threat Hunting](https://adsecurity.org/wp-content/uploads/2017/04/2017-BSidesCharm-DetectingtheElusive-ActiveDirectoryThreatHunting-Final.pdf)
    - 在Windows活动目录中
- [Windows Hunting](https://github.com/beahunt3r/Windows-Hunting)
    - 整理在Windows系统中进行威胁狩猎的常见
- [Windows Commands Abused by Attackers](https://blogs.jpcert.or.jp/en/2016/01/windows-commands-abused-by-attackers.html)
    - 被攻击者滥用的Windows命令
- [JPCERT - Detecting Lateral Movement through Tracking Event Logs](https://blogs.jpcert.or.jp/en/2017/12/research-report-released-detecting-lateral-movement-through-tracking-event-logs-version-2.html)
    - 通过跟踪事件日志检测攻击者的横向渗透
- [Tool Analysis Result Sheet](https://jpcertcc.github.io/ToolAnalysisResultSheet/)
    - 总结了49种常用于渗透的工具在执行后，对应在Windows中的日志

#### Sysmon

-   注：Sysmon是微软的一款轻量级的系统监控工具，它通过系统服务和驱动程序实现记录进程创建、文件访问以及网络信息的记录，并把相关的信息写入并展示在windows的日志事件里

- [Splunking the Endpoint: Threat Hunting with Sysmon](https://medium.com/@haggis_m/splunking-the-endpoint-threat-hunting-with-sysmon-9dd956e3e1bd)
    - [Hunting with Sysmon](https://medium.com/@haggis_m/hunting-with-sysmon-38de012e62e6)
    - 基于Sysmon进行威胁狩猎
- [Threat Hunting with Sysmon: Word Document with Macro](http://www.syspanda.com/index.php/2017/10/10/threat-hunting-sysmon-word-document-macro/)
    - 基于Sysmon狩猎带有宏的Word文档
- Chronicles of a Threat Hunter: Hunting for In-Memory Mimikatz with Sysmon and ELK
    - [Part I (Event ID 7)](https://cyberwardog.blogspot.com.au/2017/03/chronicles-of-threat-hunter-hunting-for.html)
    - [Part II (Event ID 10)](https://cyberwardog.blogspot.com.au/2017/03/chronicles-of-threat-hunter-hunting-for_22.html)
    - 使用Sysmon和ELK发现内存中的 Mimikatz
- Advanced Incident Detection and Threat Hunting using Sysmon (and Splunk) ([botconf 2016 Slides](https://www.botconf.eu/wp-content/uploads/2016/11/PR12-Sysmon-UELTSCHI.pdf), [FIRST 2017 Slides](https://www.first.org/resources/papers/conf2017/Advanced-Incident-Detection-and-Threat-Hunting-using-Sysmon-and-Splunk.pdf))
    - 使用 Sysmon和Splunk进行高级事件检测和狩猎
- [Sysmon Threat Detection Guide](https://www.varonis.com/blog/sysmon-threat-detection-guide/) ([PDF](assets/varonis.com-SysmonThreatAnalysisGuide.pdf))
    - Sysmon威胁分析指南

#### PowerShell

- Revoke-Obfuscation: PowerShell Obfuscation Detection Using Science ([Paper](https://www.blackhat.com/docs/us-17/thursday/us-17-Bohannon-Revoke-Obfuscation-PowerShell-Obfuscation-Detection-And%20Evasion-Using-Science-wp.pdf), [Slides](https://www.blackhat.com/docs/us-17/thursday/us-17-Bohannon-Revoke-Obfuscation-PowerShell-Obfuscation-Detection-And%20Evasion-Using-Science.pdf))
    - 使用数据科学进行PowerShell混淆检测
- [Hunting the Known Unknowns (With PowerShell)](https://conf.splunk.com/files/2016/slides/hunting-the-known-unknowns-the-powershell-edition.pdf)
    - 使用PowerShell进行威胁狩猎
- [HellsBells, Let's Hunt PowerShells!](https://www.splunk.com/blog/2017/07/06/hellsbells-lets-hunt-powershells.html)
    - 检测PowerShell的一些方法和技巧
- [Hunting for PowerShell Using Heatmaps](https://medium.com/@jshlbrd/hunting-for-powershell-using-heatmaps-69b70151fa5d)
    - 可视化（热图）狩猎PowerShell

### 指纹

- [JA3: SSL/TLS Client Fingerprinting for Malware Detection](https://engineering.salesforce.com/open-sourcing-ja3-92c9e53c3c41)
    - 使用JA3指纹进行恶意软件检测
    - 注：JA3指纹属于SSL/TLS协商指纹，其计算所需字段从协商信息中获取，用于在流量层识别特定客户端与服务器之间的加密通讯
- [TLS Fingerprinting with JA3 and JA3S](https://engineering.salesforce.com/tls-fingerprinting-with-ja3-and-ja3s-247362855967)
    - 对JA3/JA3S指纹计算原理及应用场景的讲解
- [HASSH - a profiling method for SSH Clients and Servers](https://engineering.salesforce.com/open-sourcing-hassh-abed3ae5044c)
    - [HASSH @BSides Canberra 2019 - Slides](https://github.com/benjeems/Presentations/blob/master/BSides%202019%20%20-%20HASSH%20-%20a%20Profiling%20Method%20for%20SSH%20Clients%20and%20Servers.pdf)
    - HASSH，对SSH协议进行流量层指纹识别的一个方案
- [Finding Evil on the Network Using JA3/S and HASSH](https://engineering.salesforce.com/finding-evil-on-the-network-using-ja3-s-and-hassh-11431a8606e4)
    - 使用JA3/JA3S和HASSH进行威胁狩猎的演讲
- [RDP Fingerprinting - Profiling RDP Clients with JA3 and RDFP](https://medium.com/@0x4d31/rdp-client-fingerprinting-9e7ac219f7f4)
    - 使用JA3和RDFP识别RDP客户端
- [Effective TLS Fingerprinting Beyond JA3](https://www.ntop.org/ndpi/effective-tls-fingerprinting-beyond-ja3/)
    - 在JA3计算的基础上，提出了的优化方向，包括使用ALPN（应用层协议协商）和客户端支持的TLS协议版本
- [TLS Fingerprinting in the Real World](https://blogs.cisco.com/security/tls-fingerprinting-in-the-real-world)
    - 对TLS指纹的业务场景介绍
- [HTTP Client Fingerprinting Using SSL Handshake Analysis](https://www.ssllabs.com/projects/client-fingerprinting/) (source code: [mod_sslhaf](https://github.com/ssllabs/sslhaf))
    - 基于SSL协商进行HTTP指纹的识别
- [TLS fingerprinting - Smarter Defending & Stealthier Attacking](https://blog.squarelemon.com/tls-fingerprinting/)
    - 介绍TLS指纹的定义和工具（包括FingerprinTLS和Fingerprintout）
- [JA3er](https://ja3er.com)
    - JA3指纹库
- [An Introduction to HTTP fingerprinting](https://www.net-square.com/httprint_paper.html)
    - 对HTTP指纹的简介
- [TLS Fingerprints](https://tlsfingerprint.io/)
    - 从科罗拉多大学博尔德校区网络收集的TLS指纹
- [The use of TLS in Censorship Circumvention](https://tlsfingerprint.io/static/frolov2019.pdf)
    - 论文，TLS在规避审查中的应用
- [TLS Beyond the Browser: Combining End Host and Network Data to Understand Application Behavior](https://dl.acm.org/doi/pdf/10.1145/3355369.3355601)
    - 论文，结合终端主机和网络数据来了解应用程序行为
- [HTTPS traffic analysis and client identification using passive SSL/TLS fingerprinting](https://link.springer.com/article/10.1186/s13635-016-0030-7)
    - 论文，使用被动SSL/TLS指纹识别的HTTPS流量分析进行客户端识别
- [Markov Chain Fingerprinting to Classify Encrypted Traffic](https://drakkar.imag.fr/IMG/pdf/1569811033.pdf)
    - 论文，使用马尔可夫链指纹（Markov Chain Fingerprinting）对加密流量进行分类
- [HeadPrint: Detecting Anomalous Communications through Header-based Application Fingerprinting](https://www.conand.me/publications/bortolameotti-headprint-2020.pdf)
    - 论文，通过基于标题的应用程序指纹检测异常通信

### 研究报告

- [Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains](https://www.lockheedmartin.com/content/dam/lockheed/data/corporate/documents/LM-White-Paper-Intel-Driven-Defense.pdf)
  - 论文，通过分析对抗行为和入侵杀伤链进行情报驱动的计算机网络防护
- [The Diamond Model of Intrusion Analysis](http://www.activeresponse.org/wp-content/uploads/2013/07/diamond.pdf)
  - 论文，入侵分析的钻石模型
- [EXPOSURE: Finding Malicious Domains Using Passive DNS Analysis](https://www.cs.ucsb.edu/~chris/research/doc/ndss11_exposure.pdf)
  - 论文，通过被动DNS（Passive DNS）分析查找恶意域名
- A Comprehensive Approach to Intrusion Detection Alert Correlation ([Paper](https://www.cs.ucsb.edu/~vigna/publications/2004_valeur_vigna_kruegel_kemmerer_TDSC_Correlation.pdf), [Dissertation](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.115.8310&rep=rep1&type=pdf))
  - 论文，入侵检测告警关联的综合方法
- [On Botnets that use DNS for Command and Control](http://www.few.vu.nl/~herbertb/papers/feederbot_ec2nd11.pdf)
  - 使用DNS进行C2的僵尸网络
- [Intelligent, Automated Red Team Emulation](https://dl.acm.org/citation.cfm?id=2991111)
  - 论文，自动化红队模拟
- [Machine Learning for Encrypted Malware Traffic Classification](https://dl.acm.org/doi/pdf/10.1145/3097983.3098163)
  - 论文，用于加密恶意软件流量分类的机器学习

### 相关博客

- [David Bianco's Blog](https://detect-respond.blogspot.com)
- [DFIR and Threat Hunting Blog](http://findingbad.blogspot.com)
- [CyberWardog's Blog](https://medium.com/@Cyb3rWard0g) ([old](https://cyberwardog.blogspot.com))
- [Chris Sanders' Blog](https://chrissanders.org)
- [Kolide Blog](https://blog.kolide.com/)

### 相关视频

- [SANS Threat Hunting and IR Summit 2017](https://www.youtube.com/playlist?list=PLfouvuAjspTr95R60Kt7ZcoerR6tYoCLA)
- [SANS Threat Hunting and IR Summit 2016](https://www.youtube.com/playlist?list=PLfouvuAjspTokaa-LdUHqszL-KACkCsKT)
- [BotConf 2016 - Advanced Incident Detection and Threat Hunting using Sysmon and Splunk](https://www.youtube.com/watch?v=vv_VXntQTpE)
- [BSidesCharm 2017 - Detecting the Elusive: Active Directory Threat Hunting](https://www.youtube.com/watch?v=9Uo7V9OUaUw)
- [BSidesAugusta 2017 - Machine Learning Fueled Cyber Threat Hunting](https://www.youtube.com/watch?v=c-c-IQ5pFXw)
- [Toppling the Stack: Outlier Detection for Threat Hunters](https://www.youtube.com/watch?v=7q7GGg-Ws9s)
- [BSidesPhilly 2017 - Threat Hunting: Defining the Process While Circumventing Corporate Obstacles](https://www.youtube.com/watch?v=bDdsGBCUa8I)
- [Black Hat 2017 - Revoke-Obfuscation: PowerShell Obfuscation Detection (And Evasion) Using Science](https://www.youtube.com/watch?v=x97ejtv56xw)
- [DefCon 25 - MS Just Gave the Blue Team Tactical Nukes](https://www.youtube.com/watch?v=LUtluTaEAUU)
- [BSides London 2017 - Hunt or be Hunted](https://www.youtube.com/watch?v=19H7j_sZcKc)
- [SecurityOnion 2017 - Pivoting Effectively to Catch More Bad Guys](https://www.youtube.com/watch?v=_QVhMPGtIeU)
- [SkyDogCon 2016 - Hunting: Defense Against The Dark Arts](https://www.youtube.com/watch?v=mKxGulV2Z74)
- [BSidesAugusta 2017 - Don't Google 'PowerShell Hunting'](https://www.youtube.com/watch?v=1mfVPLPxKTc)
- [BSidesAugusta 2017 - Hunting Adversaries w Investigation Playbooks & OpenCNA](https://www.youtube.com/watch?v=8qM-DnmHNv8)
- [Visual Hunting with Linked Data](https://www.youtube.com/watch?v=98MrgfTFeMo)
- [RVAs3c - Pyramid of Pain: Intel-Driven Detection/Response to Increase Adversary's Cost](https://www.youtube.com/watch?v=zlAWbdSlhaQ)
- [BSidesLV 2016 - Hunting on the Endpoint w/ Powershell](https://www.youtube.com/watch?v=2MrrOxsJk_M)
- [Derbycon 2015 - Intrusion Hunting for the Masses A Practical Guide](https://www.youtube.com/watch?v=MUUseTJp3jM)
- [BSides DC 2016 - Practical Cyborgism: Getting Start with Machine Learning for Incident Detection](https://www.youtube.com/watch?v=2FvP7nwb2UE&feature=youtu.be)
- [SANS Webcast 2018 - What Event Logs? Part 1: Attacker Tricks to Remove Event Logs](https://www.youtube.com/watch?v=7JIftAw8wQY)
- [Profiling And Detecting All Things SSL With JA3](https://www.youtube.com/watch?v=oprPu7UIEuk)
- [ACoD 2019 - HASSH SSH Client/Server Profiling](https://www.youtube.com/watch?v=kG-kenOypLk)
- [QueryCon 2018](https://www.youtube.com/playlist?list=PLlSdCcsTOu5STvaoPlr-PJE-zbYmlAGrX) - An annual conference for the osquery open-source community ([querycon.io](https://querycon.io))
- [Visual Hunting with Linked Data Graphs](https://www.youtube.com/watch?v=EpK7MkWCh1I)
- [SecurityOnion Con 2018 - Introduction to Data Analysis](https://www.youtube.com/watch?v=A6hBoeSNJJw)

### 相关课程

- [SANS SEC555](https://www.sans.org/course/siem-with-tactical-analytics) - SIEM with Tactical Analytics.
    - 在SIEM中进行战术（Tactics）分析
- [SpecterOps Adversary Tactics: PowerShell](https://github.com/specterops/at-ps) (FREE)
- [SpecterOps Adversary Tactics: Detection](https://specterops.io/how-we-help/training-offerings/adversary-tactics-detection)





## References

\[1] Osquery检测入侵痕迹, [EvilAnne](https://evilanne.github.io/about/), https://evilanne.github.io/2019/02/20/Osquery%E6%A3%80%E6%B5%8B%E5%85%A5%E4%BE%B5%E7%97%95%E8%BF%B9/

\[2] 微软轻量级系统监控工具sysmon原理与实现完全分析（上篇）, [浪子_三少](https://www.anquanke.com/member/123937), https://www.anquanke.com/post/id/156704

\[3] 甲方视角浅析MITRE ATT&CK ，[chiweiwei ](https://www.freebuf.com/author/chiweiwei)，https://www.freebuf.com/articles/es/249278.html

