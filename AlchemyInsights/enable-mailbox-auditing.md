---
title: Permitir a auditoria da caixa de correio
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 19997b0a-394f-4943-8908-c601696a332c
ms.openlocfilehash: 2bcfb7cc174cd58b21e1bb0c82f0d7cdb25e2fdd
ms.sourcegitcommit: bc7d6f4f3c9f7060d073f5130e1ec856e248d020
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 06/02/2020
ms.locfileid: "44506965"
---
# <a name="enable-mailbox-auditing"></a>Permitir a auditoria da caixa de correio

Para ativar a auditoria da Caixa de Correio para um único utilizador ou para uma organização inteira, os seguintes cmdlets devem ser executados a partir de Remote Power Shell:
  
 **Utilizador Único**
  
Set-Mailbox -Identidade "Jane Dow" - AuditEnabled $true
  
 **Organização**
  
Get-Mailbox -ResultadoSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} Set-Mailbox -AuditEnabled $true
  
[Saiba mais](https://docs.microsoft.com/microsoft-365/compliance/enable-mailbox-auditing)
  

