---
title: 726 Encaminhamento de e-mail de bloqueio
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "726"
- "1200004"
ms.assetid: 8865c68e-7e8a-4135-a254-d7f69f1ded30
ms.openlocfilehash: 2f3528375d251542fd82761d00c776706de2e23c
ms.sourcegitcommit: f7b82f75a5400e992ecbd48a666783354e2e2871
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 10/15/2020
ms.locfileid: "48473112"
---
# <a name="blocking-or-unblocking-email-forwarding"></a><span data-ttu-id="6f387-102">Bloquear ou desbloquear o reencaminhamento de e-mails</span><span class="sxs-lookup"><span data-stu-id="6f387-102">Blocking or unblocking email forwarding</span></span>

<span data-ttu-id="6f387-103">Para ativar ou desativar o reencaminhamento de e-mails para uma caixa de correio específica, consulte o [reencaminhamento de e-mail Configure](https://docs.microsoft.com/microsoft-365/admin/email/configure-email-forwarding).</span><span class="sxs-lookup"><span data-stu-id="6f387-103">To enable or disable email forwarding for a specific mailbox, see [Configure email forwarding](https://docs.microsoft.com/microsoft-365/admin/email/configure-email-forwarding).</span></span>

<span data-ttu-id="6f387-104">Ao nível dos inquilinos, o controlo do encaminhamento externo é feito utilizando a política de spam de saída.</span><span class="sxs-lookup"><span data-stu-id="6f387-104">On the tenant level, control of external forwarding is done using the outbound spam policy.</span></span> <span data-ttu-id="6f387-105">Pode consultar a política de filtro de spam de saída do Security and Compliance Center [aqui] ( https://protection.office.com/antispam) ou utilizando o comando [Get-HostedOutboundSpamFilterPolicy](https://docs.microsoft.com/powershell/module/exchange/get-hostedoutboundspamfilterpolicy).</span><span class="sxs-lookup"><span data-stu-id="6f387-105">You can check the outbound spam filter policy from Security and Compliance Center [here] (https://protection.office.com/antispam) or by using the [Get-HostedOutboundSpamFilterPolicy command](https://docs.microsoft.com/powershell/module/exchange/get-hostedoutboundspamfilterpolicy).</span></span>

<span data-ttu-id="6f387-106">Se estiver a obter o seguinte erro: **"550 5.7.520 Acesso negado, a sua organização não permite o encaminhamento externo"**, certifique-se de que a política está configurada para ativar o Auto-forward Externo.</span><span class="sxs-lookup"><span data-stu-id="6f387-106">If you are getting the following error: **“550 5.7.520 Access denied, Your organization does not allow external forwarding”**, please make sure the policy is configured to enable External Auto-forward.</span></span>

<span data-ttu-id="6f387-107">**Nota:** Recomenda-se manter o Autoforward Externo desativado na sua política de filtro de spam por defeito e permitir apenas para os utilizadores que necessitem de reencaminhamento externo, criando uma política personalizada para esses utilizadores.</span><span class="sxs-lookup"><span data-stu-id="6f387-107">**Note:** It is recommended to keep the External Autoforward disabled on your default outbound spam filter policy and enable it only for the users who need external forwarding by creating a custom policy for those users.</span></span> <span data-ttu-id="6f387-108">Pode ler mais na [configuração do reencaminhamento de e-mails externos no Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/external-email-forwarding).</span><span class="sxs-lookup"><span data-stu-id="6f387-108">You can read more in [Configuring external email forwarding in Office 365](https://docs.microsoft.com/microsoft-365/security/office-365-security/external-email-forwarding).</span></span>