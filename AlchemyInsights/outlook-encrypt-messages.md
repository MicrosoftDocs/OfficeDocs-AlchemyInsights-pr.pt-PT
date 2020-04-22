---
title: S/MIME no Outlook na web
ms.author: pebaum
author: pebaum
manager: pamgreen
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: 9000329
ms.openlocfilehash: 7184ffd68f56639a8bcb87e9c6cab88388868103
ms.sourcegitcommit: 631cbb5f03e5371f0995e976536d24e9d13746c3
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/22/2020
ms.locfileid: "43764883"
---
# <a name="encrypt-email-messages-in-outlook"></a><span data-ttu-id="3a4c2-102">Criptografe mensagens de e-mail no Outlook</span><span class="sxs-lookup"><span data-stu-id="3a4c2-102">Encrypt email messages in Outlook</span></span>

<span data-ttu-id="3a4c2-103">A Encriptação de Mensagens Microsoft 365 é construída na Microsoft Azure Rights Management (Azure RMS), que faz parte da Proteção de Informação do Azure.</span><span class="sxs-lookup"><span data-stu-id="3a4c2-103">Microsoft 365 Message Encryption is built on Microsoft Azure Rights Management (Azure RMS), which is part of Azure Information Protection.</span></span> <span data-ttu-id="3a4c2-104">Se a sua subscrição incluir a Azure Rights Management ou a Azure Information Protection, **não precisa de tomar quaisquer ações para ativar ou ativar manualmente** o Serviço de Gestão de Direitos.</span><span class="sxs-lookup"><span data-stu-id="3a4c2-104">If your subscription includes Azure Rights Management or Azure Information Protection, **you do not need to take any actions to manually enable or activate** the Rights Management Service.</span></span>

<span data-ttu-id="3a4c2-105">Com base no feedback do cliente, deixaremos de permitir que as regras de fluxo de correio de troca criptografem automaticamente e-mails de saída contendo determinado tipo de informação sensível no seu inquilino por defeito.</span><span class="sxs-lookup"><span data-stu-id="3a4c2-105">Based on customer feedback, we will no longer be enabling Exchange mail flow rules to automatically encrypt outbound email containing certain type of sensitive information in your tenant by default.</span></span> <span data-ttu-id="3a4c2-106">Em vez disso, estamos a dar instruções detalhadas sobre como podem fazê-lo a si mesmos.</span><span class="sxs-lookup"><span data-stu-id="3a4c2-106">Instead, we are providing detailed instructions on how you can do so yourselves.</span></span> <span data-ttu-id="3a4c2-107">Para mais detalhes sobre como criar uma regra de transporte para encriptar informações sensíveis, consulte [este artigo](https://aka.ms/OmeEtr).</span><span class="sxs-lookup"><span data-stu-id="3a4c2-107">For additional details on how to create a transport rule to encrypt sensitive information, see [this article](https://aka.ms/OmeEtr).</span></span>

- <span data-ttu-id="3a4c2-108">Se utilizar o Outlook na Web (anteriormente **OWA**): Ao compor uma mensagem de e-mail, basta clicar em **Proteger** em OWA.</span><span class="sxs-lookup"><span data-stu-id="3a4c2-108">If using Outlook on the Web (formerly **OWA**): When composing an email message, simply click **Protect** in OWA.</span></span> <span data-ttu-id="3a4c2-109">Isto aplicará permissão "Não encaminhar".</span><span class="sxs-lookup"><span data-stu-id="3a4c2-109">This will apply "Do not forward" permission.</span></span> <span data-ttu-id="3a4c2-110">Clique na **permissão De alterar** e escolha **encriptar** apenas para encriptar a mensagem.</span><span class="sxs-lookup"><span data-stu-id="3a4c2-110">Click **Change permission** and choose **Encrypt** to only encrypt the message.</span></span>

- <span data-ttu-id="3a4c2-111">Se utilizar o **cliente do Outlook**: Para enviar uma mensagem encriptada do Outlook 2013 ou 2016, ou do Outlook 2016 para Mac, selecione **Options** > **Permissions,** então selecione a opção de proteção de que necessita.</span><span class="sxs-lookup"><span data-stu-id="3a4c2-111">If using **Outlook client**: To send an encrypted message from Outlook 2013 or 2016, or Outlook 2016 for Mac, select **Options** > **Permissions**, then select the protection option you need.</span></span>

- <span data-ttu-id="3a4c2-112">Para **encriptar automaticamente todos os e-mails** enviados a determinados destinatários ou organizações parceiras externas, é necessário criar uma regra de transporte de fluxo de correio no Exchange Admin Center.</span><span class="sxs-lookup"><span data-stu-id="3a4c2-112">To **automatically encrypt all email** sent to certain recipients or external partner organizations, you need to create a mail flow transport rule in the Exchange Admin Center.</span></span> <span data-ttu-id="3a4c2-113">Instruções detalhadas são fornecidas [neste artigo de apoio](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span><span class="sxs-lookup"><span data-stu-id="3a4c2-113">Detailed instructions are provided in [this support article](https://docs.microsoft.com/office365/securitycompliance/define-mail-flow-rules-to-encrypt-email#create-a-mail-flow-rule-to-encrypt-email-messages-with-the-new-ome-capabilities).</span></span>

