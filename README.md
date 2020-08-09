# Awesome Cybersecurity Blue Team - CN[![Awesome](https://awesome.re/badge-flat2.svg)](https://awesome.re)

>   攻防对抗 · 蓝队清单，中文版

本项目基于[awesome-cybersecurity-blueteam](https://github.com/fabacab/awesome-cybersecurity-blueteam)，经过蹩脚的翻译和一些补充，**旨在帮助以中文为母语的安全研究者更好地了解蓝队工作，以及便利地找寻蓝队工具**。

非常感谢原作者的整理，对于我这个蓝队的入门学习者来说，帮助非常大。也希望自己的一点点工作能帮助到你，一起来玩吧！

> 在网络安全蓝队方向的一些很酷的资源、工具和一些小玩意～
>
> 网络安全·蓝队，是由一群能够识别信息技术系统中安全缺陷的人组成。他们能够验证安全防护措施的有效性，并且能持续监控系统并确保已采用的安全防御措施。 
>
> 尽管没有偏见，但这个列表更倾向于[自由软件](https://www.gnu.org/philosophy/free-sw.html)项目，而不是商业的产品和服务。 
>
> 关于攻防对抗的TTPs（战术、技术和过程），请查看这个项目：[awesome-pentest](https://github.com/fabacab/awesome-pentest).  
>
> 你的贡献和建议十分重要，欢迎来参与(✿◕‿◕)。请查看[贡献准则](CONTRIBUTING.md)来获取更多的信息。本项目是在[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/)许可下进行的。



## 🚀在线文档请查看：https://y1ng.org/awesome-cybersecurity-blueteam-cn/



## 🧾目录

- [自动化工具](#%E8%87%AA%E5%8A%A8%E5%8C%96%E5%B7%A5%E5%85%B7)
    - [零碎的](#%E9%9B%B6%E7%A2%8E%E7%9A%84)
    - [代码库和绑定](#%E4%BB%A3%E7%A0%81%E5%BA%93%E5%92%8C%E7%BB%91%E5%AE%9A)
    - [安全编排自动化与响应](#%E5%AE%89%E5%85%A8%E7%BC%96%E6%8E%92%E8%87%AA%E5%8A%A8%E5%8C%96%E4%B8%8E%E5%93%8D%E5%BA%94)
- [云平台安全](#%E4%BA%91%E5%B9%B3%E5%8F%B0%E5%AE%89%E5%85%A8)
- [通讯安全](#%E9%80%9A%E8%AE%AF%E5%AE%89%E5%85%A8)
- [DevSecOps](#devsecops)
    - [应用或二进制加固](#%E5%BA%94%E7%94%A8%E6%88%96%E4%BA%8C%E8%BF%9B%E5%88%B6%E5%8A%A0%E5%9B%BA)
    - [模糊测试](#%E6%A8%A1%E7%B3%8A%E6%B5%8B%E8%AF%95)
    - [策略执行](#%E7%AD%96%E7%95%A5%E6%89%A7%E8%A1%8C)
- [蜜罐](#%E8%9C%9C%E7%BD%90)
    - [Tarpits](#tarpits)
- [主机防护工具](#%E4%B8%BB%E6%9C%BA%E9%98%B2%E6%8A%A4%E5%B7%A5%E5%85%B7)
    - [沙箱](#%E6%B2%99%E7%AE%B1)
- [事件响应工具](#%E4%BA%8B%E4%BB%B6%E5%93%8D%E5%BA%94%E5%B7%A5%E5%85%B7)
    - [事件响应管理平台](#%E4%BA%8B%E4%BB%B6%E5%93%8D%E5%BA%94%E7%AE%A1%E7%90%86%E5%B9%B3%E5%8F%B0)
    - [事件证据搜集（取证）](#%E4%BA%8B%E4%BB%B6%E8%AF%81%E6%8D%AE%E6%90%9C%E9%9B%86%E5%8F%96%E8%AF%81)
- [网络外围防御](#%E7%BD%91%E7%BB%9C%E5%A4%96%E5%9B%B4%E9%98%B2%E5%BE%A1)
    - [防火墙设备或发行版](#%E9%98%B2%E7%81%AB%E5%A2%99%E8%AE%BE%E5%A4%87%E6%88%96%E5%8F%91%E8%A1%8C%E7%89%88)
    - [操作系统发行版](#%E6%93%8D%E4%BD%9C%E7%B3%BB%E7%BB%9F%E5%8F%91%E8%A1%8C%E7%89%88)
    - [网络钓鱼意识和报告](#%E7%BD%91%E7%BB%9C%E9%92%93%E9%B1%BC%E6%84%8F%E8%AF%86%E5%92%8C%E6%8A%A5%E5%91%8A)
- [攻防演练](#%E5%A4%87%E6%88%98%E8%AE%AD%E7%BB%83%E5%8F%8A%E6%BC%94%E4%B9%A0)
- [安全监控](#%E5%AE%89%E5%85%A8%E7%9B%91%E6%8E%A7)
    - [端点防护及响应（EDR）](#%E7%AB%AF%E7%82%B9%E9%98%B2%E6%8A%A4%E5%8F%8A%E5%93%8D%E5%BA%94edr)
    - [网络安全监控（NSM）](#%E7%BD%91%E7%BB%9C%E5%AE%89%E5%85%A8%E7%9B%91%E6%8E%A7nsm)
    - [安全信息和事件管理（SIEM）](#%E5%AE%89%E5%85%A8%E4%BF%A1%E6%81%AF%E5%92%8C%E4%BA%8B%E4%BB%B6%E7%AE%A1%E7%90%86siem)
    - [服务和性能监控](#%E6%9C%8D%E5%8A%A1%E5%92%8C%E6%80%A7%E8%83%BD%E7%9B%91%E6%8E%A7)
    - [威胁狩猎](#%E5%A8%81%E8%83%81%E7%8B%A9%E7%8C%8E)
- [威胁情报](#%E5%A8%81%E8%83%81%E6%83%85%E6%8A%A5)
- [Tor Onion服务防护](#tor-onion%E6%9C%8D%E5%8A%A1%E9%98%B2%E6%8A%A4)
- [传输层防护](#%E4%BC%A0%E8%BE%93%E5%B1%82%E9%98%B2%E6%8A%A4)
- [基于macOS的防护](#%E5%9F%BA%E4%BA%8Emacos%E7%9A%84%E9%98%B2%E6%8A%A4)
- [基于Windows的防护](#%E5%9F%BA%E4%BA%8Ewindows%E7%9A%84%E9%98%B2%E6%8A%A4)
- [License](#license)
- [References](#references)



## 自动化工具

### 零碎的

- [Ansible Lockdown](https://ansiblelockdown.io/) - 以信息安全为主题的Ansible（运维工具）规则集合。经过精心地审核，并且维护积极
- [Clevis](https://github.com/latchset/clevis) - 对于自动解密的可插入式工具，经常被用做[Tang](https://github.com/latchset/tang)客户端
- [DShell](https://github.com/USArmyResearchLab/Dshell) - 用Python编写网络取证分析框架，支持扩展，可快速开发插件来分析捕获的网络数据包
- [Dev-Sec.io](https://dev-sec.io/) - 服务器增强框架，提供各种基准安全配置的Ansible，Chef和Puppet实现
- [peepdf](https://eternal-todo.com/tools/peepdf-pdf-analysis-tool) - 支持脚本编写的PDF文件分析器

### 代码库和绑定

- [MultiScanner](https://github.com/mitre/multiscanner) - 使用Python编写的文件分析框架，支持自动运行相关的工具，汇总输出帮助评估一组带分析的文件
- [Posh-VirusTotal](https://github.com/darkoperator/Posh-VirusTotal) - 可与VirusTotal.com的API进行交互的PowerShell接口
- [censys-python](https://github.com/censys/censys-python) - 对Censys REST API的Python轻量级封装
- [libcrafter](https://github.com/pellegre/libcrafter) - 一个c++的高级库，用于创建和解码网络数据包
- [python-dshield](https://github.com/rshipp/python-dshield) - 连接SANS ISC/DShiel API的Python接口
    - 补充：SANS ISC是一个全球性的安全事件响应组织，为所有的Internet用户和组织提供免费的互联网攻击分析和预警服务
- [python-sandboxapi](https://github.com/InQuest/python-sandboxapi) - 用于构建恶意软件沙箱集成的最小型、并且长期有效的的Python API
- [python-stix2](https://github.com/oasis-open/cti-python-stix2) - 用于序列化和反序列化STIX（JSON形式）的Python API，以及一些用于常见任务的高级API
    - 补充：STIX是用来交换威胁情报的一种语言和序列化格式，由MITRE联合DHS（美国国土安全部）发布

### 安全编排自动化与响应

SOAR, Security Orchestration, Automation and Response, 安全编排自动化与响应。

另行查阅[Security Information and Event Management (SIEM)](#security-information-and-event-management-siem)和[IR management consoles](#ir-management-consoles).

- [Shuffle](https://shuffler.io/) - 用于IT专家和蓝队成员的图形化工作流（自动化）生成器



## 云平台安全

另请参阅：[asecure.cloud/tools](https://asecure.cloud/tools/).

- [Checkov](https://www.checkov.io/) - 对于Terraform（在DevOps实践中，代码即基础设施概念）的静态分析器。可以帮助检测CIS策略违规行为，并防止云安全策略配置错误
    - 补充：Terraform是一种安全有效地构建、更改和版本控制基础设施的工具(基础架构自动化的编排工具)[1]
    - 补充：[CIS](https://www.cisecurity.org/cis-benchmarks/)基准是安全配置系统的配置基线和最佳做法[2]
- [Falco](https://falco.org/) - 行为活动监视器，旨在通过审核Linux内核和运行时数据（例如Kubernetes指标）进行拓展和丰富，以检测容器化的应用程序，以及主机和网络数据包流中的异常活动
- [Istio](https://istio.io/) - 提供统一的方式的开放平台，可以集成微服务，管理跨微服务的流量，执行策略和汇总遥测数据
- [Kata Containers](https://katacontainers.io/) - 使用轻量级虚拟机来保护容器的运行时，这些虚拟机的情况和性能类似于容器，但是使用硬件虚拟化技术作为第二层防御，可以提供更强的工作负载隔离
- [Managed Kubernetes Inspection Tool (MKIT)](https://github.com/darkbitio/mkit) - 可提供查询和验证托管Kubernetes群集对象以及群集内运行的工作负载/资源的几种与安全性相关的常见设置
- [Prowler](https://github.com/toniblyx/prowler) - 基于AWS-CLI命令的工具，用于Amazon Web Services帐户安全性评估和增强
- [Scout Suite](https://github.com/nccgroup/ScoutSuite) - 开源的多云安全审核工具，可用于评估云环境的安全状态
    - 补充：Muticloud，多云，是指在单个异构架构中使用多个[云计算](https://en.wikipedia.org/wiki/Cloud_computing)和[存储](https://en.wikipedia.org/wiki/Cloud_storage)服务
- [gVisor](https://github.com/google/gvisor) - 用Go编写的应用程序内核，它实现Linux系统表面的很大一部分，用以在应用程序和主机内核之间提供隔离边界



## 通讯安全

COMSEC, Communications Security, 通讯安全

- [GPG Sync](https://github.com/firstlookmedia/gpgsync) - 用于在组织和团队中进行自动化OpenPGP公钥集成和分发。



## DevSecOps

另请参阅：[awesome-devsecops](https://github.com/devsecops/awesome-devsecops)

补充：DevOps旨在加强开发人员，IT运营和安全性之间的关系。

- [BlackBox](https://github.com/StackExchange/blackbox) - 通过GnuPG技术安全地保存Git/Mercurial/Subversion的密钥，该过程可在空闲时进行
- [Cilium](https://cilium.io/) - 开源软件，用于透明地保护应用服务和Linux容器化管理平台（e.g. Docker, Kubernetes）之间的网络连接安全
    - 透明是指，Cilium 是位于 Linux kernel 与容器编排系统的中间层。向上可以为容器配置网络，向下可以向 Linux 内核生成 BPF 程序来控制容器的安全性和转发行为
- [Clair](https://github.com/coreos/clair) - 静态分析工具，用于探测应用容器镜像（e.g. Docker）中的漏洞
- [CodeQL](https://securitylab.github.com/tools/codeql) - 通过对代码进行查询，就像发现数据一样，从而发现整个代码库中的漏洞
- [DefectDojo](https://www.defectdojo.org/) - 为DevOps和可持续的安全集成而生的应用程序漏洞管理工具
- [Gauntlt](http://gauntlt.org/) - 用于应用在测试和通讯中进行安全性的渗透测试
- [Git Secrets](https://github.com/awslabs/git-secrets) - 用于防止用户提交密码或其他的敏感信息到Git仓库
- [Vault](https://www.vaultproject.io/) - 用于通过统一的界面安全访问密钥（例如API密钥，密码或证书）的工具
- [git-crypt](https://www.agwa.name/projects/git-crypt/) - 同样用于防止用户将密钥提交到Git仓库。其中，选择保护的文件在提交时会加密，在签出时会解密
- [Snyk](https://snyk.io/) - 用于查找并修复开源依赖项和容器映像中的漏洞和许可证违规信息
- [SonarQube](https://sonarqube.org) - 持续性代码检查工具，可在自动测试期间提供详细的报告，并就新引入的安全漏洞提供警告
### 应用或二进制加固

- [Egalito](https://egalito.org/) - 是一个二进制反编译器，可以完全反汇编、转换和重新生成用于二进制强化和安全性研究的普通Linux二进制文件。
### 模糊测试（Fuzzing）

另请参阅： [Awesome-Fuzzing](https://github.com/secfigo/Awesome-Fuzzing).

- [FuzzBench](https://google.github.io/fuzzbench/) -  用于根据Google规模的各种实际基准来评估模糊测试器的一项免费服务
### 策略执行

- [OpenPolicyAgent](https://www.openpolicyagent.org/)  - 用于跨云原生环境进行统一策略控制的一套工具集和框架
- [Tang](https://github.com/latchset/tang) - 用于将数据绑定到网络状态的服务器。只有当客户端位于特定的（安全的）网络上时才向客户端提供数据



## 蜜罐

另请参阅：[awesome-honeypots](https://github.com/paralax/awesome-honeypots).

- [CanaryTokens](https://github.com/thinkst/canarytokens) - 可以自承载的Honey Token生成器及报告模版，演示版本可查看：[CanaryTokens.org](https://canarytokens.org/).
    - 补充，Honey Token：对蜜罐概念的一种发展，是一种数字化的实体，使得蜜罐不再局限于硬件设备。任何黑客感兴趣信息的伪造都可成为蜜罐[3]。例如，一串银行卡密码、一个名为“财务报表”的Excel表格等
- [Kushtaka](https://kushtaka.org) - 可持续的多合一蜜罐和honey token编排器，用于资源不丰富的蓝队

### Tarpits

补充：Tarpit(Tar pit, 焦油坑)概念为低于计算器蠕虫而生。核心思路是：对于网络攻击（例如扫描器和密码爆破工具）来说，如果其总共消耗的时间过长，那么对于攻击者来说，这些系统的吸引力也会降低。

其实这也是从攻防成本的角度出发，攻防对抗的本质是成本的对抗，利用该类型的蜜罐技术，可以增加攻击者的时间成本，从而丧失行动力。

这种概念类似焦油坑，陷入其中的东西会缓慢地沉入，让对方失去行动力，因此被称为Tarpit(Tar pit, 焦油坑)。


- [Endlessh](https://github.com/skeeto/endlessh) - 一种SSH tarpit，可以缓慢地发送无休止的SSH banner

    - 补充，SSH Banner：即SSH警告横幅，在使用SSH进行交互式会话期间，登录前SSH警告横幅会显示在密码提示之前[4]，一些法律警告和相关条款
- [LaBrea](http://labrea.sourceforge.net/labrea-info.html) - 一种响应ARP请求中未使用的IP空间的程序，其伪造机器的外表，非常缓慢地响应其他请求，从而达到减慢扫描程序，蠕虫等速度的目的



## 主机防护工具

- [Artillery](https://github.com/BinaryDefense/artillery) - 一套结合了蜜罐，文件系统监视器和警报系统的工具，旨在保护Linux和Windows操作系统
- [chkrootkit](http://chkrootkit.org/) - 用于在GNU / Linux系统上本地检查rootkit的迹象
    - 补充，Rootkit：常指被作为驱动程序，加载到操作系统内核中的恶意软件
- [Crowd Inspect](https://www.crowdstrike.com/resources/community-tools/crowdinspect-tool/) - 针对Windows系统，用于提醒可能存在的、通过网络进行通信的恶意软件的工具
- [Fail2ban](https://www.fail2ban.org/) - 入侵防御软件框架，可保护计算机服务器免遭暴力攻击
- [OpenSCAP Base](https://www.open-scap.org/tools/openscap-base/) - 即代表库又代表命令行（扫描）工具，可用于解析和评估[SCAP标准的](https://www.open-scap.org/features/standards/)每个组件，即根据SCAP基线配置文件来评估系统，从而报告被扫描系统的安全状态
- [Open Source HIDS SECurity (OSSEC)](https://www.ossec.net/) - 完全开源、免费的，功能丰富的基于主机的入侵检测系统（HIDS）
- [Rootkit Hunter (rkhunter)](http://rkhunter.sourceforge.net/) - 该工具兼容POSIX的Bash脚本，用以扫描主机来查找各种恶意软件迹象

### 沙箱

- [Firejail](https://firejail.wordpress.com/) - SUID程序，使用Linux命名空间和seccomp-bpf来限制不受信任的应用程序的运行环境，从而降低安全漏洞的风险
    - 补充，Linux命名空间：是Linux内核的一项功能，它对内核资源进行分区，以使一组进程看到一组资源，而另一组进程看到另一组资源
    - 补充，seccomp-bpf
        - 先介绍即seccomp，是Linux的一种安全机制，通过限制程序使用某些系统调用，减少系统的暴露面，使得程序进入一种“安全”的状态
        - 再来说说BPF，BPF全称是Berkeley Packet Filter。目的是为了提供一种过滤包的方法，并且要避免从内核空间到用户空间的无用的数据包复制行为
        - 所以，seccomp-bpf即采用了BPF方法对syscall进行过滤的seccomp。seccomp在过滤syscall的时候，借助了BPF定义的过滤规则，以及处于内核的用BPF language写的mini-program



## 事件响应工具

另请参阅：[awesome-incident-response](https://github.com/meirwah/awesome-incident-response).

- [LogonTracer](https://github.com/JPCERTCC/LogonTracer) - 可用于可视化分析Windows事件日志来调查恶意的Windows登录
- [Volatility](https://www.volatilityfoundation.org/) - 一套先进的内存取证框架
- [aws_ir](https://github.com/ThreatResponse/aws_ir) - 通过零信任安全假设来自动化执行事件响应的工具
    - 补充，零安全：本质是以身份为基石的动态访问控制，即以身份为基础，通过动态访问控制技术，以细粒度的应用、接口、数据为核心保护对象，遵循最小权限原则，构筑端到端的身份边界[5]

### 事件响应管理平台

Incident Response management consoles，事件响应管理平台

另请参阅 [Security Orchestration, Automation, and Response (SOAR)](#安全编排自动化与响应).

- [CIRTKit](https://github.com/opensourcesec/CIRTKit) - 基于Viper构建的、可编写脚本的数字取证和事件响应（Digital Forensics and Incident Response, DFIR）工具包
- [Fast Incident Response (FIR)](https://github.com/certsocietegenerale/FIR) - 一个网络安全事件管理平台，可以轻松创建，跟踪和报告网络安全事件
- [Rekall](http://www.rekall-forensic.com/) - 一个先进的取证及事件响应的框架
- [TheHive](https://thehive-project.org/) - 可扩展的免费安全事件响应平台，旨在[简化](https://thehive-project.org/)与SOC，CSIRT和[CERT的交互](https://thehive-project.org/)，并与MISP紧密集成。
    - 补充
        - SOC：Security operations center，安全管理/运营中心
        - CSIRT：Computer Security Incident Response Team，计算机安全入侵事件响应小组，偏溯源
        - CERT：Computer Emergency Response Team，计算机应急响应中心/小组，偏指挥
        - MISP：Malware Information Sharing Platform，威胁情报共享平台，偏情报
- [threat_note](https://github.com/defpoint/threat_note) - 用于方便安全研究人员添加和检索与他们自己研究的相关指标，是一个由[Defence Point Security](https://www.crunchbase.com/organization/defense-point-security)（一个美国的网络安全公司）构建的Web应用程序
    - 注：简单讲，这个平台目前实现的功能是一个便于添加攻击者向量（IoC）的一个笔记应用

### 事件证据搜集（取证）

- [AutoMacTC](https://github.com/CrowdStrike/automactc) - 一个模块化的自动取证分类收集框架，旨在访问macOS上的各种取证工件，进行解析，并以可用的格式化形式展现。
- [OSXAuditor](https://github.com/jipegit/OSXAuditor) - 一个免费的macOS计算机取证工具
- [OSXCollector](https://github.com/Yelp/osxcollector) - 适用于macOS的证据收集和分析工具包
- [ir-rescue](https://github.com/diogo-fernan/ir-rescue) - 用于在事件响应期间全面收集主机取证数据的脚本（包括Windows Batch脚本和Unix Bash脚本）
- [Margarita Shotgun](https://github.com/ThreatResponse/margaritashotgun) - 命令行工具，用于并行的远程内存获取，可自由选择是否与Amazon EC2实例一起使用



## 网络外围防御

Network perimeter defenses

- [Gatekeeper](https://github.com/AltraMayor/gatekeeper) - 第一个开源的、用于分布式拒绝服务（DDoS）保护的系统
- [fwknop](https://www.cipherdyne.org/fwknop/) - 通过防火墙中的单包授权保护端口
    - 补充，单包授权：Single Packet Authorization，SPA。SPA将单个数据包经过加密，不可重放，并通过HMAC进行身份验证，以便在传达到隐藏在防火墙后面的服务[6]
- [ssh-audit](https://github.com/jtesta/ssh-audit) - 用于快速提出建议来改善SSH服务器安全状况的一个简易工具

### 防火墙设备或发行版

- [OPNsense](https://opnsense.org/) - 一个基于FreeBSD的防火墙和路由平台
- [pfSense](https://www.pfsense.org/) - 用于防火墙和路由器的FreeBSD发行版

### 操作系统发行版

- [Computer Aided Investigative Environment (CAINE)](https://caine-live.net/) - Italian GNU/Linux live distribution that pre-packages numerous digital forensics and evidence collection tools.
- 意大利的GNU / Linux发行版，预先打包了许多用于数字取证和证据收集的工具
- [Security Onion](https://securityonion.net/) - 免费和开源GNU / Linux发行版，用于入侵检测，企业安全监视和日志管理


### 网络钓鱼意识和报告

另请参阅[awesome-pentest § Social Engineering Tools](https://github.com/fabacab/awesome-pentest#social-engineering-tools)

- [CertSpotter](https://github.com/SSLMate/certspotter) - 来自SSLMate的证书透明日志监视器，当你的某个域被颁发SSL/TLS证书时，该监视器会发出警报
- [Gophish](https://getgophish.com/) - 强大的开源网络钓鱼框架，可轻松测试组织对网络钓鱼的危害
- [King Phisher](https://github.com/securestate/king-phisher) - 通过模拟真实的网络钓鱼攻击来测试和提高用户意识的工具
- [NotifySecurity](https://github.com/certsocietegenerale/NotifySecurity) - Outlook加载项，用于帮助您的用户向安全团队报告可疑电子邮件。
- [Phishing Intelligence Engine (PIE)](https://github.com/LogRhythm-Labs/PIE) - 有助于检测和响应网络钓鱼攻击的框架
- [Swordphish](https://github.com/certsocietegenerale/swordphish-awareness) - 该平台可用于创建和管理（伪造）网络钓鱼活动，目的是训练目标识别可疑邮件的能力
- [mailspoof](https://github.com/serain/mailspoof) - 可用与扫描SPF和DMARC记录来查找可能造成电子邮件欺骗的问题
    - 补充
        - SPF：Sender Policy Framework，发信者策略架构，是为了防范垃圾邮件而提出来的一种DNS记录类型，它是一种TXT类型的记录，用于登记某个域名拥有的用来外发邮件的所有IP地址
        - DMARC：Domain-based Message Authentication, Reporting and Conformance，基于基于域的消息认证，报告和一致性。是一套以SPF及DKIM为基础的电子邮件认证机制，可以检测及防止伪冒身份、对付网络钓鱼或垃圾电邮
        - DKIM：DomainKeys Identified Mail，域名密钥识别邮件。是一套电子邮件认证机制，使用公开密钥加密的基础提供了数字签名与身份验证的功能，以检测寄件者、主旨、内文、附件等部分有否被伪冒或窜改。
- [phishing_catcher](https://github.com/x0rz/phishing_catcher) - 使用[CertStream](https://certstream.calidog.io/)服务在证书透明日志(CTL)中通过域名监视可疑TLS证书的可配置脚本



## 攻防演练

Preparedness training and wargaming，备战训练及演习。也同样被称为*adversary emulation*和*threat simulation*之类。此处使用大陆地区较为常见的说法：攻防演练。

- [APTSimulator](https://github.com/NextronSystems/APTSimulator) - 可以使系统看起来像APT攻击受害者的工具集
- [Atomic Red Team](https://atomicredteam.io/) - 一个简单，可自动执行的测试库，可以执行这些测试来测试安全性控件
- [DumpsterFire](https://github.com/TryCatchHCF/DumpsterFire) - 一个模块化，菜单驱动的跨平台工具，可用于为蓝队演练和传感器/警报映射构建可重复的、延迟的、分布式的安全事件
- [Metta](https://github.com/uber-common/metta) - 自动化的信息安全防范工具，可以进行对抗性模拟
- [Network Flight Simulator (`flightsim`)](https://github.com/alphasoc/flightsim) - 用于生成恶意网络流量，可帮助安全团队评估安全控制以及审核他们网络的可见性
- [RedHunt OS](https://github.com/redhuntlabs/RedHunt-OS) - 基于Ubuntu的开放式虚拟设备（`.ova`），预配置了多个威胁仿真工具以及防守方的工具包



## 安全监控

### 端点防护及响应（EDR）
Endpoint Detection and Response , EDR

- [Wazuh](https://wazuh.com/) - 开源的、基于多平台代理的安全监视平台。基于[OSSEC HIDS](https://github.com/ossec/ossec-hids)分支开发

### 网络安全监控（NSM）

Network Security Monitoring (NSM)

另请参阅：[awesome-pcaptools](https://github.com/caesar0301/awesome-pcaptools).

- [ChopShop](https://github.com/MITRECND/chopshop) - 一个MITER开发的框架，可帮助分析人员创建和执行基于APT工具及Pynids的解码器和检测器
- [Maltrail](https://github.com/stamparm/maltrail) - 一个恶意网络流量检测系统
- [Moloch](https://github.com/aol/moloch) - 可扩展当前的安全基础架构，以标准的PCAP格式存储和索引网络流量，从而实现快速的索引访问
- [OwlH](https://www.owlh.net/) - 可通过可视化Suricata，Zeek和Moloch生命周期来帮助大规模管理网络IDS
    - OwlH开源项目地址：https://github.com/owlh-net
    - 补充
        - Suricata：一款开源高性能的入侵检测系统，并支持IPS（入侵防御）与NSM（网络安全监控）模式，用来替代原有的[snort](https://www.snort.org/)入侵检测系统，完全兼容Snort规则语法和支持lua脚本[7]
        - Zeek：是一款开源网络安全分析工具。通过 Zeek 可以监测网络流量中的可疑活动，Zeek 脚本可以实现灵活的分析功能，可是实现多种协议的简易分析
        - Moloch：是一款开源的大型 IPv4 抓包（PCAP），检索和数据库系统。Moloch  并不能替代 IDS 引擎，相反它们指尖相辅相成可以一起使用，可以 PCAP  格式将保存和检索所有网络流量，提供快速访问。可在多个系统上部署，可进行扩展以应对多种网速传输。[8]
- [Respounder](https://github.com/codeexpress/respounder) - 可检测网络上是否存在使用[Responder](https://github.com/SpiderLabs/Responder)来进行LLMNR / NBT-NS / mDNS投毒的情况
    - 补充
        - LLMNR：The Link Local Multicast Name Resolution， 本地链路多播名称解析，是一个基于协议的域名系统（DNS）数据包格式的网际协议，该协议允许IPv4和IPv6主机对同一本地链路上的主机来执行名称解析
        - NBT-NS：与LLMNR一样，也是Microsoft Windows的一个系统组件
        - mDNS：在计算机网络中， 多播DNS(the multicast DNS)协议将主机名解析为不包含本地名称服务器的小型网络中的IP地址
    - 实际操作：https://www.anquanke.com/post/id/85503
- [Real Intelligence Threat Analysis (RITA)](https://github.com/activecm/rita) - 是一套用于网络流量分析的开源框架，可吸收Zeek日志并检测信标，DNS隧道等
- [Snort](https://snort.org/) - 广泛部署的免费IPS软件，能够进行实时数据包分析，流量记录和基于规则的自定义触发器
- [SpoofSpotter](https://github.com/NetSPI/SpoofSpotter) - 捕获被欺骗的NetBIOS名称服务（NBNS）响应，并发出电子邮件或日志文件形式的警告
    - 补充
        - NBNS：Network Basic Input/Output System, ,网上基本输入输出系统。提供了OSI模型中会话层服务，让在不同计算机上运行的不同程序，可以在局域网中，互相连线，以及分享数据
- [Stenographer](https://github.com/google/stenographer) - 可进行全包捕获的实用程序，用于将数据包缓冲到磁盘以进行入侵检测和事件响应
- [Suricata](https://suricata-ids.org/) - 一个免费的，跨平台的IDS / IPS，具有在线和离线分析模式以及深度数据包检查功能，该功能也可以通过Lua语言编写
- [VAST](https://github.com/tenzir/vast) - 一个用于数据驱动的安全调查的免费开源网络遥测引擎
- [Wireshark](https://www.wireshark.org) - 一个免费、开源的数据包分析器，广泛使用，具有较好的GUI，可用于网络故障排除或数字取证方面的网络流分析
- [Zeek](https://zeek.org/) - 一个强大的网络分析框架，专注于安全监控，以前称为Bro
- [netsniff-ng](http://netsniff-ng.org/) - 具有许多实用程序的便捷GNU / Linux网络工具包，例如连接跟踪工具（`flowtop`），流量生成器（`trafgen`）和自治系统（AS）跟踪路由实用程序（`astraceroute`）


### 安全信息和事件管理（SIEM）

Security Information and Event Management (SIEM)
- [AlienVault OSSIM](https://www.alienvault.com/open-threat-exchange/projects) - 一个威胁交换（OTX）驱动的单服务器开源SIEM平台，具有资产发现，资产清单，行为监控和事件关联功能。由[AlienVault](https://otx.alienvault.com/)开发
- [Prelude SIEM OSS](https://www.prelude-siem.org/) - 一个开放源码的、无代理的SIEM，有较长的历史和几个商业变体。具有安全事件收集、规范化和从任意日志输入发出警报以及许多流行的监视工具

### 服务和性能监控

Service and performance monitoring

另请参阅：[awesome-sysadmin#monitoring](https://github.com/n1trux/awesome-sysadmin#monitoring).

- [Icinga](https://icinga.com/) - 基于Nagios的模块化重新设计，带有可插拔的用户界面以及一组扩展出的数据连接器，收集器和报告工具
- [Locust](https://locust.io/) - 一个分布式开源负载测试工具，可以在其中使用Python代码定义用户行为，并让数百万用户同时进行支持
- [Nagios](https://nagios.org) - 一个流行的网络和服务监视解决方案和报告平台
- [OpenNMS](https://opennms.org/) - 一个免费且功能丰富的网络监视系统，支持多种配置，多种警报机制（电子邮件，XMPP，SMS）以及多种数据收集方法（SNMP，HTTP，JDBC等）。
- [osquery](https://github.com/facebook/osquery) - 一个适用于macOS、Windows和Linux的操作系统插装框架，其将操作系统公开为高性能关系数据库，可以使用类似sql的语法进行查询
- [Zabbix](https://www.zabbix.com/) - 一个成熟的企业级平台，用于监视大规模IT环境。

### 威胁狩猎

Threat hunting，也被称为*hunt teaming*和*threat detection*。

另请参阅：[awesome-threat-detection](https://github.com/0x4D31/awesome-threat-detection).

- [CimSweep](https://github.com/PowerShellMafia/CimSweep) - 基于CIM / WMI的工具套件，可在所有Windows版本中进行远程事件响应和[Hunting](https://github.com/PowerShellMafia/CimSweep)操作
- [DeepBlueCLI](https://github.com/sans-blue-team/DeepBlueCLI) - 用于通过Windows事件日志进行寻线分组的PowerShell模块
- [GRR Rapid Response](https://github.com/google/grr) - 一个专注于远程实时取证的事件响应框架，该组件由安装在资产上的Python代理和基于Python的服务器组成基础结构，使分析师能够快速分类攻击并进行远程分析
- [Hunting ELK (HELK)](https://github.com/Cyb3rWard0g/HELK) - 基于Elasticsearch，Logstash，Kafka和Kibana的多合一免费软件威胁狩猎套件，并具有包括Jupyter Notebook在内的各种内置集成分析功能
- [MozDef](https://github.com/mozilla/MozDef) - 用于自动执行安全事件处理流程，并促进事件处理程序的实时活动
- [PSHunt](https://github.com/Infocyte/PSHunt) - 一个PowerShell模块，设计用于扫描远程端点以发现威胁的痕迹，或用于调查，获取与系统状态有关的更多信息
- [PSRecon](https://github.com/gfoss/PSRecon) - 一个类似PSHunt的工具，可用于分析远程的Windows系统，该工具还会生成其发现信息的独立HTML报告
- [PowerForensics](https://github.com/Invoke-IR/PowerForensics) - 基于PowerShell，用于实时硬盘取证分析的多合一平台
- [rastrea2r](https://github.com/rastrea2r/rastrea2r) - 一个用于同时在众多端点上对可疑IOC进行分类，并与防病毒控制台集成的跨平台工具
- [Redline](https://www.fireeye.com/services/freeware/redline.html) - [FireEye](https://www.fireeye.com/)公司的提供的免费端点审计和分析工具，提供基于主机的调查功能



## 威胁情报

Threat intelligence

另请参阅：[awesome-threat-intelligence](https://github.com/hslatman/awesome-threat-intelligence).

- [Active Directory Control Paths](https://github.com/ANSSI-FR/AD-control-paths) - 可视化Active Directory权限配置并对其进行图形化处理，用来审核诸如“谁可以阅读CEO的电子邮件？”之类的问题
- [AttackerKB](https://attackerkb.com/) - 免费公开的漏洞评估平台，可帮助确定高风险补丁程序的优先级来消除漏洞疲劳
    - 补：漏洞疲劳（vulnerability fatigue）指系统每天都会发现越来越多的漏洞，因此内部团队很难迅速提供纠正补丁。而黑客就会利用这段时间来分析信息系统，发现漏洞并发起成功的攻击。[9]
- [DATA](https://github.com/hadojae/DATA) - 用于网络钓鱼凭据分析和自动化的工具，可以直接接收可疑网络钓鱼URL，或在观察到的包含此类URL的网络流量时触发
- [Forager](https://github.com/opensourcesec/Forager) - 使用Python3构建的多线程威胁情报收集工具。基于文本进行了简单配置和数据存储，以简化使用和数据可移植性。
- [GRASSMARLIN](https://github.com/nsacyber/GRASSMARLIN) - 该工具通过被动映射，计算和报告ICS / SCADA网络拓扑和端点，提供IP网络对工业控制系统（ICS）以及监督控制和数据采集（SCADA）的态势感知
- [MLSec Combine](https://github.com/mlsecproject/combine) - 该工具收集并组合多个威胁情报源，并将其组合成一种可定制的，基于CSV的标准化格式
- [Malware Information Sharing Platform and Threat Sharing (MISP)](https://misp-project.org/) - 一种用于收集，存储，分发和共享网络安全指标的开源软件解决方案
- [ThreatIngestor](https://github.com/InQuest/ThreatIngestor) - 可扩展工具，用于从威胁源（包括Twitter，RSS或其他源）提取和聚合IOC
- [Unfetter](https://nsacyber.github.io/unfetter/) - 该工具利用Mitre的ATT&CK框架来识别安全态势中的防御性漏洞
- [Viper](https://github.com/viper-framework/viper) - 二进制分析和管理框架，可轻松组织恶意软件和利用样本



## Tor Onion服务防护

Tor Onion service defenses

另请参阅：[awesome-tor](https://github.com/ajvb/awesome-tor).

- [OnionBalance](https://onionbalance.readthedocs.io/) - 该工具用于提供Tor网络代理的负载平衡，同时通过消除单个故障点使Onion服务更具弹性和可靠性
- [Vanguards](https://github.com/mikeperry-tor/vanguards) - 用于在Onion 3版本防护并发现攻击缓解脚本（打算最终包含在Tor核心中）



## 传输层防护

Transport-layer defenses

- [Certbot](https://certbot.eff.org/) - 免费工具，用于通过配置各种Web和电子邮件服务器软件的插件，来自动从[LetsEncrypt Root CA](https://letsencrypt.org/)发行和更新TLS证书。
- [MITMEngine](https://github.com/cloudflare/mitmengine) - 一个Golang库，用于在服务器端检测TLS拦截事件
- [OpenVPN](https://openvpn.net/) - 一个开源的、基于SSL / TLS的虚拟专用网络（VPN）
- [Tor](https://torproject.org/) - 一个用于规避审查制度的匿名覆盖网络，提供分布式的，经过密码验证的域名服务（`.onion`域），用以增强发布者的隐私和服务可用性



## 基于macOS的防护

macOS-based defenses

- [BlockBlock](https://objective-see.com/products/blockblock.html) - 该工具可用监视常见的持久性位置，并在添加持久性组件时发出警报，这有助于检测和阻止恶意软件的安装
- [LuLu](https://objective-see.com/products/lulu.html) - 免费的macOS防火墙
- [Santa](https://github.com/google/santa) - 适用于macOS的二进制白名单/黑名单系统
- [Stronghold](https://github.com/alichtman/stronghold) - 用于在终端轻松配置macOS安全设置
- [macOS Fortress](https://github.com/essandess/macOS-Fortress) - 提供内核级、操作系统级和客户端级安全功能的自动配置，包括私有化代理和macOS的防病毒扫描。



## 基于Windows的防护

Windows-based defenses

另请参阅：[awesome-windows#security](https://github.com/Awesome-Windows/Awesome#security)和[awesome-windows-domain-hardening](https://github.com/PaulSec/awesome-windows-domain-hardening)。

- [HardenTools](https://github.com/securitywithoutborders/hardentools) - 一个可用于禁用许多危险的Windows功能的实用程序
- [NotRuler](https://github.com/sensepost/notruler) - 用于侦测尝试破坏Microsoft Exchange服务器的行为，并同时检测由[Ruler](https://github.com/sensepost/ruler)攻击工具使用的客户端规则和启用VBScript的表单
- [Sandboxie](https://www.sandboxie.com/) - 一个免费并且开放源代码的通用Windows应用程序沙箱工具
- [Sigcheck](https://docs.microsoft.com/en-us/sysinternals/downloads/sigcheck) - 该工具可根据Microsoft的[证书信任列表（CTL）](https://docs.microsoft.com/en-us/windows/desktop/SecCrypto/certificate-trust-list-overview)审核Windows主机的根证书存储
- [Sticky Keys Slayer](https://github.com/linuz/Sticky-Keys-Slayer) - 该工具用于从主机名列表建立Windows RDP会话，并扫描可访问性工具后门，并在发现后门时发出警报
- [Windows Secure Host Baseline](https://github.com/nsacyber/Windows-Secure-Host-Baseline) - 一种组策略对象，合规性检查和配置工具，提供了一种自动且灵活的方法来安全地部署和维护Windows 10的最新版本
- [WMI Monitor](https://github.com/realparisi/WMI_Monitor) - 该工具可将新创建的WMI使用者和进程记录到Windows应用程序事件日志中



## License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

本项工作在[知识共享（CC协议4.0）下](https://creativecommons.org/licenses/by/4.0/)进行。



## References

\[1] Terraform：简介，sparkdev，https://www.cnblogs.com/sparkdev/p/10052310.html

\[2] Internet 安全中心 (CIS) 基准, [Robert Mazzoli](https://github.com/robmazz)，https://docs.microsoft.com/zh-cn/microsoft-365/compliance/offering-cis-benchmark?view=o365-worldwide

\[3] 网络蜜罐系统是什么?, 课课家教育 , http://www.kokojia.com/article/24017.html

\[4] HowTo: Set a Warning Message (Banner) in SSH, [admin](https://www.shellhacks.com/author/admin/), https://www.shellhacks.com/setup-warning-message-banner-ssh/

\[5] 36氪首发 | 聚焦零信任安全，「虎符网络」完成近千万元天使轮融资, [真梓](https://36kr.com/user/11868707) , https://36kr.com/p/771205828523273

\[6] Fwknop：单包授权与端口试探工具, [周俊辉](https://cloud.tencent.com/developer/user/2638143), https://cloud.tencent.com/developer/article/1578194

\[7] Suricata IDS 入门 — 规则详解,  [al0ne](https://www.secpulse.com/newpage/author?author_id=6767) , https://www.secpulse.com/archives/71603.html

\[8] 渗透测试：数十款重要工具介绍,  [E安全](https://www.secrss.com/articles?author=E安全),  https://www.secrss.com/articles/2409

\[9] Vulnerability fatigue – why you need to get on top of patch management, https://orangecyberdefense.com/global/blog/threat/vulnerability-fatigue-why-you-need-to-get-on-top-of-patch-management/