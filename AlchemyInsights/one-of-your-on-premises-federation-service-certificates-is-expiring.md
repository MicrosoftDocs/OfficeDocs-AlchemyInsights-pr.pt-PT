---
title: Um dos seus certificados de serviço da Federação está expirando
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
ms.assetid: 172084b7-68a1-42a5-944d-2e871eaa2972
ms.openlocfilehash: 45a679e83aa8f07d65d2e7e84d7eb2a2b5a721e8
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/15/2021
ms.locfileid: "51810063"
---
# <a name="one-of-your-on-premises-federation-service-certificates-is-expiring"></a>Um dos seus certificados de serviço da Federação está expirando

Para resolver esta questão, siga estes passos:
  
- Instale o Módulo de Diretório Ativo Microsoft Azure para o Windows PowerShell no computador (se o módulo ainda não estiver instalado). Para isso, vá ao [Azure Ative Directory PowerShell para o Graph ](https://docs.microsoft.com/powershell/azure/active-directory/install-adv2?view=azureadps-2.0)
    
- Siga os passos na secção "Cenário 1: O certificado de assinatura de fichas AD FS expirou" da secção ["Houve um problema de acesso ao site" de AD FS quando um utilizador federado assina a Microsoft 365, Azure ou Intune.](https://support.microsoft.com/help/2713898/there-was-a-problem-accessing-the-site-error-from-ad-fs-when-a-federat)
    
- Siga os passos em [Como atualizar ou reparar as definições de um domínio federado na Microsoft 365, Azure ou Intune](https://support.microsoft.com/help/2647048/how-to-update-or-repair-the-settings-of-a-federated-domain-in-office-3).
    
Para obter mais informações sobre a renovação dos certificados da Federação, consulte [a renovação do Certificado para O365 e AZure AD](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-o365-certs).
  

