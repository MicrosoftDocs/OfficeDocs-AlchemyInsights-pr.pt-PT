---
title: Anti-paspam - 5.7.23
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3156"
- "9001196"
ms.openlocfilehash: e494e8017f24d65a94d1a7490be4d67c46a2120b
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/15/2021
ms.locfileid: "51821422"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a>Corrija os problemas de entrega de e-mail para código de erro 5.7.23

Verifique o registo de DNS SPF para o seu domínio num verificador de registo SPF ou DNS disponível publicamente na web.

Verifique se a mensagem de saída não foi identificada como spam pela Microsoft e encaminhada através do [Pool de Entrega de Alto Risco](https://docs.microsoft.com/microsoft-365/security/office-365-security/high-risk-delivery-pool-for-outbound-messages). As mensagens no Pool de Entrega de Alto Risco não passarão cheques SPF, pelo que não serão aceites pela organização de email de destino.

Se o problema persistir, poderá ter de contactar o administrador do anfitrião do correio para o qual está a tentar enviar e-mail. Tome nota do erro externo detalhado disponível na mensagem de ressalto. O suporte da Microsoft pode não ser capaz de ajudar mais.
