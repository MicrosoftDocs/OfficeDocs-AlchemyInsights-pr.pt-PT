---
title: Como desabilitar grupos externos
ms.author: pebaum
author: pebaum
ms.date: 12/17/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "966"
- "6000006"
ms.assetid: 4e429507-039b-410e-a994-54b443d4e91e
ms.openlocfilehash: b2328ea85d3ff6ec722cc56d8a46395d8438f79c
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 10/18/2019
ms.locfileid: "36739504"
---
# <a name="how-to-disable-external-groups"></a><span data-ttu-id="67bea-102">Como desabilitar grupos externos</span><span class="sxs-lookup"><span data-stu-id="67bea-102">How to disable External Groups</span></span>

<span data-ttu-id="67bea-103">O sistema de mensagens externas do Yammer aplica as regras de transporte do Exchange (ETRs), um conjunto de controles pró-ativos para impedir que as informações da empresa sejam compartilhadas.</span><span class="sxs-lookup"><span data-stu-id="67bea-103">Yammer external messaging applies Exchange Transport Rules (ETRs), a set of proactive controls to prevent company information from being shared.</span></span> <span data-ttu-id="67bea-104">Para restringir os usuários de criar grupos externos, você precisa configurar uma regra de transporte do Exchange (ETR) e, em seguida, configurar o Yammer para usar a regra de transporte do Exchange para bloquear mensagens externas.</span><span class="sxs-lookup"><span data-stu-id="67bea-104">In order to restrict users from creating external groups, you need to configure an Exchange transport rule (ETR), and then configure Yammer to use the Exchange Transport rule to block external messaging.</span></span>
  
<span data-ttu-id="67bea-105">Depois de criar uma regra no centro de administração do Exchange Online, siga estas etapas para definir ETR para aplicar no Yammer:</span><span class="sxs-lookup"><span data-stu-id="67bea-105">Once you have created a rule in Exchange Online admin center, follow these steps to set ETR to apply in Yammer:</span></span>
  
- <span data-ttu-id="67bea-106">Faça logon no Yammer como um administrador verificado e no centro de **Administração do Yammer**, vá para **configurações de segurança de \> conteúdo e segurança** do C.</span><span class="sxs-lookup"><span data-stu-id="67bea-106">Log on to Yammer as a verified admin, and in the **Yammer admin center**, go to C **Content and Security \> Security Settings.**</span></span>

- <span data-ttu-id="67bea-107">Em **mensagens externas**, selecione **impor suas regras de transporte do Exchange Online Exchange (ETRS) no Yammer.**</span><span class="sxs-lookup"><span data-stu-id="67bea-107">Under **External Messaging**, select **Enforce your Exchange Online Exchange Transport Rules (ETRs) in Yammer.**</span></span>

- <span data-ttu-id="67bea-108">Selecione **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="67bea-108">Choose **Save**.</span></span>

<span data-ttu-id="67bea-109">Para obter mais informações, consulte [desabilitar mensagens externas em uma rede Yammer](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span><span class="sxs-lookup"><span data-stu-id="67bea-109">For more information, see [Disable external messaging in a Yammer network](https://docs.microsoft.com/yammer/work-with-external-users/disable-external-messaging).</span></span>
  