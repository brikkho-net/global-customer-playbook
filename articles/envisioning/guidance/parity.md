<properties
	pageTitle="Global Customer Playbook envisioning-guidance-parity"
	description="Global Customer Playbook envisioning-guidance-parity"
	services="global-customer-playbook"
	documentationCenter=""
	authors="jtong"
	manager="edwinc"
	editor=""
	tags="global-customer-playbook"/>

<tags
	ms.service="migration-lifecycle-envisioning"
	ms.workload=""
	ms.tgt_pltfrm=""
	ms.devlang="na"
	ms.topic="article"
	ms.date="11/21/2016"
	wacn.date="11/21/2016"
	wacn.lang="en"
	ms.author="jtong"/>


# Envisioning Guidance - Parity

[AZURE.INCLUDE [header](../envisioning-guidance.md)]

## Global Azure and China Azure Services Asymmetry

China Azure, or Mooncake, is a separate instance of Azure operated by 21Vianet. There are differences in the availability of Azure services, compared to that of Global Azure.
 
Below is a summary table based on service parity, essentially comparing Global Azure to Mooncake (Note: if there is difference, it is highlighted in yellow).
 
It should be noted that new services are still being launched. The following table is the information updated as of the end of Sep 2016. You should always refer to the latest services offered in Mooncake at www.azure.cn.

Service Category | Services | Global Azure (WW) | Mooncake (via 21vianet)
---------------- | ---------------- | ---------------- | ----------------
**Compute** | Virtual Machines | A series Basic, A series Standard, D series, <mark>DS series</mark>, Dv2 series, <mark>DSv2 series</mark>, F series, <mark>G series, N series, H series, A8 & A9 network optimized, A10 & A11 compute optimized</mark> | A series Basic, A series Standard, D series, Dv2 series, F series 
  | Virtual Machine Scale Sets | ditto | ditto
  | Cloud Services | A series Basic, A series Standard, D series Basic, Dv2 series, <mark>A8 & A9 network optimized, A10 & A11 compute optimized</mark> | A series Basic, A series Standard, D series Basic, Dv2 series
  | Batch | GA | GA
  | Service Fabric | GA| GA
  | Service Fabric for Linux | <mark>Preview</mark> | GA
  | Functions | <mark>Preview</mark> | NA
  | Azure Container Service | <mark>GA</mark> | NA
  | Azure Container Registry | <mark>Preview</mark> | NA
**Storage** | Storage (Blob, File, Table, Queue) | Standard Storage, Premium Storage (available in some regions), Cool/Hot | Standard Storage, Premium Storage, Cool/Hot
 | Data Lake Store | <mark>GA</mark> | NA
 | StorSimple | StorSimple 5000, StorSimple 7000, <mark>StorSimple 8000</mark> | StorSimple 5000, StorSimple 7000
 | Backup | File Backup, IaaS VM Backup | File Backup, IaaS VM Backup
 | Site Recovery | GA, On-premise VMM to Azure, On-premise Hyper-V to Azure, <mark>On-premise VMware/Physical server to Azure (Preview), Between two on-premise VMware Sites, Protect SQL Server(Preview)</mark> | GA, On-premise VMM to Azure, On-premise Hyper-V to Azure
**Networking** | Virtual Networks | Static/Dynamic Routing VPN Gateway, Standard VPN Gateway, High Performance VPN Gateway, Application Gateway | Static/Dynamic Routing VPN Gateway, Standard VPN Gateway, High Performance VPN Gateway, Application Gateway
 | ExpressRoute | Provide the following port speed : 50 Mbp, 100 Mbp, 200 Mbp, 500 Mbp, 1 Gbp, 2 Gbp, 5 Gbp, 10 Gbp | Provide the following port speed : 50 Mbp, 100 Mbp, 200 Mbp, 500 Mbp, 1 Gbp, 2 Gbp, 5 Gbp, 10 Gbp
 | DNS | <mark>Preview</mark> | NA
 | Traffic Manager | GA | GA
 | Load Balancer | GA | GA
