---
title: AgregadoGroupMailbox full NDR recebido por e-mail enviado para o grupo Microsoft 365
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/18/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004286"
- "7656"
ms.openlocfilehash: 9de09ab4cbd2f09648305b11da6273ed990907cf
ms.sourcegitcommit: 2ffdf6096de5608b117c6677d3cd7dd4c23ea024
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 12/18/2020
ms.locfileid: "49722083"
---
# <a name="aggregategroupmailbox-full-ndr-received-for-email-sent-to-microsoft-365-group"></a>AgregadoGroupMailbox full NDR recebido por e-mail enviado para o grupo Microsoft 365

Utilize o seguinte comando EXO Shell para criar uma regra de transporte de intercâmbio para deixar cair silenciosamente os e-mails enviados para a caixa de correio de grupo agregada:

`New-TransportRule -SentTo @("AggregateGroupMailbox.A.201708181918@contoso.onmicrosoft.com") -DeleteMessage:$true -Name 'Agg1' -StopRuleProcessing:$false -Mode 'Enforce' -Comments '' -RuleErrorAction 'Ignore' -SenderAddressLocation 'Header'`

> [!NOTE]
> Substitua o endereço SMTP em **-SentTo** por endereço SMTP da caixa de correio de grupo agregada no seu inquilino. Pode obter o endereço SMTP da caixa de correio de grupo agregada da NDR recebida.



