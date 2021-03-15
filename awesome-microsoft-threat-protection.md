# Awesome Microsoft Threat Protection [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A curated list of awesome resources, repos, scripts, tools, queries and learning resouces about Microsoft Threat Protection. Inspired by Sindre Sorhus and his [awesome](https://github.com/sindresorhus/awesome) collection.

Imagine having visibility into threats across all your resources, AI that stitches signals together and tells you what’s most important, and the ability to respond proactively across your entire organisation. Microsoft Threat Protection is a suite of next-generation, cloud-delivered security services that enables you to proactively protect, detect and respond to emerging threats and risks that impact your business.

## Contents

- [Important Resources](#important-resources)
  - [Licensing](#licensing)
  - [Updates and Roadmaps](#updates-and-roadmaps)
- [Azure](#azure)
  - [Azure Active Directory](#azure-active-directory)
  - [Azure Defender for App Service](#azure-defender-for-app-service)
  - [Azure Defender for DNS](#azure-defender-for-dns)
  - [Azure Defender for Key Vault](#azure-defender-for-key-vault)
  - [Azure Defender for Kubernetes](#azure-defender-for-kubernetes)
  - [Azure Defender for Resource Manager](#azure-defender-for-resource-manager)
  - [Azure Defender for Servers](#azure-defender-for-servers)
  - [Azure Defender for SQL](#azure-defender-for-sql)
  - [Azure Defender for Storage](#azure-defender-for-storage)
  - [Azure Security Center](#azure-security-center)
  - [Azure Sentinel](#azure-sentinel)
- [Microsoft 365](#microsoft-365)
  - [Microsoft Cloud App Security](#microsoft-cloud-app-security)
  - [Microsoft Defender for Endpoint](#microsoft-defender-for-endpoint)
  - [Microsoft Defender for Identity](#microsoft-defender-for-identity)
  - [Microsoft Defender for Office](#microsoft-defender-for-office)
- [Threat Hunting](#threat-hunting)
  - [Getting Started](#getting-started)
  - [Kusto Query Language (KQL)](#kusto-query-language)
  - [Threat Hunting with Microsoft 365 Defender](#threat-hunting-with-microsoft-365-defender)

## Important Resources

#### Licensing

COMING SOON

#### Products by Region

It's important to understand which Microsoft Cloud Service is available within which Microsoft Region, as this may influence how you choose to use them.

- [Azure Data Centre Locations](https://azure.microsoft.com/en-gb/global-infrastructure/geographies/)
- [Azure Products by Region](https://azure.microsoft.com/en-us/global-infrastructure/services/)
- [Microsoft 365 International Availability](https://www.microsoft.com/en-gb/microsoft-365/business/international-availability)

#### Updates and Roadmaps

- [**Roadmap**: Microsoft 365](https://www.microsoft.com/en-gb/microsoft-365/roadmap?filters=)
- [**Roadmap**: Azure](https://azure.microsoft.com/en-us/updates/)
- [What's new in Azure Security Center?](https://docs.microsoft.com/en-gb/azure/security-center/release-notes)
- [What's new in Microsoft Cloud App Security?](https://docs.microsoft.com/en-us/cloud-app-security/release-notes)
- [What's new in Microsoft Defender for Endpoint?](https://docs.microsoft.com/en-us/windows/security/threat-protection/microsoft-defender-atp/whats-new-in-microsoft-defender-atp)
- [What's new in Defender for Identity](https://docs.microsoft.com/en-us/defender-for-identity/whats-new)
- [What's new in Microsoft Defender for Office](https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/whats-new-in-office-365-atp?view=o365-worldwide)

## Azure

This section focuses on the Microsoft Threat Protection services available on the Microsoft Azure platform.

#### Azure Active Directory

WORK IN PROGRESS

#### Azure Defender for App Service

- [Introduction to Azure Defender for App Service](https://docs.microsoft.com/en-gb/azure/security-center/defender-for-app-service-introduction) - Understand how to provide native threat protection for Azure App Service.

#### Azure Defender for DNS

- [Introduction to Azure Defender for DNS](https://docs.microsoft.com/en-gb/azure/security-center/defender-for-dns-introduction)

#### Azure Defender for Key Vault

- [Introduction to Azure Defender for Key Vault](https://docs.microsoft.com/en-gb/azure/security-center/defender-for-key-vault-introduction)

#### Azure Defender for Kubernetes

- [Introduction to Azure Defender for Kubernetes](https://docs.microsoft.com/en-gb/azure/security-center/defender-for-kubernetes-introduction)

#### Azure Defender for Resource Manager

- [Introduction to Azure Defender for Resource Manager](https://docs.microsoft.com/en-gb/azure/security-center/defender-for-resource-manager-introduction)

#### Azure Defender for Servers

- [Introduction to Azure Defender for Servers](https://docs.microsoft.com/en-gb/azure/security-center/defender-for-servers-introduction)

#### Azure Defender for SQL

- [Introduction to Azure Defender for SQL](https://docs.microsoft.com/en-gb/azure/security-center/defender-for-sql-introduction)

#### Azure Defender for Storage

- [Introduction to Azure Defender for Storage](https://docs.microsoft.com/en-gb/azure/security-center/defender-for-storage-introduction)

#### Azure Security Center

- [Introduction to Azure Security Center](https://docs.microsoft.com/en-gb/azure/security-center/security-center-introduction)
- [Readiness: Planning your Azure Security Center Roadmap](https://docs.microsoft.com/en-gb/azure/security-center/security-center-readiness-roadmap)
- [Webinars: Azure Security Center in the Field (#ASCinthefield)](https://www.youtube.com/hashtag/ascinthefield)

#### Azure Sentinel

WORK IN PROGRESS

## Microsoft 365

This section focuses on the Microsoft Threat Protection services available within the Microsoft 365 platform.

#### Microsoft Cloud App Security

- [What is Microsoft Cloud App Security?](https://docs.microsoft.com/en-us/cloud-app-security/what-is-cloud-app-security)
- [Microsoft Cloud App Security Getting Started Guide](https://docs.microsoft.com/en-us/cloud-app-security/getting-started-with-cloud-app-security)
- [Microsoft Cloud App Security Best Practices](https://docs.microsoft.com/en-us/cloud-app-security/best-practices)
- [Webinars: Microsoft Cloud App Security](https://docs.microsoft.com/en-us/cloud-app-security/webinars)

#### Microsoft Defender for Endpoint

- [What is Defender for Endpoint?](https://docs.microsoft.com/en-us/windows/security/threat-protection/microsoft-defender-atp/microsoft-defender-advanced-threat-protection)
- [Readiness: Planning your Microsoft Defender for Endpoint Deployment](https://docs.microsoft.com/en-us/windows/security/threat-protection/microsoft-defender-atp/deployment-strategy)
- [Defender for Endpoint Deployment Phases](https://docs.microsoft.com/en-us/windows/security/threat-protection/microsoft-defender-atp/deployment-phases)

#### Microsoft Defender for Identity

- [What is Microsoft Defender for Identity](https://docs.microsoft.com/en-us/defender-for-identity/what-is)
- [Defender for Identity Architecture](https://docs.microsoft.com/en-us/defender-for-identity/architecture)
- [Readiness: Planning your Defender for Identity roadmap](https://docs.microsoft.com/en-us/defender-for-identity/resources)

#### Microsoft Defender for Office

- [What is Microsoft Defender for Office?](https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/?view=o365-worldwide)
- [Readiness: Planning your Defender for Office Roadmap](https://docs.microsoft.com/en-us/microsoft-365/security/office-365-security/security-roadmap?view=o365-worldwide)

## Threat Hunting

#### Getting Started

COMING SOON

#### Kusto Query Language

COMING SOON

#### Threat Hunting with Microsoft 365 Defender

- [Microsoft 365 Defender Hunting Queries by Microsoft](https://github.com/microsoft/Microsoft-365-Defender-Hunting-Queries)
- [Kusto Query Language (KQL) queries for Advanced Hunting by Wortell](https://github.com/wortell/KQL)
- [Advanced Hunting by Jan Geisbauer](https://github.com/jangeisbauer/AdvancedHunting)
- [Microsoft Defender for Endpoint Queries by Elli Schlomo](https://github.com/eshlomo1/Microsoft-Defender-for-Endpoint-Queries)

#### Threat Hunting with Azure Sentinel

COMING SOON

## Communities

- [Tech Community: Azure Security Center](https://techcommunity.microsoft.com/t5/azure-security-center/bg-p/AzureSecurityCenterBlog)
- [Tech Community: Microsoft Cloud App Security](https://techcommunity.microsoft.com/t5/microsoft-cloud-app-security/bd-p/MicrosoftCloudAppSecurity)
- [Tech Community: Microsoft Defender for Endpoint](https://techcommunity.microsoft.com/t5/microsoft-defender-for-endpoint/bd-p/MicrosoftDefenderATP)
- [Tech Community: Defender for Identity](https://techcommunity.microsoft.com/t5/microsoft-defender-for-identity/bd-p/AzureAdvancedThreatProtection)
- [Tech Community: Microsoft Defender for Office](https://techcommunity.microsoft.com/t5/microsoft-defender-for-office/bd-p/MicrosoftDefenderforOffice365)

## Learning Resources

- [Become a Microsoft 365 Defender Ninja - October 2020](https://techcommunity.microsoft.com/t5/microsoft-365-defender/become-a-microsoft-365-defender-ninja/ba-p/1789376)
- [Become a Microsoft 365 Defender Ninja - January 2021 Update](<https://techcommunity.microsoft.com/t5/microsoft-365-defender/microsoft-365-defender-ninja-training-january-2021-update/ba-p/2103073>)
- [Tech Community: Microsoft 365 Defender](https://techcommunity.microsoft.com/t5/microsoft-365-defender/bd-p/MicrosoftThreatProtection)

#### Microsoft Threat Protection

- [**LEARN**: Introduction to threat protection with Microsoft 365](https://docs.microsoft.com/en-us/learn/modules/m365-security-threat-define/)
- [**LEARN**: Mitigate incidents using Microsoft 365 Defender](https://docs.microsoft.com/en-gb/learn/modules/mitigate-incidents-microsoft-365-defender/)

#### Azure Active Directory

- [**LEARN**: Protect your identities with Azure AD Identity Protection](https://docs.microsoft.com/en-gb/learn/modules/protect-identities-with-aad-idp/)

#### Azure Defender

- [**LEARN**: Plan for cloud workload protections using Azure Defender](https://docs.microsoft.com/en-gb/learn/modules/what-is-azure-defender/)
- [**LEARN**: Explain cloud workload protections in Azure Defender](https://docs.microsoft.com/en-gb/learn/modules/understand-azure-defender-cloud-workload-protection/)
- [**LEARN**: Connect Azure assets to Azure Defender](https://docs.microsoft.com/en-gb/learn/modules/connect-azure-assets-to-azure-defender/)
- [**LEARN**: Connect non-Azure resources to Azure Defender](https://docs.microsoft.com/en-gb/learn/modules/connect-non-azure-machines-to-azure-defender/)
- [**LEARN**: Remediate security alerts using Azure Defender](https://docs.microsoft.com/en-gb/learn/modules/remediate-azure-defender-security-alerts/)

#### Azure Security Center

COMING SOON

#### Azure Sentinel

COMING SOON

#### Microsoft Cloud App Security

- [**LEARN**: Secure your cloud apps and services with Microsoft Cloud App Security](https://docs.microsoft.com/en-us/learn/modules/microsoft-cloud-app-security/)
- [**LEARN**: Respond to data loss prevention alerts using Microsoft 365](https://docs.microsoft.com/en-gb/learn/modules/respond-to-data-loss-prevention-alerts-microsoft-365/)

#### Microsoft Defender for Endpoint

- [**LEARN**: Protect against threats with Microsoft Defender for Endpoint](https://docs.microsoft.com/en-us/learn/modules/m365-security-threat-protect/)
- [**LEARN**: Deploy the Microsoft Defender for Endpoint Environment](https://docs.microsoft.com/en-gb/learn/modules/deploy-microsoft-defender-for-endpoints-environment/)
- [**LEARN**: Implement Windows 10 security enhancements with Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/implement-windows-10-security-enhancements-with-microsoft-defender-for-endpoint/)
- [**LEARN**: Manage alerts and incidents in Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/manage-alerts-incidents-microsoft-defender-for-endpoints/)
- [**LEARN**: Perform device investigations in Microsoft Defender for Endpoint](<https://docs.microsoft.com/en-gb/learn/modules/perform-device-investigations-microsoft-defender-for-endpoints/>)
- [**LEARN**: Perform actions on a device using Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/perform-actions-device-microsoft-defender-for-endpoint/)
- [**LEARN**: Perform evidence and entities investigations using Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/perform-evidence-entities-investigations-microsoft-defender-for-endpoint/)
- [**LEARN**: Configure and manage automation using Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/configure-manage-automation-microsoft-defender-for-endpoint/)
- [**LEARN**: Configure for alerts and detections in Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/configure-settings-for-alerts-detections-microsoft-defender-for-endpoint/)
- [**LEARN**: Utilize Threat and Vulnerability Management in Microsoft Defender for Endpoint](https://docs.microsoft.com/en-gb/learn/modules/use-threat-vulnerability-management-microsoft-defender-for-endpoint/)

#### Microsoft Defender for Identity

- [**LEARN**: Safeguard your environment with Microsoft Defender for Identity](https://docs.microsoft.com/en-us/learn/modules/m365-threat-safeguard/)
- [**LEARN**: Manage insider risk in Microsoft 365](https://docs.microsoft.com/en-us/learn/modules/m365-compliance-insider-manage-insider-risk/)

#### Microsoft Defender for Office

- [**LEARN**: Remediate risks with Microsoft Defender for Office 365](https://docs.microsoft.com/en-us/learn/modules/m365-threat-remediate/)