**Web & Mobile** | App Service | Free, Shared(Preview), Basic, Standard, Premium(Preview) | Free, Shared(Preview), Basic, Standard, Premium(Preview).  <mark>Only followings available: Web Apps, Mobile Apps, API Apps</mark>
 | Mobile Engagement | <mark>GA</mark> | NA
 | Azure Search | <mark>Free, Basic, Standard S1 ,Standard S2, Standard S3 (Preview)</mark> | NA
**Databases** | SQL Database | Single database, Elastic database (Preview) | Single database, Elastic database (Preview)
 | SQL Data Warehouse | <mark>GA</mark> | Preview
 | SQL Server Stretch Database | <mark>GA</mark> | Preview
 | Redis Cache | Basic, Standard, Premium | Basic, Standard, Premium
 | DocumentDB | GA | GA
 | MySQL Database on Azure | NA | <mark>MS1, MS2, MS3, MS4, MS5, MS6</mark>
**Intelligence + Analytics** | Cortana Intelligence | <mark>GA</mark> | NA
 | Cognitive Services | Preview | Preview
 | HDInsight | HDInsight General Purpose Node, HDInsight Optimized Node, <mark>HDInsight on Linux, A10 & A11 Compute Intensive Node</mark> | HDInsight General Purpose Node, HDInsight Optimized Node
 | Machine Learning | <mark>Free, Standard</mark> | NA
 | Stream Analytics | GA | GA
 | Data Factory | <mark>Low Frequency, High Frequency</mark> | NA
 | Data Catalog | <mark>Free, Standard</mark> | NA
 | Data Lake Store | <mark>GA</mark> | NA
 | Data Lake Analytics | <mark>GA</mark> | NA
 | Power BI Embedded | <mark>GA</mark> | NA
**IoT** | Events Hub | Basic, Standard | Basic, Standard
 | IoT Hub | GA | GA
 | IoT Suite | GA | GA
 | Stream Analytics | GA | GA
 | Notification Hubs | Free, Basic, Standard | Free, Basic, Standard
**Media & CDN** | Media Services | Encoding, Indexing, Streaming, DRM <mark>(support multi-DRM : PlayReady, Widevine, and FairPlay Streaming)</mark> | Encoding, Indexing, Streaming, DRM 
 | CDN | Provided by <mark>EdgeCast</mark> | Provided by <mark>local CDN</mark> provider
**Enterprise Integration** | BizTalk Services | <mark>Free, Developer, Basic, Standard, Premium</mark> | NA
 | Service Bus | Basic, Standard, <mark>Premium</mark> | Basic, Standard
 | API Management | <mark>Developer, Standard, Premium</mark> | MVP Preview
 | Logic Apps | <mark>GA</mark> | NA
**Security & Identity** | Azure Active Directory | Free, <mark>Basic, Premium</mark> | Free (Self Service Password Reset is available)
 | Azure Active Directory B2C | <mark>GA</mark> | NA
 | Azure AD Domain Services | <mark>GA</mark> | NA
 | Multi-factor Authentication | GA | GA
 | Key Vault |	Standard, Premium | Standard, Premium 
 | Security Centre | <mark>Free, Standard</mark> | NA
**Developer Tools** | Visual Studio Team Services | <mark>Basic, Professional, Advanced</mark> | NA
 | Application Insights | <mark>Free, Basic, Enterprise</mark> | NA
 | DevTest Labs | <mark>Free</mark> | NA
 | HockeyApp | <mark>GA</mark> | NA
**Monitoring & Management** | Azure Portal | GA | Preview
 | Azure Resource Manager | GA | GA
 | Marketplace | <mark>GA</mark> | Preview
 | Scheduler | Free, Standard, Premium | Free, Standard, Premium
 | Automation | Free, Basic, <mark>Desired State Configuration (DSC)</mark> | Free, Basic
 | Operational Insights | <mark>Free, Standard, Premium</mark> | NA
 | Log Analytics | <mark>Free, Standard, Premium</mark> | NA
 
![navigation](/solutions/global-customer/media/navigation.png)

Let's move to the next section - [Performance](/solutions/global-customer/envisioning/guidance/performance/) .
