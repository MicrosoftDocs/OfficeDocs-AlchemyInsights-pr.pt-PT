---
title: Permitir a auditoria da caixa de correio
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: c04f27edc1e22e0e4269758827d5468767967be8
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/15/2021
ms.locfileid: "51814203"
---
# <a name="enable-mailbox-auditing"></a><span data-ttu-id="f4adb-102">Permitir a auditoria da caixa de correio</span><span class="sxs-lookup"><span data-stu-id="f4adb-102">Enable mailbox auditing</span></span>

<span data-ttu-id="f4adb-103">Para ativar a auditoria da Caixa de Correio para um único utilizador ou para uma organização inteira, os seguintes cmdlets devem ser executados a partir de Remote Power Shell:</span><span class="sxs-lookup"><span data-stu-id="f4adb-103">To enable Mailbox Auditing for either a single user or an entire organization the following cmdlets must be run from Remote Power Shell:</span></span>
  
 <span data-ttu-id="f4adb-104">**Utilizador Único**</span><span class="sxs-lookup"><span data-stu-id="f4adb-104">**Single User**</span></span>
  
<span data-ttu-id="f4adb-105">Set-Mailbox -Identidade "Jane Dow" - AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="f4adb-105">Set-Mailbox -Identity "Jane Dow" -AuditEnabled $true</span></span>
  
 <span data-ttu-id="f4adb-106">**Organização**</span><span class="sxs-lookup"><span data-stu-id="f4adb-106">**Organization**</span></span>
  
<span data-ttu-id="f4adb-107">Get-Mailbox -ResultadoSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span><span class="sxs-lookup"><span data-stu-id="f4adb-107">Get-Mailbox -ResultSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true</span></span>
  
[<span data-ttu-id="f4adb-108">Saiba mais</span><span class="sxs-lookup"><span data-stu-id="f4adb-108">Learn more</span></span>](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  

