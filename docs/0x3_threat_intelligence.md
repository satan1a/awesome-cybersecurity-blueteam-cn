---
title: ✉️ 威胁情报大合集
---

>   改写自[awesome-threat-intelligence](https://github.com/hslatman/awesome-threat-intelligence)

# 威胁情报大合集

威胁情报的简明定义：基于证据的知识，包括上下文、机制、指标、影响与和可行的建议，关于现有或新出现对资产的威胁或风险，可被用来告知有关威胁响应的决定


## 资源

下面列表中提到的大多数资源/API 都是用来获得最新的威胁情报信息。
有些人不认为这些资源可以当成威胁情报。但是对基于特定域或特定业务的真实威胁情报进行分析是很必要的。

| 项目名称                                                     | 介绍                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [AbuseIPDB](https://www.abuseipdb.com/)                      | AbuseIPDB 是一个致力于帮助打击黑客、垃圾邮件发送者与互联网滥用的项目。为网站管理员、系统管理员和其他各方提供中心黑名单，提交查找与恶意活动相关的 IP 地址来帮助网络更加安全 |
| [Alexa Top 1 Million sites](https://s3.amazonaws.com/alexa-static/top-1m.csv.zip) | 亚马逊提供的 Alexa TOP 100 万排名的网站。永远[不要](http://threatglass.com/pages/about)作为[白名单](https://www.netresec.com/?page=Blog&month=2017-04&post=Domain-Whitelist-Benchmark%3a-Alexa-vs-Umbrella)使用 |
| [Apility.io](http://Apility.io)                              | [Apility.io](http://Apility.io) 是一个简单的反滥用 API 的黑名单，它可以从多个来源帮助用户查询 IP、域名、电子邮件是否被列入黑名单 |
| [APT Groups and Operations](https://docs.google.com/spreadsheets/u/1/d/1H9_xaxQHpWaa4O_Son4Gx0YOIzlcBWMsdvePFX68EKU/pubhtml) | 一个包含有 APT 组织信息、行动和策略的表格                    |
| [AutoShun](https://www.autoshun.org/)                        | 提供不到两千个恶意 IP 地址和其他一些资源的公共服务           |
| [BGP Ranking](https://www.circl.lu/projects/bgpranking/)     | 提供恶意内容最多的 ASN 排名                                  |
| [Botnet Tracker](https://intel.malwaretech.com/)             | 对一些活跃的僵尸网络跟踪                                     |
| [BOTVRIJ.EU](http://www.botvrij.eu/)                         | [Botvrij.eu](http://Botvrij.eu) 提供了不同种类的开源 IOC，可以在安全设备中使用来检测潜在的恶意活动 |
| [BruteForceBlocker](http://danger.rulez.sk/projects/bruteforceblocker/) | BruteForceBlocker 是一个旨在监视服务器上 sshd 日志来阻止暴力破解攻击的 perl 脚本，可以自动配置防火墙阻止规则并且提交恶意 IP 到项目地址, http://danger.rulez.sk/projects/bruteforceblocker/blist.php. |
| [C&C Tracker](http://osint.bambenekconsulting.com/feeds/c2-ipmasterlist.txt) | Bambenek Consulting 提供的活动 C&C 服务器的 IP 地址跟踪      |
| [CertStream](https://certstream.calidog.io/)                 | 实时证书透明度日志更新流，可以实时查询可能存在问题的证书     |
| [CCSS Forum Malware Certificates](http://www.ccssforum.org/malware-certificates.php) | 论坛报告的数字证书列表，列出那些潜在与恶意软件相关的各种证书颁发机构，此信息旨在防止公司根据数字证书判断恶意软件合法，并鼓励其撤销对此类证书的信任 |
| [CI Army List](http://cinsscore.com/list/ci-badguys.txt)     | 商业列表 [CINS Score](http://cinsscore.com/) 的子集，聚焦于提供那些其他情报列表重没有的恶意IP地址 |
| [Cisco Umbrella](https://s3-us-west-1.amazonaws.com/umbrella-static/index.html) | Cisco Umbrella 提供的其 DNS 解析前一百万站点的白名单         |
| [Critical Stack Intel](https://intel.criticalstack.com/)     | Critical Stack 提供的免费威胁情报解析与聚合工具，可以应用到生产系统中。也可以指定你信任的情报来源或能提取情报的来源 |
| [C1fApp](https://www.c1fapp.com/)                            | C1fApp 是一个威胁情报订阅聚合应用，提供开源订阅与私有订阅。带有统计面板、用来搜索几年内数据的开放 API |
| [Cyber Cure free intelligience feeds](https://www.cybercure.ai/) | CyberCure 提供的免费网络威胁情报源，其中包括当前正在互联网上受到感染和攻击的 IP 地址列表。恶意软件使用的 URL 列表以及当前正在传播的已知恶意软件的文件哈希值。CyberCure 使用传感器以低误报收集情报，细节请看[文档](https://docs.cybercure.ai/) |
| [Cyber Threat Exchange](https://www.cyberthreatexchange.com/) | Threat Exchange 是一个购买、出售与共享网络威胁情报的在线市场平台 |
| [DataPlane.org](http://DataPlane.org)                        | [DataPlane.org](http://DataPlane.org) 是社区驱动的互联网数据、订阅和测量资源的提供方。免费提供可靠与值得信赖的服务 |
| [DigitalSide Threat-Intel](https://osint.digitalside.it/)    | Cointains 开源网络威胁情报指标集合，基于恶意软件分析的 URL、IP 和域名。该项目的目的是开发和测试寻找、分析、收集与共享相关 IOC 指标的新方法，以便 SOC/CSIRT/CERT/个人尽可能地方便。报告以三种方式共享：[ STIX2 ](https://osint.digitalside.it/Threat-Intel/stix2/)，[ CSV ](https://osint.digitalside.it/Threat-Intel/csv/)和[ MISP Feed ](https://osint.digitalside.it/Threat-Intel/digitalside-misp-feed/)。报告也发布在[GitHub](https://github.com/davidonzo/Threat-Intel/)中 |
| [Disposable Email Domains](https://github.com/martenson/disposable-email-domains) | 常用于垃圾邮件/滥用服务的匿名或一次性电子邮件域名的集合      |
| [DNSTrails](https://dnstrails.com/)                          | 提供当前和历史 DNS 信息、WHOIS 信息，子域名信息，还提供了一个[ IP 与域名情报的 API](https://securitytrails.com/) |
| [DomainStream](https://www.assetwatch.io/domainstream/)      | 来自每日扫描的各种证书透明度日志和 Passive DNS 数据的实时域名订阅，可以基于此查找互联网中感兴趣的新的子域名，或者查找潜在的网络钓鱼域名 |
| [Emerging Threats Firewall Rules](https://rules.emergingthreats.net/fwrules/) | 不同类型防火墙的规则集，包括 iptables、PF 和 PIX             |
| [Emerging Threats IDS Rules](https://rules.emergingthreats.net/blockrules/) | 用于报警或拦截的 Snort 和 Suricata 规则集                    |
| [ExoneraTor](https://exonerator.torproject.org/)             | ExoneraTor 提供 Tor 网络中一部分 IP 地址的数据库，可以响应给定的 IP 地址在给定的时间是否作为 Tor 节点运行过 |
| [Exploitalert](http://www.exploitalert.com/)                 | 最新的 exploits 列表                                         |
| [FastIntercept](https://intercept.sh/threatlists/)           | Intercept Security 依托其在全球的蜜网提供免费的 IP 信誉列表  |
| [ZeuS Tracker](https://feodotracker.abuse.ch/)               | Feodo Tracker [abuse.ch](http://abuse.ch) 跟踪 Feodo 木马    |
| [FireHOL IP Lists](https://iplists.firehol.org/)             | 超过 400 个公开可用的 IP 订阅，可以用来分析其演化、地理位置、时长、保留策略、重叠，这个网站侧重于网络犯罪（攻击、滥用、恶意软件） |
| [FraudGuard](https://fraudguard.io/)                         | FraudGuard 提供了一个验证不断收集、分析实时网络流量的工具的服务 |
| [Grey Noise](http://greynoise.io/)                           | Grey Noise 是一个收集、分析互联网范围内扫描器的系统，收集良性扫描器（如 [Shodan.io](http://Shodan.io)）以及恶意扫描（如 SSH 和远程登录蠕虫）的数据 |
| [Hail a TAXII](http://hailataxii.com/)                       | Hail a [TAXII.com](http://TAXII.com) 是一个 STIX 格式的开源网络威胁情报库，包括多种不同的格式，例如 Emerging Threats rules 与 PhishTank |
| [HoneyDB](https://riskdiscovery.com/honeydb/)                | HoneyDB 提供蜜罐活动的实时数据，这些数据来自在互联网中部署的 [HoneyPy](https://github.com/foospidy/HoneyPy) 蜜罐。此外，HoneyDB 还提供对所收集的蜜罐活动的 API 访问，其中还包括各种来自蜜罐相关的 Twitter 推送的聚合 |
| [Icewater](https://github.com/SupportIntelligence/Icewater)  | 由 http://icewater.io 提供的 12805 条免费的 Yara 规则        |
| [Infosec - CERT-PA](https://infosec.cert-pa.it/)             | 恶意软件样本的[收集和分析](https://infosec.cert-pa.it/analyze/submission.html)、[黑名单服务、](https://infosec.cert-pa.it/analyze/statistics.html)[漏洞数据库](https://infosec.cert-pa.it/cve.html)等。创建并管理自定义的[CERT-PA](https://www.cert-pa.it/) |
| [Infosec - CERT-PA](https://infosec.cert-pa.it/)             | 恶意软件样本的[收集与分析](https://infosec.cert-pa.it/analyze/submission.html)、[黑名单](https://infosec.cert-pa.it/analyze/statistics.html)[漏洞数据库](https://infosec.cert-pa.it/cve.html)等其他服务。由[CERT-PA](https://www.cert-pa.it/)创建并管理 |
| [I-Blocklist](https://www.iblocklist.com/lists)              | I-Blocklist 维护包括 IP 地址在内的多种类型的列表，主要有国家、ISP 和组织。其他列表包括 Web 攻击、Tor、间谍软件、代理，许多都可以免费使用，并且有多种格式 |
| [IPsum](https://raw.githubusercontent.com/stamparm/ipsum/master/ipsum.txt) | IPsum 是一个威胁情报源，基于 30 多个不同的、公开的可疑或恶意的 IP 地址列表。 每天自动检索并解析所有列表，并将最终结果推送到此存储库。列表由 IP 地址和出现的总数组成。 由[ Miroslav Stampar ](https://twitter.com/stamparm)创建并管理 |
| [Majestic Million](https://majestic.com/reports/majestic-million) | 由 Majestic 为前一百万的网站中排出可能的白名单，按照引用子网的数量排序。更多关于排名的信息可以在 [博客](https://blog.majestic.com/development/majestic-million-csv-daily/)中找到 |
| [Malc0de DNS Sinkhole](http://malc0de.com/bl/)               | 由 Malc0de 每天更新的文件，包含过去三十天内已经识别出分发恶意软件的域名 |
| [Maldatabase](https://maldatabase.com/)                      | Maldatabase 旨在帮助恶意软件数据科学与威胁情报订阅。提供的数据包含样本通信的域名、执行的进程列表与释放的文件等其他信息。 这些源可以帮助您改进监控与安全工具。安全研究人员与学生都可以免费获得服务。 |
| [MalShare.com](http://MalShare.com)                          | MalShare 项目为研究人员提供一个公开的样本库。普通用户每天可进行2000个样本的拉取。 |
| [Maltiverse](https://www.maltiverse.com/)                    | Maltiverse 项目是一个庞大而丰富的 IoC 数据库，可以进行复杂的查询和聚合以调查恶意软件的活动及其基础设施。也提供了一个很棒的 IoC 批量查询服务 |
| [Malware Domain List](https://www.malwaredomainlist.com/)    | 可搜索的恶意网站列表，反向查询出注册人信息，重点关注网络钓鱼、木马和漏洞利用工具包 |
| [MalwareDomains.com](http://MalwareDomains.com)              | DNS-BH 项目创建并维护了一个传播恶意软件以及间谍软件的域名列表，可以被用来检测 DNS 请求做预防检测 |
| [MetaDefender Cloud](https://www.opswat.com/developers/threat-intelligence-feed) | MetaDefender 云威胁情报源包含最新的恶意软件哈希签名，包括 MD5 和 SHA1，SHA256。是过去 24 MetaDefender 云发现的新的恶意哈希值。定语提供每日更新及恶意软件的检测和报告，提供可操作、及时的威胁情报 |
| [Netlab OpenData Project](http://data.netlab.360.com/)       | Netlab OpenData 于 2016.8.16 在 ISC 2016 上首次发布，提供多种数据源，包括 DGA、EK、MalCon、Mirai C2、Mirai-Scanner、Hajime-Scanner 和 DRDoS 反射器 |
| [NoThink!](http://www.nothink.org/honeypots.php)             | 来自 Matteo Cantoni 蜜罐提供的 SNMP、SSH、Telnet 黑名单 IP   |
| [NormShield Services](https://services.normshield.com/)      | NormShield Services 提供了数千个潜在网络钓鱼攻击的域名信息（包括 whois 信息），免费注册公共服务以进行持续监控 |
| [OpenPhish Feeds](https://openphish.com/phishing_feeds.html) | OpenPhish 接收来自多个流的 URL，然后使用其专有的网络钓鱼检测算法进行检测。有免费以及商业两个版本 |
| [PhishTank](https://www.phishtank.com/developer_info.php)    | PhishTank 提供了可疑钓鱼网站的 URL，它们的数据来自各个报告的人，它们也在外部订阅中获得数据，这是一项免费服务，但有时需要 API key |
| [Ransomware Tracker](https://ransomwaretracker.abuse.ch/)    | Ransomware Tracker 由 [abuse.ch](http://abuse.ch) 提供对与 Ransomware 有关的域名、IP、URL 状态进行跟踪与监视 |
| [REScure Threat Intel Feed](https://rescure.fruxlabs.com/)   | [RES]cure 是由 Fruxlabs Crack 团队运营的独立威胁情报项目，旨在增强对分布式系统底层架构的理解、威胁情报的性质以及如何有效地收集、存储、使用和分发威胁情报。 每六小时发布一次 |
| [Rutgers Blacklisted IPs](https://report.cs.rutgers.edu/mrtg/drop/dropstat.cgi?start=-86400) | 合并本地观测到的 IP 地址与 [badip.com](http://badip.com) 和 [blocklist.de](http://blocklist.de) 最新两小时的数据创建的暴力破解 SSH 的 IP 地址列表 |
| [SANS ICS Suspicious Domains](https://isc.sans.edu/suspicious_domains.html) | Suspicious Domains Threat 由 [SANS ICS](https://isc.sans.edu/suspicious_domains.html) 提供对恶意域名的跟踪，提供三个列表分为 [高](https://isc.sans.edu/feeds/suspiciousdomains_High.txt), [中](https://isc.sans.edu/feeds/suspiciousdomains_Medium.txt) or [低](https://isc.sans.edu/feeds/suspiciousdomains_Low.txt) 三个层级，高级名单的错报低，低级名单的错报高。还有一个域名的 [白名单](https://isc.sans.edu/feeds/suspiciousdomains_whitelist_approved.txt) 另外，也有黑名单 [IP blocklist](https://isc.sans.edu/block.txt) 由 [DShield](https://dshield.org/) 提供 |
| [signature-base](https://github.com/Neo23x0/signature-base)  | 在其他工具中使用的签名数据库                                 |
| [The Spamhaus project](https://www.spamhaus.org/)            | Spamhaus 项目包含包括垃圾邮件以及恶意软件活动在内的多种威胁情报 |
| [SSL Blacklist](https://sslbl.abuse.ch/)                     | SSL Blacklist (SSLBL) 是由 [abuse.ch](http://abuse.ch) 维护的项目，旨在提供一个与恶意软件、僵尸网络活动有关的不良 SSL 证书列表。SSLBL 提供恶意 SSL 证书的 SHA1 指纹，并且提供多种黑名单 |
| [Statvoo Top 1 Million Sites](https://statvoo.com/dl/top-1million-sites.csv.zip) | Statvoo 排名的前一百万站点，可作为白名单                     |
| [Strongarm, by Percipient Networks](https://strongarm.io/)   | Strongarm 是一个 DNS 黑洞，旨在提供阻止恶意软件 C&C 的 IOC 信息，其聚合了许多免费的订阅源，并与商业订阅集成，利用 Percipient 的 IOC 订阅，利用 DNS 解析与 API 来保护你的网络与企业。Strongarm 对个人使用是免费的 |
| [Talos Aspis](http://www.talosintelligence.com/aspis/)       | Aspis 是一个 Talos 和主机提供商的封闭合作项目，用来识别与阻止主要威胁。Talos 与主机提供商共享其专业知识、资源与能力，包括网络与系统取证、逆向工程与威胁情报 |
| [Technical Blogs and Reports, by ThreatConnect](https://threatconnect.com/blog/ingest-technical-blogs-reports/) | 在九十多个开源博客中提取 IOCs ([Indicators of Compromise](https://en.wikipedia.org/wiki/Indicator_of_compromise))，博客内容使用 markdown 排版 |
| [Threatglass](http://www.threatglass.com/)                   | 一个用于共享、浏览、与分析基于网络的恶意软件的在线工具，Threatglass 允许用户通过浏览器来查看恶意软件在感染阶段的屏幕截图以及网络特性的分析（包括主机关系与数据包捕获） |
| [ThreatMiner](https://www.threatminer.org/)                  | ThreatMiner 为分析师从数据收集到执行分析提供了一个门户，ThreatMiner 关注的重点不仅仅是关于 IOC，还为分析人员提供有关 IOC 的上下文信息 |
| [WSTNPHX Malware Email Addresses](https://raw.githubusercontent.com/WSTNPHX/scripts-n-tools/master/malware-email-addresses.txt) | 由 VVestron Phoronix (WSTNPHX)收集的恶意软件使用的电子邮件地址 |
| [UnderAttack.today](https://portal.underattack.today/)       | UnderAttack 是一个免费的情报平台，它共享有关可疑事件和攻击的 IP 地址与其他信息。可在[此处](https://portal.underattack.today/)免费注册 |
| [URLhaus](https://urlhaus.abuse.ch/)                         | URLhaus 是一个由 [abuse.ch](http://abuse.ch) 发起的旨在共享用于恶意软件传播的 URL 的项目 |
| [VirusShare](https://virusshare.com/)                        | [VirusShare.com](http://VirusShare.com) 是一个为安全研究员、事件响应人员、取证分析人员提供恶意样本的仓库，其中也含有很多恶意样本的代码，网站只能通过邀请得到访问授权 |
| [Yara-Rules](https://github.com/Yara-Rules/rules)            | 收集不同 Yara 规则的开源库，经过分类并尽量保持时效性         |
| [ZeuS Tracker](https://zeustracker.abuse.ch/)                | ZeuS Tracker 由 [abuse.ch](http://abuse.ch) 提供对 ZeuS 的 C&C 主机的跟踪，提供给你域名与主机的黑名单 |
| [1st Dual Stack Threat Feed by MrLooquer](https://iocfeed.mrlooquer.com/) | Mrlooquer 创建了第一个同时支持 IPv4 与 IPv6 的威胁源。由于 IPv6 协议已经开始成为恶意软件和欺诈通信的一部分，因此有必要检测和缓解两种协议（IPv4 与 IPv6） |




## 格式

用于分享的威胁情报标准化格式：

| 格式名称                                                     | 介绍                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [CAPEC](https://capec.mitre.org/)                            | Common Attack Pattern Enumeration and Classification (CAPEC) 是一个综合性的术语大全以及对已知攻击的分类，可以被分析、开发、测试以及教育工作者使用，推动社会的重视并且增加网络防御能力 |
| [CybOX](https://cyboxproject.github.io/)                     | Cyber Observable eXpression (CybOX) 提供了一种用于企业网络安全运营中可观察性的信息结构，用来提高部署的工具和流程的效率、一致性和互通性，通过详细地自动化共享、映射、检测以及启发式分析来挖掘信息的潜在价值 |
| [IODEF (RFC5070)](https://tools.ietf.org/html/rfc5070)       | Incident Object Description Exchange Format (IODEF) 定义了为 CSIRTs 交换有关计算机安全事件信息的框架的数据表示方法 |
| [IDMEF (RFC4765)](https://tools.ietf.org/html/rfc4765)       | *Experimental* - Intrusion Detection Message Exchange Format (IDMEF) 的目的是定义共享入侵检测和响应系统有用的信息包括可能需要进行交互的管理系统的数据格式和交换过程 |
| [MAEC](https://maecproject.github.io/)                       | Malware Attribute Enumeration and Characterization (MAEC) 项目旨在创建、提供一种根据恶意软件的行为、工具、攻击模式等可用于共享的结构化信息的标准 |
| [OpenC2](https://www.oasis-open.org/committees/tc_home.php?wg_abbrev=openc2) | OASIS Open Command and Control (OpenC2) Technical Committee. 在创建技术委员会和规范之前，OpenC2 论坛是由国家安全局（NSA）推动的一个网络安全利益相关者社区。OpenC2 技术委员会负责起草文件、规范、词典或其他内容，以标准化的方式满足网络安全指挥和控制的需求 |
| [STIX 2.0](https://oasis-open.github.io/cti-documentation/)  | Structured Threat Information eXpression (STIX) 定义了一组网络威胁信息的标准， STIX 旨在完整传达全部潜在地网络威胁信息，力求灵活、可扩展以及自动化。STIX 不仅与工具无关，还提供了所谓的 测试机制，为嵌入特定工具元素提供手段，包括 OpenIOC, Yara and Snort |
| [TAXII](https://taxiiproject.github.io/)                     | Trusted Automated eXchange of Indicator Information (TAXII) 标准定义了一系列服务与信息交换的标准，执行实施后可以在组织和产品/服务的边界提供可操作的网络威胁信息，它定义了概念、协议、用于检测、预防和减轻网络威胁的信息交换 |
| [VERIS](http://veriscommunity.net/index.html)                | Vocabulary for Event Recording and Incident Sharing (VERIS) 是一组指标，旨在提供一种以结构化和可重复的方式描述安全事件的通用语言。VERIS 是对安全行业缺乏高质量信息挑战的回应。除了提供架构格式外，VERIS 也 从 Verizon 数据泄漏调查报告库 ([DBIR](http://www.verizonenterprise.com/verizon-insights-lab/dbir/))社区收集报告和 [VCDB.org](http://VCDB.org) 的在线数据库 |



## 框架与平台

收集、分析、构建、分享威胁情报的框架、平台与服务。

| 平台名称                                                     | 介绍                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [AbuseHelper](https://github.com/abusesa/abusehelper)        | AbuseHelper 是一个用来接收与重分配威胁情报订阅的开源框架     |
| [AbuseIO](https://abuse.io/)                                 | 用于接收、处理、关联、通知用户有关滥用的信息                 |
| [AIS](https://www.dhs.gov/ais)                               | Department of Homeland Security’s (DHS) 设计的用于联邦政府和私营部门之间共享威胁指标的标准，威胁指标包括恶意 IP 地址或网络钓鱼邮件发送人等信息 |
| [Barncat](https://www.fidelissecurity.com/resources/fidelis-barncat) | Fidelis Cybersecurity 注册后提供对 Barncat 免费的访问权限，该平台旨在为 CERT、研究人员、政府、ISP 以及大型组织提供，数据库保存着攻击者的各种信息 |
| [Bearded Avenger](https://github.com/csirtgadgets/bearded-avenger) | CIF 的接替者，最快处理威胁情报的方式                         |
| [Blueliv Threat Exchange Network](https://community.blueliv.com/) | 允许社区的参与者共享威胁情报信息                             |
| [Cortex](https://github.com/TheHive-Project/Cortex)          | Cortex 允许对如 IP 地址、电子邮件地址、URL、域名、文件或哈希，在 bulk 模式下使用 Web 界面逐个分析。前端接口可以充当许多分析器的前端，从而消除了在分析过程中将其整合在一起的需求。分析人员还可以使用 Cortex REST API 进行自动分析 |
| [CRITS](https://crits.github.io/)                            | CRITS 是一个为分析人员提供恶意软件和威胁情报协同研究的平台，可以作为中心情报数据库的一部分，但也可以独立成库 |
| [CIF](http://csirtgadgets.org/collective-intelligence-framework) | Collective Intelligence Framework (CIF) 允许你将已知的多源恶意威胁信息联结起来，可以用于 IR、检测与缓解，代码在 [GitHub](https://github.com/csirtgadgets/massive-octo-spice) 上可用 |
| [IntelMQ](https://www.enisa.europa.eu/topics/csirt-cert-services/community-projects/incident-handling-automation) | IntelMQ 是 CERTs 的一个为了收集和处理安全订阅数据的解决方案，其最初由 IHAP 发起，现在由社区驱动。目标是给事件响应者提供一个简单的方法来收集和处理威胁情报，从而改善 CERT 的事件处理过程 |
| [IntelStitch](https://www.intelstitch.com/)                  | IntelStitch 简化了网络威胁情报的聚合、处理与共享。 IntelStitch 可以从传统威胁源以及更多动态源（包括 Pastebin、Twitter 和论坛）收集与处理情报，以便可以更好地与下游安全工具集成。 |
| [Interflow](https://technet.microsoft.com/en-us/security/dn750892) | Interflow 是由 Microsoft 为网络安全分析人员创建的安全和威胁信息交换平台，它使用分布式架构，可以在社区内外构建更强大的生态系统来分享安全与威胁信息。Interflow 提供多种配置选项，允许用户决定要组建那些社区，整合那些数据订阅以及与谁共享。Interflow 目前仍然是 private preview 状态 |
| [Malstrom](https://github.com/byt3smith/malstrom)            | Malstrom 的目的是来跟踪与取证的神器，还包括 YARA 的规则库与一些调查的笔记。注：GitHub 仓库无人维护，没有新的 PR 被接受 |
| [ManaTI](https://github.com/stratosphereips/Manati)          | ManaTI 期望通过使用机器学习技术帮助威胁分析人员自动寻找新的关系与推论 |
| [MANTIS](https://django-mantis.readthedocs.io/en/latest/)    | Model-based Analysis of Threat Intelligence Sources (MANTIS) 网络威胁情报管理框架支持各种标准语言（如 STIX 和 CybOX）来进行网络威胁情报的管理 |
| [Megatron](https://github.com/cert-se/megatron-java)         | Megatron 是由 CERT-SE 实施的工具，用于收集和分析恶意 IP，带有数据统计、转换、分析以及事件响应的功能 |
| [MineMeld](https://github.com/PaloAltoNetworks/minemeld/wiki) | Palo Alto Networks 创建的一个可扩展的威胁情报处理框架，它可以有效管理 IOC 列表，并将其转换/汇总到第三方基础架构中使用 |
| [MISP](https://www.misp-project.org/)                        | Malware Information Sharing Platform (MISP) 是一个收集、存储、分发和分享网络安全指标和恶意软件分析信息的开源软件解决方案 |
| [n6](https://github.com/CERT-Polska/n6)                      | n6 (Network Security Incident eXchange) 是一个大规模收集、管理、分发安全信息的系统，通过简单的 REST API 和 Web 界面即可实现分发，授权用户可以使用它来接收各种类型的数据，特别是有关其网络中威胁的信息，其由 [CERT Polska](https://www.cert.pl/en/) 开发 |
| [OpenCTI](https://www.opencti.io/en/)                        | OpenCTI 是一个开放式网络威胁情报平台，允许组织管理其网络威胁情报知识。 其目标是构建、存储、组织和可视化有关网络威胁的技术和非技术信息。数据围绕 STIX2 标准的知识模式构建。OpenCTI 可以与其他工具和平台集成，包括 MISP、TheHive 和 MITRE ATT&CK |
| [OpenIOC](http://www.openioc.org/)                           | OpenIOC 是一个开放的共享威胁情报的框架，它的目的是用计读的格式互通内部与外部的威胁情报信息 |
| [OpenTAXII](https://github.com/EclecticIQ/OpenTAXII)         | OpenTAXII 是 TAXII 的一个 Python 实现，提供了一系列丰富的功能与友好的 Python API |
| [OSTrICa](https://github.com/Ptr32Void/OSTrICa)              | 一个开源的插件化框架来对威胁情报的收集与可视化               |
| [OTX - Open Threat Exchange](https://otx.alienvault.com/)    | AlienVault Open Threat Exchange (OTX) 为威胁研究人员和安全专业人士提供全球开放访问，其提供社区生成的威胁数据来实现协作研究，并自动更新汇聚多来源的威胁数据来完善安全基础设施建设 |
| [Open Threat Partner eXchange](https://github.com/Lookingglass/opentpx/) | Open Threat Partner eXchange (OpenTPX) 由开源格式和用于机器的威胁情报和网络安全工具组成，它是一种基于 JSON 的格式，允许在互联的系统间共享情报 |
| [PassiveTotal](https://www.passivetotal.org/)                | RiskIQ 提供的 PassiveTotal 平台是一个威胁分析平台，可以为威胁分析人员提供尽可能多的数据，来阻止曾经发生过的攻击，提供了不同类型的解决方案和与其他系统的整合 |
| [Pulsedive](https://pulsedive.com/)                          | Pulsedive 是一个免费的社区威胁情报平台，聚合开源资源，丰富 IOC，并通过风险评分算法过滤 IOC 以提高数据质量。它允许用户提交、搜索、关联与更新 IOC，列出 IOC 的“风险因素”，并提供威胁和威胁活动的高级视图 |
| [Recorded Future](https://www.recordedfuture.com/)           | Recorded Future 是一个优秀的 SaaS 产品，可以将不同类型的威胁情报整合到单一的解决方案中，其使用自然语言处理（NLP）和机器学习来实时提供威胁情报，这些都让 Recorded Future 成为 IT 安全团队的热门选择 |
| [Scumblr](https://github.com/Netflix/Scumblr)                | Scumblr 是一个可以执行数据源定期同步的 Web 应用程序，并对可识别的结果执行分析（如静态分析、动态检测和元数据收集）。Scumblr 可以帮助你通过智能自动化框架简化安全分析过程，以帮助你更快地识别、跟踪和解决安全问题 |
| [Soltra Edge](https://soltra.com/)                           | Soltra Edge 的免费版本，支持扩展社区防御模型。扩展性好，操作性交互度很高，基于开箱即用的行业标准，包括 STIX 和 TAXII |
| [STAXX (Anomali)](https://www.anomali.com/product/staxx)     | Anomali STAXX™ 提供了一种免费、简便地方式来处理任何 STIX/TAXII 类的订阅信息。只需要下载 STAXX 客户端，配置好数据源就可以由它完成后续的工作 |
| [stoQ](http://stoq.punchcyber.com/)                          | stoQ 是一个允许网络分析师来组织、自动化那些数据驱动的任务，，它具有许多可用于其他系统的插件，一种用例是从文档中提取 IOC，例如 [博客](https://stoq-framework.blogspot.nl/2016/04/operationalizing-indicators.html), 也可以用于解帧和解码以及 YARA 的自动扫描 |
| [TARDIS](https://github.com/tripwire/tardis)                 | Threat Analysis, Reconnaissance, and Data Intelligence System (TARDIS) 是一个使用攻击签名执行历史搜索的开源框架 |
| [ThreatConnect](https://www.threatconnect.com/)              | ThreatConnect 是一个分析、编排威胁情报的平台。它旨在帮助收集数据、产生情报、与他人分享数据并采取行动 |
| [ThreatCrowd](https://www.threatcrowd.org/)                  | ThreatCrowd 是一个发现和研究有关网络威胁的系统               |
| [ThreatPipes](https://www.threatpipes.com/)                  | ThreatPipes 连接威胁情报源与安全工具，以便它们以强大的新方式协同工作。 ThreatPipes 简化了网络威胁情报的聚合、处理与共享的流程。 |
| [ThreatExchange](https://developers.facebook.com/docs/threat-exchange/) | Facebook 创建了 ThreatExchange 可以方便的使用结构化、易用的 API 来共享威胁数据，该 API 提供隐私控制，以便与所需的组织进行共享，该项目仍然处于测试阶段，参考代码可以在 [GitHub](https://github.com/facebook/ThreatExchange) 中找到 |
| [VirusBay](https://beta.virusbay.io/)                        | VirusBay 是一个基于 Web 的协作平台，可将 SOC 与恶意软件研究人员联系起来 |
| [Threat_Note](https://github.com/defpoint/threat_Note)       | DPS 的轻量级调查笔记本                                       |
| [XFE - X-Force Exchange](https://exchange.xforce.ibmcloud.com/) | IBM XFE 开发的 X-Force Exhange (XFE) 是一款免费的 SaaS 产品，可用于搜索威胁情报信息，收集你的数据并与 XFE 社区的其他成员分享你的看法 |
| [Yeti](https://yeti-platform.github.io/)                     | 开放、分布式、机器与分析友好的威胁情报存储库，由应急响应人员制作 |




## 工具

用户创建、解析、编辑威胁情报的各种工具，大多数基于 IOC。

| 工具名称                                                     | 介绍                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [ActorTrackr](http://actortrackr.com/)                       | ActorTrackr 是一个用来存储/搜索/链接事件相关数据的开源 Web 应用程序。主要来源是用户以及各种公共资料库，也有一些来自 [GitHub](https://github.com/dougiep16/actortrackr) |
| [AIEngine](https://bitbucket.org/camp0/aiengine)             | AIEngine 是下一代交互式支持 Python/Ruby/Java/Lua 编程的包检测引擎，无需任何人工干预，具有 NIDS 的功能、DNS 域名分类、网络流量收集、网络取证等许多功能，源码在[Bitbucket](https://bitbucket.org/camp0/aiengine) |
| [Automater](https://github.com/1aN0rmus/TekDefense-Automater) | Automater 是一个集合 URL/Domain、IP Address 和 Md5 的 OSINT 工具，旨在让入侵分析变得更轻松 |
| [BotScout](https://botscout.com/)                            | BotScout 有助于防止论坛注册自动化 Web 脚本、污染数据库、传播垃圾邮件、滥用网站上的表单 |
| [bro-intel-generator](https://github.com/exp0se/bro-intel-generator) | 从 PDF 或 HTML 报告中提取信息生成 Bro intel 文件的脚本       |
| [cabby](https://github.com/EclecticIQ/cabby)                 | 一个用来和 TAXII 服务器进行交互的简单 Python 库              |
| [cacador](https://github.com/sroberts/cacador)               | Cacador 是一个使用 Go 编写的工具，用来从一段文本中提取常见的威胁情报指标 |
| [Combine](https://github.com/mlsecproject/combine)           | Combine 聚合了多个公开源的威胁情报                           |
| [CrowdFMS](https://github.com/CrowdStrike/CrowdFMS)          | CrowdFMS 是一个利用私有 API 来自动收集与处理来自 VirusTotal 的样本的框架，该框架会自动下载最近的样本，从而触发 YARA 提醒订阅的警报 |
| [CyBot](https://github.com/CylanceSPEAR/CyBot)               | CyBot 是一个威胁情报聊天机器人，可以执行自定义模块提供的多类型的查找 |
| [Cuckoo Sandbox](https://github.com/cuckoosandbox/cuckoo)    | Cuckoo 沙盒是自动化动态恶意软件分析系统。它是最知名的开源恶意软件分析沙盒，由研究人员、CERT/SOC 团队和全球的威胁情报团队部署。对于许多组织来说 Cuckoo 沙盒可以发现第一个潜在的恶意软件样本 |
| [Fenrir](https://github.com/Neo23x0/Fenrir)                  | 简单的 Bash IOC 扫描器                                       |
| [FireHOL IP Aggregator](https://github.com/spacepatcher/FireHOL-IP-Aggregator) | 保留 FireHOL [黑名单 IP 地址数据集](https://github.com/firehol/blocklist-ipsets)，包括历史更改，针对请求开发的基于 HTTP 的 API 服务 |
| [Forager](https://github.com/byt3smith/Forager)              | 多线程威胁情报收集脚本                                       |
| [GoatRider](https://github.com/BinaryDefense/goatrider)      | GoatRider 会动态拉取 Artillery Threat Intelligence 订阅数据、TOR、AlienVaults OTX 以及 Alexa top 1 million websites 与给定的主机名或 IP 进行比较 |
| [Google APT Search Engine](https://cse.google.com/cse/publicurl?cx=003248445720253387346:turlh5vi4xc) | APT 组织与恶意软件搜索引擎，用于此 Google 自定义搜索的来源列表在 [GitHub 中](https://gist.github.com/Neo23x0/c4f40629342769ad0a8f3980942e21d3) |
| [GOSINT](https://github.com/ciscocsirt/gosint)               | The GOSINT 框架是一个免费项目，用于收集、处理和导出高质量的 IOC 指标 |
| [hashdd](https://hashdd.com/)                                | 在 crytographic 上使用哈希值查找相关信息的工具               |
| [Harbinger Threat Intelligence](https://github.com/exp0se/harbinger) | 从单一接口查询多个在线威胁情报聚合服务的 Python 脚本         |
| [Hippocampe](https://github.com/TheHive-Project/Hippocampe)  | Hippocampe 是一个从互联网中聚合威胁订阅的 Elasticsearch 集群。它拥有一个 REST API，基于一个可以 fetch 对应订阅的 URL 的 Python 脚本，还可以进行解析与索引 |
| [Hiryu](https://github.com/S03D4-164/Hiryu)                  | 一个用来组织 APT 组织信息的工具，并提供 IOC 之间关系的可视化展示 |
| [IOC Editor](https://www.fireeye.com/services/freeware/ioc-editor.html) | 一个免费的 Indicators of Compromise (IOCs) 编辑器            |
| [IOC Finder](https://github.com/fhightower/ioc-finder)       | 用于查找文本中 IOC 指标的 Python 库。使用语法而不是正则表达式来提高可理解性。截至 2019 年 2 月，可以解析 18 种类型的 IOC 指标 |
| [ioc_parser](https://github.com/armbues/ioc_parser)          | 从 PDF 格式的安全报告中提取 IOC 的工具                       |
| [ioc_writer](https://github.com/mandiant/ioc_writer)         | 一个可以创建/编辑基本 OpenIOC 对象的 Python 库               |
| [iocextract](https://github.com/InQuest/python-iocextract)   | 从文本中提取 URL、IP 地址、MD5/SHA 哈希、电子邮件地址与 YARA 规则。在输出中包含一些编码或处理后的 IOC 指标，可选择将其解码/反处理 |
| [IOCextractor](https://github.com/stephenbrannon/IOCextractor) | IOC (Indicator of Compromise) Extractor 是一个帮助从文本文件中提取 IOC 的程序，旨在加速从非结构化数据/半结构化数据中提取结构化数据的过程 |
| [ibmxforceex.checker.py](https://github.com/johestephan/ibmxforceex.checker.py) | IBM X-Force Exchange 的 Python 客户端                        |
| [jager](https://github.com/sroberts/jager)                   | Jager 是一个从各种数据源（现在已支持 PDF，很快支持纯文本，最终会支持网页）提取有用的 IOC 并将其变成易于操作的 JSON 格式的工具 |
| [KLara](https://github.com/KasperskyLab/klara)               | KLara 是一个使用 Python 编写的分布式系统，可以扫描一个或多个 Yara 规则、通过邮件获取通知、通过 Web 界面查看扫描结果 |
| [libtaxii](https://github.com/TAXIIProject/libtaxii)         | 可以调用 TAXII 服务处理 TAXII 信息的 Python 库               |
| [Loki](https://github.com/Neo23x0/Loki)                      | 简单的 IOC 与事件响应扫描器                                  |
| [LookUp](https://bitbucket.org/ssanthosh243/ip-lookup-docker) | LookUp 是一个有关 IP 地址的各种威胁信息的聚合页面，可以轻松的被集成到工具的上下文菜单中，如 SIEM 或其他调查工具 |
| [Machinae](https://github.com/HurricaneLabs/machinae)        | Machinae 是一个用于从公开站点/订阅源收集各种与安全相关数据的工具，包括 IP 地址、域名、URL、电子邮件地址、文件哈希值与 SSL 指纹 |
| [MalPipe](https://github.com/silascutler/MalPipe)            | Amodular 是一个针对恶意软件与 IOC 指标收集与处理的框架。旨在从多个不同的源中提取恶意软件、域名、URL 和 IP 地址，汇总收集到的数据并导出结果 |
| [MISP Workbench](https://github.com/MISP/misp-workbench)     | 将 MISP 的 MySQL 数据库导出，使之可以在外部应用              |
| [MISP-Taxii-Server](https://github.com/MISP/MISP-Taxii-Server) | 一组用于使用 EclecticIQ 的 OpenTAXII 实例的配置文件，当数据送达 TAXII 服务器的收件箱时带有回调 |
| [nyx](https://github.com/paulpc/nyx)                         | 该项目的目标是促进威胁情报分发到防御系统中，并增强从开源和商业工具中获得的价值 |
| [OneMillion](https://github.com/fhightower/onemillion)       | 用于确定域名是否在 Alexa 或 Cisco 的 TOP 100 万域名列表中的 Python 库 |
| [openioc-to-stix](https://github.com/STIXProject/openioc-to-stix) | 转换 STIX XML 为 OpenIOC XML                                 |
| [Omnibus](https://github.com/InQuest/omnibus)                | Omnibus 是一个交互式命令行程序，用于收集、管理 IOC 指标，使用公共 OSINT 数据进行补充，并提供存储与访问这些指标的简单方法 |
| [OSTIP](https://github.com/kx499/ostip/wiki)                 | 自制的威胁数据平台                                           |
| [poortego](https://github.com/mgeide/poortego)               | 用于处理/链接开源威胁情报的项目。最初用 ruby 开发，新版本用 python 重写了 |
| [PyIOCe](https://github.com/yahoo/PyIOCe)                    | PyIOCe 是一个使用 Python 编写的 IOC 编辑器                   |
| [QRadio](https://github.com/QTek/QRadio)                     | QRadio 是一个旨在巩固网络威胁情报源的工具/框架，该项目试图建立一个强大的框架来审查提取得到的威胁情报数据 |
| [rastrea2r](https://github.com/aboutsecurity/rastrea2r)      | 收集与整理 Indicators of Compromise (IOC)                    |
| [Redline](https://www.fireeye.com/services/freeware/redline.html) | 主机调查工具，分析其可用于 ICO 分析的数据                    |
| [RITA](https://github.com/ocmdev/rita)                       | Real Intelligence Threat Analytics (RITA) 旨在帮助不同规模的企业在网络中搜索 IOC |
| [Softrace](https://github.com/spacepatcher/softrace)         | 轻量级国家软件参考库 RDS 存储                                |
| [SRA TAXII2 Server](https://github.com/SecurityRiskAdvisors/sra-taxii2-server) | 带有 MongoDB 后端的 Node JS 实现的完整 TAXII 2.0 服务器      |
| [stix-viz](https://github.com/STIXProject/stix-viz)          | STIX 可视化工具                                              |
| [TAXII Test Server](https://test.taxiistand.com/)            | 允许你通过连接给定的服务并执行 TAXII 给定的各种功能来测试你的 TAXII 环境 |
| [threataggregator](https://github.com/jpsenior/threataggregator) | ThreatAggregrator 聚合了许多在线的威胁情报源，支持输出到各种格式，包括 CEF、Snort 和 iptables 的规则 |
| [threatcrowd_api](https://github.com/jheise/threatcrowd_api) | 使用 ThreatCrowd API 的 Python 库                            |
| [threatcmd](https://github.com/jheise/threatcmd)             | ThreatCrowd 的命令行接口                                     |
| [Threatelligence](https://github.com/syphon1c/Threatelligence) | Threatelligence 是一个简单的威胁情报订阅收集器，使用 Elasticsearch、Kibana 和 Python 来自动收集自定义或开源的情报，自动跟踪数据更新，但是项目似乎以及放弃更新了 |
| [ThreatIngestor](https://github.com/InQuest/ThreatIngestor)  | 用于消费威胁情报的灵活的、配置驱动的、可扩展的框架。 ThreatIngestor 可以处理 Twitter、RSS 和其他来源，从中提取有意义的信息，如 C&C 的 IP、域名或 YARA 签名，并将该信息发送到其他系统进行分析 |
| [ThreatPinch Lookup](https://chrome.google.com/webstore/detail/threatpinch-lookup/ljdgplocfnmnofbhpkjclbefmjoikgke) | 一个用于在每个页面查找 IPv4、MD5、SHA2 以及 CVEs 的 Chrome 扩展程序 |
| [ThreatTracker](https://github.com/michael-yip/ThreatTracker) | 用于监控并生成一组由 Google 自定义搜索引擎得出的 IOC 数据集  |
| [threat_intel](https://github.com/Yelp/threat_intel)         | 多个威胁情报的 API 聚合在一个包中，其中包括 OpenDNS Investigate、VirusTotal 和 ShadowServer |
| [Threat-Intelligence-Hunter](https://github.com/abhinavbom/Threat-Intelligence-Hunter) | TIH 是一个可以帮助你在多个可公开提取的安全订阅源与知名 API 中提取 IOC 的智能工具，创建这个工具的初衷就是为了方便搜索、存储 IOC，以方便你创建自己的本地数据库 |
| [tiq-test](https://github.com/mlsecproject/tiq-test)         | Threat Intelligence Quotient (TIQ) 测试工具提供对威胁情报的可视化与统计分析 |
| [YETI](https://github.com/TAXIIProject/yeti)                 | YETI 是一个 TAXII 的概念验证，带有收件箱、轮询和 TAXII 的特定服务支持 |
| [sqhunter](https://github.com/0x4d31/sqhunter)               | 基于 osquery、Salt Open 和 Cymon API 的威胁狩猎。它可以查询 open 的网络套接字并根据威胁情报来源进行检查 |






## 研究、标准、书籍

威胁情报的各种材料，包括研究与白皮书。

| 资源名称                                                     | 介绍                                                         |
| ------------------------------------------------------------ | ------------------------------------------------------------ |
| [APT & Cyber Criminal Campaign Collection](https://github.com/gasgas4/APT_CyberCriminal_Campaign) | 广泛收集各种组织信息，来源多样                               |
| [APTnotes](https://github.com/kbandla/APTnotes)              | 关于 APT 的信息收集，通常包括战略、战术知识或建议            |
| [ATT&CK](https://attack.mitre.org/index.php/Main_Page)       | Adversarial Tactics, Techniques, and Common Knowledge (ATT&CK™) 是用于描述攻击者在企业内网可能采取行动的一个模型与框架。ATT&CK 对于 post-access 是一个持续进步的共同参考，其可以在网络入侵中意识到什么行动最可能发生。MITRE 正在积极致力于相关信息的构建，就像 CAPEC、STIX 和 MAEC |
| [Building Threat Hunting Strategies with the Diamond Model](http://www.activeresponse.org/building-threat-hunting-strategy-with-the-diamond-model/) | Sergio Caltagirone 的博客：如何利用钻石模型开发威胁情报战略  |
| [Cyber Analytics Repository by MITRE](https://car.mitre.org/wiki/Main_Page) | Cyber Analytics Repository (CAR) 是 MITRE 基于 ATT&CK™ 开发的知识库 |
| [Definitive Guide to Cyber Threat Intelligence](https://cryptome.org/2015/09/cti-guide.pdf) | 描述了网络威胁情报的要素，讨论了如何收集、分析和使用这些数据来进一步应用在战略、运营层面来提高网络安全，以及如何帮助你更早地阻断攻击，提高自己的防御能力，更加有效的讨论网络安全隐患，以典型的 *Dummies* 风格进行管理 |
| [The Detection Maturity Level (DML)](https://ryanstillions.blogspot.nl/2014/04/the-dml-model_21.html) | DML 模型是一个能力成熟度模型，引入成熟度来检测网络攻击。专为情报驱动的威胁检测和应急响应而设计，并强调一个成熟的应用流程。成熟度并不是通过获得相关情报的能力还衡量的，而是将能力有效地应用到检测和响应功能上 |
| [The Diamond Model of Intrusion Analysis](https://www.threatconnect.com/wp-content/uploads/ThreatConnect-The-Diamond-Model-of-Intrusion-Analysis.pdf) | 本文介绍了钻石模型，一种支持和改善入侵分析认知的框架和分析工具。Supporint 为入侵分析中增加了可检测性、可测试性和可重复性来获得更高的有效性，击败对手的效率和准确度是其主要贡献之一 |
| [F3EAD](http://www.dtic.mil/dtic/tr/fulltext/u2/a547092.pdf) | F3EAD 是一个将行动与情报相结合的军事方法                     |
| [Guide to Cyber Threat Information Sharing by NIST](https://dx.doi.org/10.6028/NIST.SP.800-150) | Guide to Cyber Threat Information Sharing (NIST Special Publication 800-150) 协助组织建立计算机安全事件响应能力，利用合作伙伴的知识、经验和能力，积极分享威胁情报并持续协调。该指南提供协调事件处理的指导方针，包括生成和使用数据，参与信息共享社区 |
| [Intelligence Preparation of the Battlefield/Battlespace](https://blue.y1ng.org/0x3_threat_intelligence/docs/Intelligence Preparation for the Battlefield-Battlespace.pdf) | 探讨了 intelligence preparation of the battlespace (IPB) 战场的情报准备，讲述了 IPB 作为军事决策与规划的一个重要组成部分是如何支持决策以及整合流程 |
| [Intelligence-Driven Computer Network Defense Informed by Analysis of Adversary Campaigns and Intrusion Kill Chains](http://www.lockheedmartin.com/content/dam/lockheed/data/corporate/documents/LM-White-Paper-Intel-Driven-Defense.pdf) | 此文提出的入侵杀伤链为入侵分析、指标提取与执行防御行动提供了一种结构化的方法 |
| [ISAO Standards Organization](https://www.isao.org/)         | ISAO Standards Organization 一个非政府组织，成立于2015年10月1日.。其任务是通过确定与网络安全风险、事件和最佳实践有关的有效信息共享标准与准则，来改善国家的网络安全态势 |
| [Joint Publication 2-0: Joint Intelligence](http://www.dtic.mil/doctrine/new_pubs/jp2_0.pdf) | 美军的这本出版物以情报学说为核心，为运作、计划情报融入一个凝聚力的团队奠定了基础，所提出的概念也适用于网络威胁情报 |
| [Microsoft Research Paper](https://download.microsoft.com/download/8/0/1/801358EC-2A0A-4675-A2E7-96C2E7B93E73/Framework_for_Cybersecurity_Info_Sharing.pdf) | 网络安全信息共享与风险降低的框架，微软高级概述文档           |
| [MISP Core Format (draft)](https://tools.ietf.org/html/draft-dulaunoy-misp-core-format-00) | 文档主要介绍了在 MISP 实例间进行指标与威胁情报交换的核心格式 |
| [NECOMA Project](http://www.necoma-project.eu/)              | Nippon-European Cyberdefense-Oriented Multilayer threat Analysis (NECOMA) 研究项目旨在改进威胁情报的收集和分析，来展示新的网络防范机制，作为项目的一部分，出版物和软件已经面世 |
| [Pyramid of Pain](http://rvasec.com/slides/2014/Bianco_Pyramid of Pain.pdf) | Pyramid of Pain 以图形化方式来表达不同级别指标数据的困难度，以及防守者发现时攻击方获得的资源量 |
| [Structured Analytic Techniques For Intelligence Analysis](https://www.amazon.com/Structured-Analytic-Techniques-Intelligence-Analysis/dp/1452241511) | 这本书包含了代表威胁情报、法律执行、国土安全以及商业分析最佳实践的方法 |
| [Threat Intelligence: Collecting, Analysing, Evaluating](https://www.ncsc.gov.uk/content/files/protected_files/guidance_files/MWR_Threat_Intelligence_whitepaper-2015.pdf) | MWR InfoSecurity 的报告清楚的描述了威胁情报几种不同的类型，包括战略、战术和执行变化。还讨论了需求启发、收集、分析、生成和评估威胁情报的过程。也包括了其定义的每种威胁情报的成熟度模型 |
| [Threat Intelligence Sharing Platforms: An Exploratory Study of Software Vendors and Research Perspectives](http://aisel.aisnet.org/wi2017/track08/paper/3/) | 对 22 种威胁情报共享平台（TISP）的系统化研究提出了当前状态下关于威胁情报使用的情况，其定义和 TISPs 系统 |
| [Traffic Light Protocol](https://www.us-cert.gov/tlp)        | Traffic Light Protocol (TLP) 是一组用来确保敏感信息可以被正确发布接收的信号组合。其使用四种颜色来标定不同程度的敏感信息和与其敏感程度相适应的接收人 |
| [Unit42 Playbook Viewer](https://pan-unit42.github.io/playbook_viewer/) | Playbook 的目标是将对手使用的工具、技术和程序组织成结构化格式，可以与其他人共享、并在此基础上构建。用于构建、共享的框架是 MITRE 的 ATT&CK 框架与 STIX 2.0 |
| [Who's Using Cyberthreat Intelligence and How?](https://www.sans.org/reading-room/whitepapers/analyst/who-039-s-cyberthreat-intelligence-how-35767) | 由 SANS 研究所出品，描述包括策略执行在内的威胁情报使用情况的白皮书 |
| [WOMBAT Project](http://www.wombat-project.eu/)              | WOMBAT 项目旨在提供新的手段来了解针对互联网出现的新威胁。为了实现这一目标，该方案包括三个关键的工作：（1）实时收集各种与安全相关的原始数据（2）通过各种分析技术丰富输入数据（3）辨识和理解当前的安全状况 |