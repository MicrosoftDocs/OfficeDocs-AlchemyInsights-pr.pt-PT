---
title: Ligue a auditoria da caixa de correio
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 02/26/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3100005"
- "7327"
ms.openlocfilehash: aa0ff925ae891d28e31394ec66eb17c2d9710008
ms.sourcegitcommit: 251e2e82571fb3bb1fbe3dbf7bfca30e004b3373
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 03/05/2021
ms.locfileid: "50483550"
---
# <a name="turn-on-mailbox-auditing"></a>Ligue a auditoria da caixa de correio

Para ativar a auditoria da caixa de correio para um único utilizador ou para uma organização inteira, executar os seguintes cmdlets a partir de Remote PowerShell:

- **Utilizador único**: Set-Mailbox -Identidade "Jane Dow" -AuditEnabled $true
- **Organização**: Get-Mailbox -ResultadoSize Unlimited -Filter {RecipientTypeDetails -eq "UserMailbox"} | Set-Mailbox -AuditEnabled $true

Para saber mais, consulte [Gerir a auditoria da caixa de correio.](https://go.microsoft.com/fwlink/?linkid=2103668)