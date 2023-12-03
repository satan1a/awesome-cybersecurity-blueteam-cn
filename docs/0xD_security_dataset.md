---
title: 📊安全领域数据集
---

>   转载、改写自[Awesome Machine Learning for Cyber Security](https://github.com/jivoi/awesome-ml-for-cybersecurity)、[Awesome-Cybersecurity-Datasets](https://github.com/shramos/Awesome-Cybersecurity-Datasets)、[机器学习之安全数据集 - wstart](https://xz.aliyun.com/u/395)



# 安全领域数据集

## 目录

[TOC]

## 综合数据集

-   [SecRepo.com](https://www.secrepo.com/) - [Samples of Security Related Data](https://github.com/sooshie/secrepo)
    -   整理大量安全相关的数据集，包括网络、恶意软件、文件等
-   [Security Data Analysis](https://github.com/sooshie/Security-Data-Analysis)
    -   总共4个lab，包含http，连接记录，域名，host等
-   [WebShell收集项目](https://github.com/tennc/webshell)
    -   包含多种类型的WebShell数据集
-   AZSecure
    -   [官网](https://www.azsecure-data.org/)
    -   收集来自不同渠道的暗网论坛、市场和社交媒体数据



## 网络类数据集

-   [HIKARI-2021 Datasets](https://zenodo.org/record/5199540)
-   [Samples of Security Related Data](http://www.secrepo.com/)
-   [DARPA Intrusion Detection Data Sets](https://www.ll.mit.edu/r-d/datasets) [ [1998](https://www.ll.mit.edu/r-d/datasets/1998-darpa-intrusion-detection-evaluation-dataset) / [1999](https://www.ll.mit.edu/r-d/datasets/1999-darpa-intrusion-detection-evaluation-dataset) ]
-   [Stratosphere IPS Data Sets](https://stratosphereips.org/category/dataset.html)
-   [Open Data Sets](http://csr.lanl.gov/data/)
-   [Data Capture from National Security Agency](http://www.westpoint.edu/crc/SitePages/DataSets.aspx)
-   [The ADFA Intrusion Detection Data Sets](https://www.unsw.adfa.edu.au/australian-centre-for-cyber-security/cybersecurity/ADFA-IDS-Datasets/)
    -   **ADFA IDS Datasets** 是澳大利亚国防大学发布的一套关于HIDS的数据集。分为Linux（ADFA-LD）和Windows（ADFA-WD）
    -   内容类型：主机行为
    -   是否特征化：是
    -   使用范围：入侵检测
-   [NSL-KDD Data Sets](https://github.com/defcom17/NSL_KDD)
-   [Malicious URLs Data Sets](http://sysnet.ucsd.edu/projects/url/)
-   [Multi-Source Cyber-Security Events](http://csr.lanl.gov/data/cyber1/)
-   [KDD Cup 1999 Data](http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html)
    -   KDD竞赛在1999年举行时采用的数据集。1998年美国国防部高级规划署（DARPA）在MIT林肯实验室进行了一项入侵检测评估项目收集而来的数据
    -   内容类型：网络流量、主机行为
    -   是否特征化：是
    -   适用范围：主机入侵检测、异常流量监控
-   [Web Attack Payloads](https://github.com/foospidy/payloads)
-   [WAF Malicious Queries Data Sets](https://github.com/faizann24/Fwaf-Machine-Learning-driven-Web-Application-Firewall)
-   [Malware Training Data Sets](https://github.com/marcoramilli/MalwareTrainingSets)
-   [Aktaion Data Sets](https://github.com/jzadeh/Aktaion/tree/master/data)
-   [CRIME Database from DeepEnd Research](https://www.dropbox.com/sh/7fo4efxhpenexqp/AADHnRKtL6qdzCdRlPmJpS8Aa/CRIME?dl=0)
-   [Publicly available PCAP files](http://www.netresec.com/?page=PcapFiles)
-   [2007 TREC Public Spam Corpus](https://plg.uwaterloo.ca/~gvcormac/treccorpus07/)
-   [Drebin Android Malware Dataset](https://www.sec.cs.tu-bs.de/~danarp/drebin/)
-   [PhishingCorpus Datset](https://monkey.org/~jose/phishing/)
-   [EMBER](https://github.com/endgameinc/ember)
-   [Vizsec Research](https://vizsec.org/data/)
-   [SHERLOCK](http://bigdata.ise.bgu.ac.il/sherlock/index.html#/)
-   [Probing / Port Scan - Dataset](https://github.com/gubertoli/ProbingDataset)
-   [Aegean Wireless Intrusion Dataset (AWID)](http://icsdweb.aegean.gr/awid/)
-   [HTTP DATASET CSIC 2010](http://www.isi.csic.es/dataset/)
    -   **HTTP DATASET CSIC 2010** 包含已经标注过的针对web服务的请求。数据量约5w条。下载地址已经为我们分类好了训练用的正常数据，测试用的正常数据，测试用的异常数据
    -   内容类型：网络流量
    -   是否特征化：否
    -   使用范围：WAF类产品、异常流量监控
-   [honeypot.json](http://www.secrepo.com/honeypot/honeypot.json.zip)
    -   honeypot 是由多种类型的蜜罐采集回来的数据。主要是WEB请求。约99万条数据。由于没有分类和规整，需要自己数据清洗，也可以用作校验模型的数据
    -   内容类型：网络流量
    -   是否特征化：否
    -   使用范围：WAF类产品、异常流量监控
-   [Masquerading User Data](https://xz.aliyun.com/t/1879)
    -   **Masquerading User Data**（也被称为SEA数据集） 是Matthias Schonlau 教授通过正常数据构造出来用于训练和检测 Masquerading User攻击的数据集(内部攻击者分为两种，一种是内鬼[Traitor]，一种是窃取了身份凭证的正常用户的伪装者[Masquerading User]）由于是构造出来的数据，缺乏实际攻击的真实性，在一定程度上，训练出来的模型会存在一定的过拟
    -   内容类型：主机行为
    -   是否特征化：否
    -   使用范围：入侵检测类、用户异常行为识别
-   [360DGA](http://data.netlab.360.com/dga/)
    -   360安全厂商提供的DGA数据集，用于DAG域名检测，可作为黑样本
    -   内容类型：文本样本
    -   是否特征化：否
    -   使用范围：入侵检测、异常流量、WAF
-   [Gameover Zeus DGA sample](https://www.secrepo.com/misc/zeus_dga_domains.txt.zip) 2014
    -   Zeus P2P僵尸网络的DGA恶意样本数据
    -   内容类型：文本样本
    -   是否特征化：否
    -   使用范围：入侵检测、异常流量、WAF
-   [auth.log](http://www.secrepo.com/auth.log/auth.log.gz)
    -   **auth.log** 主要是都是登录失败的日志 适合用作判断是爆破登录还是正常的输错密码
    -   内容类型：主机行为
    -   是否特征化：否
    -   使用范围：入侵检测、异常流量、WAF
-   [malicious-URLs](https://github.com/faizann24/Using-machine-learning-to-detect-malicious-URLs)
    -   **malicious-URLs** 在Github上面一个 使用机器学习去检测恶意URL的项目 ，里面有一个训练集，有做标记是正常的URL还是恶意的URL
    -   内容类型：文本样本
    -   是否特征化：否
    -   使用范围：入侵检测、异常流量、WAF
-   [The Malware Capture Facility Project](https://mcfp.weebly.com/mcfp-dataset.html)
    -   **MCFP** 是捷克理工大学 (CTU)用于捕抓恶意软件的而抓去的网络流量。里面的数据非常多，有他们自己分析出来的恶意流量，也有所有的流量，包括网络文件、日志、DNS请求等
    -   内容类型：网络流量
    -   是否特征化：否
    -   使用范围：异常流量、WAF
-   [MalwareDB](https://github.com/BaRRaKudaRain/MalwareDB)
    -   恶意软件库，包含恶意软件列表hash、检测结果、所属域名等数据
    -   内容类型：文本样本
    -   使用范围:：特征库、入侵检测
-   [flightsim](https://github.com/alphasoc/flightsim)
    -   一个工具，可以生成数据恶意流量数据，模拟DNS隧道、DGA通信、对活跃的C2服务器请求和其他一些可疑的流量数据
    -   内容类型：网络流量（模拟）
    -   是否特征化：否
    -   使用范围：异常流量、WAF、入侵检测
-   [mordor](https://github.com/OTRF/mordor)
    -   模拟攻防对抗生成的安全事件数据，以JSON格式提供，并且按照[ATT＆CK框架](https://attack.mitre.org/wiki/Main_Page)的定义。可以用于对攻防技术（TTPs）的检测。[说明文档](https://mordordatasets.com/introduction.html)。
    -   内容类型：文本样本
    -   是否特征化：否
    -   适用范围：入侵检测、行为识别



## 恶意软件数据集

-   [UNSW-NB15 data set](https://www.unsw.adfa.edu.au/unsw-canberra-cyber/cybersecurity/ADFA-NB15-Datasets/)
    -   该数据集包含九种攻击类型，分别为：模糊攻击（Fuzzers）、分析（Analysis）、后门（Backdoors）、拒绝服务攻击（DoS）、利用（Exploits）、通用（Generic）、侦察（Reconnaissance）、Shellcode 和蠕虫（Worms）
    -   使用了Argus、Bro-IDS工具，并开发了十二种算法，以生成包含类别标签的共49个特征

-   [Malware Training Sets](https://marcoramilli.blogspot.com/2016/12/malware-training-sets-machine-learning.html)
    -   该数据集的组成为：APT1 292个样本，Crypto 2024个样本，Locker 434个样本，Zeus 2014个样本

-   [The Drebin Dataset](https://www.sec.cs.tu-bs.de/~danarp/drebin/)
    -   该数据集包含来自179个不同恶意软件家族的5,560个应用程序样本。样本收集时间为2010年8月至2012年10月，由MobileSandbox项目提供

-   [Stratosphere IPS](https://www.stratosphereips.org/datasets-overview/)
    -   该数据集包含恶意软件捕获、正常捕获、混合捕获等

-   [Microsoft Malware Classification Challenge](https://www.kaggle.com/c/malware-classification/data)
    -   该数据集提供了一组已知的恶意软件文件，代表9个不同家族的混合。每个恶意软件文件都有一个ID，一个20字符的哈希值，用于唯一识别文件，以及一个类别，一个整数，代表9个家族名称之一。

-   [Javascript Vulnerability Dataset](http://www.inf.u-szeged.hu/~ferenc/papers/JSVulnerabilityDataSet/)
    -   该数据集是根据Node Security Project和Snyk平台的公共数据库中的漏洞信息，以及GitHub上的代码修复补丁构建的

-   [ember](https://github.com/endgameinc/ember)
    -   ember数据集是一个包含了2017年某个时候扫描的110万个PE文件的sha256哈希集合
    -   该数据便于可重现地训练基准模型，扩展提供的特征集，或使用基准模型对新的PE文件进行分类




## 邮件数据集

-   [SpamBase](http://archive.ics.uci.edu/ml/datasets/Spambase)
    -   一个入门级的垃圾邮件分类训练集，已被特征化处理。特征为统计的关键字、特殊符号的词频等，一共58个属性，最后一位是垃圾邮件标记位
    -   内容类型：文本样本、邮件（特征化）
    -   是否特征化：是
    -   适用范围：垃圾邮件检测
-   [2007 TREC Public Spam Corpus](https://plg.uwaterloo.ca/~gvcormac/treccorpus07/about.html) 
-   [SPAM list](https://techhelplist.com/spam-list)



## 欺诈数据集

-   [Credit Card Fraud](https://www.kaggle.com/samkirkiles/credit-card-fraud/data)
    -   信用卡交易数据集，该数据集包含了2013年9月欧洲卡持有人进行的信用卡交易。数据集呈现了两天内发生的交易情况，其中共有284,807笔交易，492笔为欺诈行为。该数据集占比非常不平衡，积极类别（欺诈行为）占所有交易的0.172%。




## 蜜罐数据集

-   [DDS Dataset Collection](http://datadrivensecurity.info/blog/pages/dds-dataset-collection.html)
    -   来自AWS蜜罐集合的tar/gzip格式的CSV文件
    -   包含域名的zip格式CSV文件，以及对dga（域名生成算法）或合法域名的高级分类，及其子类别，包括合法、cryptolocker、gox或newgoz

-   [Threat_Research](https://github.com/JonathanPhillips/Threat_Research) - Centralized repository to dump threat research data gathered from my network of honeypots.



## 钓鱼数据集

-   [Phishing Websites Data Set](https://archive.ics.uci.edu/ml/datasets/phishing+websites#)
    -   此数据集主要收集自：PhishTank、MillerSmiles、Google搜索
