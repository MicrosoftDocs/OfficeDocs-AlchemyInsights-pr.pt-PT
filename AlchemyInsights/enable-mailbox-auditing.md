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
# <a name="enable-mailbox-auditing"></a>Permitir a auditoria da caixa de correio

Para ativar a auditoria da Caixa de Correio para um único utilizador ou para uma organização inteira, os seguintes cmdlets devem ser executados a partir de Remote Power Shell:
  
 **Utilizador Único**
  
Set-Mailbox -Identidade "Jane Dow" - AuditEnabled $true
  
 **Organização**
  
Get-Mailbox -ResultadoSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true
  
[Saiba mais](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  

