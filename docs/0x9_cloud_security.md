---
title: ☁️云安全大合集
---



>   转载、改写自：[awesome-cloud-security](https://github.com/teamssix/awesome-cloud-security)

# 云安全资源

## 目录

[TOC]

## 云服务工具

### 辅助工具

#### 综合

-  [recon.cloud](https://recon.cloud/): 在线搜索目标网站下的云资产
-  [行云管家](https://www.cloudbility.com/): 在线多云管理平台
-  [trufflehog](https://github.com/trufflesecurity/trufflehog): AK 等敏感信息查找工具
-  [ScoutSuite](https://github.com/nccgroup/ScoutSuite): 多云基线扫描工具
-  [CloudSploit](https://github.com/aquasecurity/cloudsploit): 云安全态势管理工具
-  [Cartography](https://github.com/lyft/cartography): 基础设施关系绘制工具
-  [qiniuClient](https://github.com/willnewii/qiniuClient): 多云对象存储管理工具
-  [cloudfox](https://github.com/BishopFox/cloudfox): 云渗透信息收集工具
-  [cloud_enum](https://github.com/initstring/cloud_enum): 云服务资源枚举工具
-  [RiskScanner](https://github.com/riskscanner/riskscanner): 开源多云安全合规扫描平台
-  [Cloud-Bucket-Leak-Detection-Tools](https://github.com/UzJu/Cloud-Bucket-Leak-Detection-Tools): 多云对象存储扫描工具
-  [SkyArk](https://github.com/cyberark/SkyArk): 适用于 AWS 和 Azure 的扫描工具
-  [CloudBrute](https://github.com/0xsha/CloudBrute): 云上公开资产枚举
-  [cloudlist](https://github.com/projectdiscovery/cloudlist): 多云资产收集工具
-  [PurplePanda](https://github.com/carlospolop/PurplePanda): 权限升级路径分析工具
-  [Leonidas](https://github.com/WithSecureLabs/leonidas): 云上攻击模拟工具
-  [CloudExplorer Lite](https://github.com/CloudExplorer-Dev/CloudExplorer-Lite): 开源的轻量级云管平台
-  [RedCloudOS](https://github.com/RedTeamOperations/RedCloud-OS): 红队云操作系统
-  [cloud service enum](https://github.com/NotSoSecure/cloud-service-enum): 云服务枚举工具

#### AWS

-  [buckets.grayhatwarfare.com](https://buckets.grayhatwarfare.com/): 在线搜索公开的存储桶
-  [AWS 文档 GPT 工具](https://www.awsdocsgpt.com)
-  [AWS 官方 CLI 工具](https://github.com/aws/aws-cli)
-  [CloudMapper](https://github.com/duo-labs/cloudmapper): AWS 环境分析工具
-  [S3Scanner](https://github.com/sa7mon/S3Scanner): S3 策略扫描工具  
-  [Principal Mapper](https://github.com/nccgroup/PMapper): AWS IAM 权限枚举工具
-  [enumerate-iam](https://github.com/andresriancho/enumerate-iam): AWS IAM 权限枚举工具
-  [S3cret Scanner](https://github.com/Eilonh/s3crets_scanner): S3 公开存储桶密钥扫描工具
-  [YATAS](https://github.com/padok-team/yatas): AWS 常见配置错误审计工具
-  [findmytakeover](https://github.com/anirudhbiyani/findmytakeover): 检测多云环境中存在 dangling DNS 记录的工具
-  [Route53/CloudFront 漏洞评估工具](https://github.com/prevade/cloudjack)
-  [Cloudtrail2IAM](https://github.com/carlospolop/Cloudtrail2IAM): CloudTrail 日志分析 IAM 权限工具

#### Azure

-  [Azure 官方 CLI 工具](https://github.com/Azure/azure-cli)
-  [Azure MFA 检测工具](https://github.com/dafthack/MFASweep)
-  [AADInternals](https://github.com/Gerenios/AADInternals): Azure AD 和 Office 365 的 PowerShell 管理模块
-  [AzureHound](https://github.com/BloodHoundAD/AzureHound): BloodHound 收集 Azure 数据工具
-  [AzureGraph](https://github.com/JoelGMSec/AzureGraph): Azure AD 信息收集工具

#### GCP

-  [GCP 官方 CLI 工具](https://cloud.google.com/sdk/gcloud/)
-  [GCP 资源枚举工具](https://gitlab.com/gitlab-com/gl-security/threatmanagement/redteam/redteam-public/gcp_enum)
-  [GCP 攻击面资源枚举工具](https://gitlab.com/gitlab-com/gl-security/threatmanagement/redteam/redteam-public/gcp_firewall_enum)
-  [Hayat](https://github.com/DenizParlak/hayat): GCP 资源分析工具
-  [gcp-iam-collector](https://github.com/marcin-kolda/gcp-iam-collector): GCP IAM 权限收集工具
-  [Google Workspace Directory Dump Tool](https://github.com/RedTeamOperations/GoogleWorkspaceDirectoryDump): Google Workspace 目录转储工具

#### 阿里云

-  [阿里云官方 OSS 管理工具](https://github.com/aliyun/oss-browser)
-  [阿里云官方 CLI 工具](https://github.com/aliyun/aliyun-cli)

#### 腾讯云

-  [腾讯云轻量服务器管理工具](https://www.qqvps.com/d/1011)
-  [腾讯云官方 COS 辅助工具](https://cosbrowser.cloud.tencent.com/)
-  [腾讯云官方 CLI 工具](https://github.com/TencentCloud/tencentcloud-cli)

#### 华为云

-  [华为云 OBS 官方管理工具 OBS Browser+](https://support.huaweicloud.com/browsertg-obs/obs_03_1003.html)

#### 天翼云

-  [天翼云对象存储连接工具](https://www.ctyun.cn/document/10000101/10006768)

#### 青云

-  [青云官方 CLI 工具](https://docsv4.qingcloud.com/user_guide/development_docs/cli/install/install)



### 利用工具

#### 多云

-  [阿里云/腾讯云 AK 资源管理工具](https://github.com/wyzxxz/aksk_tool)
-  [Vajra](https://github.com/TROUBLE-1/Vajra): 支持 GUI 的 AWS、GCP 利用工具

#### AWS

-  [AWS 综合利用工具 pacu](https://github.com/RhinoSecurityLabs/pacu)
-  [AWS 渗透工具集 aws-pentest-tools](https://github.com/RhinoSecurityLabs/Security-Research/tree/master/tools/aws-pentest-tools)
-  [CredKing](https://github.com/ustayready/CredKing): AWS Lambda 密码喷洒工具
-  [awsKeyTools](https://github.com/Aabyss-Team/awsKeyTools): AWS AccessKey 泄漏利用工具
-  [Endgame](https://github.com/DavidDikker/endgame): AWS 渗透测试工具
-  [aws_consoler](https://github.com/NetSPI/aws_consoler): AWS 控制台接管利用工具
-  [Redboto](https://github.com/ihamburglar/Redboto): AWS 红队利用脚本
-  [CloudCopy](https://github.com/Static-Flow/CloudCopy): AWS 域控卷影拷贝工具

#### Azure

-  [MicroBurst](https://github.com/NetSPI/MicroBurst): Azure 安全评估 PowerShell 工具包
-  [Stormspotter](https://github.com/Azure/Stormspotter): Azure 红队利用工具
-  [ROADtools](https://github.com/dirkjanm/ROADtools): Azure AD 利用工具集
-  [TeamFiltration](https://github.com/Flangvik/TeamFiltration): 枚举、喷洒、渗透 O365 AAD 帐户工具
-  [TokenTactics](https://github.com/rvrsh3ll/TokenTactics): Azure JWT 令牌操作工具集
-  [DCToolbox](https://github.com/DanielChronlund/DCToolbox): Microsoft 365 安全工具箱
-  [Microsoft365_devicePhish](https://github.com/optiv/Microsoft365_devicePhish): 滥用 Microsoft 365 OAuth 授权流程进行网络钓鱼攻击的概念验证脚本
-  [aadcookiespoof](https://github.com/jsa2/aadcookiespoof): Azure AD 身份保护 Cookie 重放测试工具
-  [FuncoPop](https://github.com/NetSPI/FuncoPop): 用于攻击 Azure Function 应用程序的 PowerShell 工具

#### GCP

-  [GCP 利用工具集](https://gitlab.com/gitlab-com/gl-security/threatmanagement/redteam/redteam-public/gcp_misc)
-  [GCPBucketBrute](https://github.com/RhinoSecurityLabs/GCPBucketBrute): GCP Bucket 枚举工具
-  [GCP-IAM-Privilege-Escalation](https://github.com/RhinoSecurityLabs/GCP-IAM-Privilege-Escalation): GCP IAM 权限提升方法
-  [GCPTokenReuse](https://github.com/RedTeamOperations/): GCP Token 复用工具

#### Google Workspace

-  [Simple Workspace ATT&CK Tool - SWAT](https://github.com/elastic/SWAT)

#### 阿里云

-  [aliyun-accesskey-Tools](https://github.com/mrknow001/aliyun-accesskey-Tools): 阿里云 AccessKey 利用工具
-  [alicloud-tools](https://github.com/iiiusky/alicloud-tools): 阿里云 ECS、策略组辅助小工具
-  [AliyunAccessKeyTools](https://github.com/NS-Sp4ce/AliyunAccessKeyTools): 阿里云 AccessKey 泄漏利用工具

#### 腾讯云

-  [Tencent_Yun_tools](https://github.com/freeFV/Tencent_Yun_tools): 腾讯云 AccessKey 利用工具



## 云原生工具

### 辅助工具

#### 综合

-  [HummerRisk](https://github.com/HummerRisk/HummerRisk): 开源的云原生安全平台
-  [neuvector](https://github.com/neuvector/neuvector): 开源云原生安全防护平台

#### Docker

-  [contains](https://contains.dev/): 一个支持在线分析容器镜像的网站
-  [DIVE](https://github.com/wagoodman/dive): 容器镜像分析工具
-  [trivy](https://github.com/aquasecurity/trivy): 镜像扫描工具
-  [Clair](https://github.com/quay/clair): 容器镜像漏洞静态扫描工具
-  [Docker_Bench_Security](https://github.com/docker/docker-bench-security): 检查生产环境中部署容器的最佳实践
-  [sysdig](https://github.com/draios/sysdig): 原生支持容器的系统可见性工具
-  [Anchore](https://github.com/anchore/syft/): Docker 镜像扫描工具
-  [Dagda](https://github.com/eliasgranderubio/dagda/): Docker 静态分析工具
-  [container-escape-check](https://github.com/teamssix/container-escape-check): 容器逃逸检测工具

#### Kubernetes

-  [k9s](https://github.com/derailed/k9s): 基于终端 UI 的 k8s 集群管理工具
-  [Falco](https://github.com/falcosecurity/falco): k8s 异常活动检测工具
-  [kube bench](https://github.com/aquasecurity/kube-bench): CIS 基准检测工具
-  [kube hunter](https://github.com/aquasecurity/kube-hunter): k8s 集群安全漏洞发现工具
-  [KubiScan](https://github.com/cyberark/KubiScan): k8s 集群风险权限扫描工具
-  [StackRox](https://github.com/stackrox/stackrox): k8s 安全风险检测工具
-  [kubestriker](https://github.com/vchinnipilli/kubestriker): k8s 安全审计工具
-  [red kube](https://github.com/lightspin-tech/red-kube): 基于 kubectl 的红队 k8s 安全评估工具
-  [validkube](https://github.com/komodorio/validkube): k8s 调试辅助工具

#### Terraform

-  [Terraform 可视化](https://github.com/hieven/terraform-visual)


#### 利用工具

-  [CDK](https://github.com/cdk-team/CDK): 容器渗透工具集
-  [veinmind-tools](https://github.com/chaitin/veinmind-tools): 容器安全工具集
-  [Peirates](https://github.com/inguardians/peirates): k8s 渗透测试工具
-  [BOtB](https://github.com/brompwnie/botb): 容器渗透测试工具
-  [CCAT](https://github.com/RhinoSecurityLabs/ccat): 容器利用工具
