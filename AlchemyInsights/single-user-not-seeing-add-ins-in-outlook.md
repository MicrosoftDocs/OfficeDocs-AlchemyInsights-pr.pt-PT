---
title: Único utilizador que não vê add-ins no Outlook
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/16/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom: ''
ms.openlocfilehash: 1f547c3f593b3256bd44f518aacbc36ed1c4c848
ms.sourcegitcommit: a05276bd623466ad211e1f8d9f0c616672dd3640
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 07/16/2020
ms.locfileid: "45198216"
---
# <a name="single-user-not-seeing-add-ins-in-outlook"></a><span data-ttu-id="eaa73-102">Único utilizador que não vê add-ins no Outlook</span><span class="sxs-lookup"><span data-stu-id="eaa73-102">Single user not seeing add-ins in Outlook</span></span>

<span data-ttu-id="eaa73-103">O utilizador pode fazer parte de uma função que não tem o parâmetro AppsForOfficeEnabled correto.</span><span class="sxs-lookup"><span data-stu-id="eaa73-103">The user might be part of a role that doesn’t have the correct AppsForOfficeEnabled parameter.</span></span> <span data-ttu-id="eaa73-104">Executar este cmdlet para saber se a função correta está associada ao utilizador:</span><span class="sxs-lookup"><span data-stu-id="eaa73-104">Run this cmdlet to find out if the correct role is associated with the user:</span></span>

<span data-ttu-id="eaa73-105">Get-ManagementRoleAssignment -RoleAssignee user@domain.com -Delegating $false [ Formato-Tabela - Função Automática,RoleAssigneeName,RoleAssigneeType</span><span class="sxs-lookup"><span data-stu-id="eaa73-105">Get-ManagementRoleAssignment -RoleAssignee user@domain.com -Delegating $false | Format-Table -Auto Role,RoleAssigneeName,RoleAssigneeType</span></span>

<span data-ttu-id="eaa73-106">Para obter mais informações, consulte [Especificar os administradores e utilizadores que podem instalar e gerir os add-ins para o Outlook](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/add-ins-for-outlook/specify-who-can-install-and-manage-add-ins).</span><span class="sxs-lookup"><span data-stu-id="eaa73-106">For more info, see [Specify the administrators and users who can install and manage add-ins for Outlook](https://docs.microsoft.com/exchange/clients-and-mobile-in-exchange-online/add-ins-for-outlook/specify-who-can-install-and-manage-add-ins).</span></span>
