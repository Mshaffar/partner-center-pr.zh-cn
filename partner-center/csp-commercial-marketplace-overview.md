---
title: 概述-CSP marketplace
ms.topic: article
ms.date: 05/05/2020
ms.service: partner-dashboard
ms.subservice: partnercenter-csp
description: 了解如何在 marketplace 中向客户的独立软件供应商（Isv）销售 "软件即服务" （SaaS）产品/服务。
author: LauraBrenner
ms.author: labrenne
keywords: 订阅，Marketplace，第三方，ISV，SaaS，许可证
ms.localizationpriority: medium
ms.custom: SEOMAY.20
ms.openlocfilehash: c9366bfc9dc09d7c62fcf01cacf30944b8801550
ms.sourcegitcommit: e9b627159745bcce53a8c2b1676f63f5249bba76
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 05/07/2020
ms.locfileid: "82908094"
---
# <a name="overview-of-the-commercial-marketplace-in-partner-center"></a>合作伙伴中心的商业市场概述

**适用于**

- 合作伙伴中心
- 云解决方案提供商计划中的合作伙伴

作为云解决方案提供商（CSP）计划中的合作伙伴，你可以将 Microsoft 产品与第三方独立软件供应商（Isv）发布的解决方案进行捆绑和销售。 以这种方式捆绑解决方案使您能够更好地为最终客户提供服务并发展您的 CSP 服务业务。

作为 CSP 计划中的合作伙伴，你可以使用合作伙伴中心从 Microsoft 的商业 marketplace 购买许多 ISV 解决方案。 这为你和你的客户提供了几个主要优势：

- 对为 Microsoft 技术和环境优化的软件解决方案目录的访问权限。
- 简化的合同和缩短的采购周期。
- 单个与合作伙伴中心 Api 的集成。 （此类集成使你可以访问 ISV 解决方案的目录，降低运营和工程的成本，并通过单个提供商简化多个供应商订阅和计费的管理。）
- 在客户的 Azure 租户中简化部署和预配（适用于基于虚拟机的解决方案）。
- 通过直接 ISV 购买或签约、Microsoft 解决方案配置和集成，以及管理或合并来自多个供应商的重复发票，减少了潜在的挑战。

## <a name="overview-of-csp-offers-in-the-commercial-marketplace"></a>商业应用商店中的 CSP 产品概述

如果你是 CSP 计划中的合作伙伴，你可能想要执行许多适用于 ISV 产品/服务的商业市场活动。 请参阅下表以了解有关每个活动的详细信息。

|**如果要**  |**读取**   |
|:------------------------------------|:------------------|
|了解如何查看或搜索可用产品/服务、定价、产品详细信息或发布者联系信息 | [发现产品](csp-commercial-marketplace-discover.md) | 
|了解如何购买和部署产品/服务   | [购买优惠](csp-commercial-marketplace-purchase.md)   | 
|了解如何取消或续订订阅或添加或删除座位  | [管理套餐](csp-commercial-marketplace-manage.md) |
|了解计费如何适用于商业 marketplace 购买 | [了解帐单](csp-commercial-marketplace-billing.md) |
|了解谁负责 ISV 购买哪些类型的支持 | [了解支持](csp-commercial-marketplace-support.md) |
|了解有关商业应用商店中 CSP 合作伙伴和 Isv 的合同和责任 | [了解合同](csp-commercial-marketplace-contracting.md) |

> [!NOTE]
> 本概述介绍了 CSP 计划中的合作伙伴如何使用合作伙伴中心的某些商业 marketplace 功能。 与 CSP 计划中的合作伙伴相比，ISV 发布者具有不同的 marketplace 角色。 它们还在合作伙伴中心提供不同的商业 Marketplace 功能。 若要了解有关 ISV 发布者角色的详细信息，请参阅[Azure 商业市场概述](https://docs.microsoft.com/azure/marketplace/partner-center-portal/commercial-marketplace-overview)。

## <a name="where-to-complete-commercial-marketplace-activities"></a>完成商业市场活动的位置

作为 CSP 计划中的合作伙伴，你可以直接从合作伙伴中心[仪表板](https://partner.microsoft.com/dashboard)或使用[合作伙伴中心 api](https://docs.microsoft.com/partner-center/develop/)完成多个适用于 ISV SaaS 产品/服务的商业市场活动。 但是，若要完成其他 marketplace 活动，你可能需要执行以下操作：

- [Microsoft Azure 管理门户](https://portal.azure.com/)

    或

- 第三方 ISV 发布者的系统或网站

在其中，你可以从你选择的产品/服务的类型着手完成活动。 CSP 计划中的合作伙伴当前可以通过第三方 ISV 发布者来处理两种类型的产品/服务：

1. 基于许可证的 SaaS 产品  
2. 基于使用情况的产品/服务（包括基于虚拟机、容器或 Azure 应用程序的产品/服务）

请参阅[计费基础知识](billing-basics.md)，详细了解基于许可证的产品/服务和基于使用情况的产品/服务的计费方式有所不同。  

若要了解在何处完成基于许可证或基于使用的 ISV 产品/服务的特定市场活动，请参阅下表。

|**适用于基于许可证的 SaaS 提供商**  |**用法**  |
|:------------------------------------|:------------------|
|发现或搜索可用的产品/服务  | 合作伙伴中心仪表板或合作伙伴中心 Api  |
|购买产品/服务  | 合作伙伴中心仪表板或合作伙伴中心 Api  |
|部署购买的产品/服务（帐户设置、软件管理或客户的 AAD 租户中的部署）  | ISV 发布者的系统或网站  |
|取消/续订提议订阅或添加/删除座位 | 合作伙伴中心仪表板或合作伙伴中心 Api  |
|创建用户或管理权限  | ISV 发布者的系统或网站  |

|**基于使用情况的 Isv 提供的产品/服务**  |**用法**  |
|:------------------------------------|:------------------|
|发现或搜索可用的产品/服务  | 合作伙伴中心仪表板、合作伙伴中心 Api 或 Azure 门户  |
|购买产品/服务  | Azure 门户  |
|部署购买的产品/服务（帐户设置、软件管理或客户的 AAD 租户中的部署）  | Azure 门户  |
|取消/续订提议订阅或添加/删除座位 | Azure 门户  |
|创建用户或管理权限  | Azure 门户  |

## <a name="next-steps"></a>后续步骤

- [发现或查看商业市场优惠](csp-commercial-marketplace-discover.md)
- [购买商业市场优惠](csp-commercial-marketplace-purchase.md)