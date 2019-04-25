---
title: Restringir SharePoint Online para o modo clássico
ms.author: kirks
author: Techwriter40
ms.date: 3/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 6e99da1c-e61d-40ba-855e-1a8f346e42fd
ms.openlocfilehash: c51e48fe5694f964aef74c2973f774b44415ebb8
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/23/2019
ms.locfileid: "32422186"
---
# <a name="restrict-sharepoint-online-to-classic-mode"></a><span data-ttu-id="69381-102">Restringir SharePoint Online para o modo clássico</span><span class="sxs-lookup"><span data-stu-id="69381-102">Restrict SharePoint Online to classic mode</span></span>

<span data-ttu-id="69381-103">Algumas organizações necessitam da experiência de modo clássico.</span><span class="sxs-lookup"><span data-stu-id="69381-103">Some organizations still require the Classic mode experience.</span></span> <span data-ttu-id="69381-104">Enquanto não existem planos para remover de modo clássico a um nível granular, início de Abril de 1,2019, já não será possível restringir a toda uma organização (tenant) para o modo clássico para listas e bibliotecas.</span><span class="sxs-lookup"><span data-stu-id="69381-104">While there are no plans to remove classic mode at a granular level, starting April 1,2019, it will no longer be possible to restrict an entire organization (tenant) to classic mode for lists and libraries.</span></span>

<span data-ttu-id="69381-105">O administrador terá as seguintes opções para gerir listas e bibliotecas na utilizando parâmetros de cancelamento granulares que fornecemos aos seguintes níveis de modo clássico individuais:</span><span class="sxs-lookup"><span data-stu-id="69381-105">The admin will have the following options to manage individual lists and libraries in classic mode using granular opt-out switches that we provide at the following levels:</span></span>

- <span data-ttu-id="69381-106">colecção de sites</span><span class="sxs-lookup"><span data-stu-id="69381-106">site collection</span></span>
- <span data-ttu-id="69381-107">site</span><span class="sxs-lookup"><span data-stu-id="69381-107">site</span></span>
- <span data-ttu-id="69381-108">lista</span><span class="sxs-lookup"><span data-stu-id="69381-108">list</span></span>
- <span data-ttu-id="69381-109">biblioteca</span><span class="sxs-lookup"><span data-stu-id="69381-109">library</span></span>

<span data-ttu-id="69381-110">Além disso, listas utilizam determinadas funcionalidades e personalizações que não são suportadas pelo moderno serão ainda ser mudadas automaticamente para o modo clássico.</span><span class="sxs-lookup"><span data-stu-id="69381-110">Additionally, lists that use certain features and customizations that are not supported by modern will still be automatically switched to classic mode.</span></span>

<span data-ttu-id="69381-111">Depois de 1 de Abril, listas e bibliotecas que se encontram no modo clássico na sequência de Tenants opt-out serão automaticamente geridas a nível de site e o nível da lista.</span><span class="sxs-lookup"><span data-stu-id="69381-111">After April 1, lists and libraries that are in classic mode as a result of tenant opt-out will automatically be managed at the site level and list level.</span></span>

<span data-ttu-id="69381-112">Se necessitar de modo clássico aqui mais informações, consulte e PnP Powershell instrução aqui que descreve as opções e ferramentas pode utilizar hoje para preparar a remoção do inquilino nível activamente em 1 de Abril.</span><span class="sxs-lookup"><span data-stu-id="69381-112">If you require classic mode please see more information here and PnP Powershell instruction here that describes options and tools you can use today to prepare for the removal of the tenant level opt-out on April 1.</span></span>
