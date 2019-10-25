---
title: Antispam - 5,7,23
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3156"
- "9001196"
ms.openlocfilehash: 9c9bc2d04fb8efaa5e75194b4ca09316d24e018e
ms.sourcegitcommit: 07b47d7f3ca191363e6bc84140e8e01524d6f08e
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 10/24/2019
ms.locfileid: "37682246"
---
# <a name="fix-email-delivery-issues-for-error-code-5723"></a><span data-ttu-id="7f2ee-102">Corrigir problemas de entrega de e-mail para código de erro 5.7.23</span><span class="sxs-lookup"><span data-stu-id="7f2ee-102">Fix email delivery issues for error code 5.7.23</span></span>

<span data-ttu-id="7f2ee-103">Verifique o registro SPF DNS para o seu domínio em um verificador de registro SPF ou DNS disponível publicamente na web.</span><span class="sxs-lookup"><span data-stu-id="7f2ee-103">Verify the SPF DNS record for your domain at a publicly available SPF or DNS record checker on the web.</span></span>

<span data-ttu-id="7f2ee-104">Verifique se a mensagem de saída não foi identificada como spam pelo Office 365 e encaminhada através do Pool de Entrega de [Alto Risco.](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages)</span><span class="sxs-lookup"><span data-stu-id="7f2ee-104">Verify that the outbound message wasn't identified as spam by Office 365 and routed through the [High Risk Delivery Pool](https://docs.microsoft.com/office365/SecurityCompliance/high-risk-delivery-pool-for-outbound-messages).</span></span> <span data-ttu-id="7f2ee-105">As mensagens no Pool de Entrega de Alto Risco não passarão nas verificações do FPS e, portanto, não serão aceitas pela organização de e-mail de destino.</span><span class="sxs-lookup"><span data-stu-id="7f2ee-105">Messages in the High Risk Delivery Pool won't pass SPF checks, and therefore won't be accepted by the destination email organization.</span></span>

<span data-ttu-id="7f2ee-106">Se o problema persistir, você pode precisar entrar em contato com o administrador do mail host para o qual você está tentando enviar e-mail.</span><span class="sxs-lookup"><span data-stu-id="7f2ee-106">If the problem persists, you may need to contact the admin of the mail host to which you are attempting to send email.</span></span> <span data-ttu-id="7f2ee-107">Anote o erro externo detalhado disponível na mensagem de rejeição.</span><span class="sxs-lookup"><span data-stu-id="7f2ee-107">Make note of the detailed external error available in the bounce message.</span></span>  <span data-ttu-id="7f2ee-108">O suporte do Escritório 365 pode não ser capaz de ajudar ainda mais.</span><span class="sxs-lookup"><span data-stu-id="7f2ee-108">Office 365 support may not be able to assist further.</span></span>