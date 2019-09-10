---
title: Mover mensagens de email para a caixa de correio arquivar
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 11/7/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1083"
- "3100008"
ms.assetid: 59cd8630-6196-4680-ad92-1ce0e479f924
ms.openlocfilehash: 5592bc7d4566e3498c33bbf9488db7f46ec58842
ms.sourcegitcommit: 8864b5789d9905916039081b53530c7e6d8bc529
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 09/10/2019
ms.locfileid: "36822173"
---
# <a name="move-email-to-the-archive-mailbox"></a><span data-ttu-id="c97ac-102">Mover email para a caixa de correio de arquivamento</span><span class="sxs-lookup"><span data-stu-id="c97ac-102">Move email to the archive mailbox</span></span>

1. <span data-ttu-id="c97ac-103">Confirme se uma **caixa de correio de arquivamento** foi habilitada.</span><span class="sxs-lookup"><span data-stu-id="c97ac-103">Confirm that an **Archive mailbox** has been enabled.</span></span> <span data-ttu-id="c97ac-104">Caso não esteja, use as etapas neste [artigo](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) para habilitar a caixa de correio de arquivamento.</span><span class="sxs-lookup"><span data-stu-id="c97ac-104">If not, use the steps in [this article](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes) to enable the archive mailbox.</span></span>

2. <span data-ttu-id="c97ac-105">Para arquivar mensagens automaticamente na caixa de correio de arquivamento, uma marca de retenção com a ação **mover para arquivar** deve ser definida como **aplicada automaticamente à marca de caixa de correio inteira (padrão)**.</span><span class="sxs-lookup"><span data-stu-id="c97ac-105">To archive messages automatically to the archive mailbox, a retention tag with the **Move to archive** action must be set to **applied automatically to entire mailbox (default) tag**.</span></span> <span data-ttu-id="c97ac-106">Use as etapas aqui para criar a marca: [Archive default tag](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).</span><span class="sxs-lookup"><span data-stu-id="c97ac-106">Use the steps here to create the tag: [Archive Default tag](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#create-a-custom-archive-default-policy-tag).</span></span>

3. <span data-ttu-id="c97ac-107">Em seguida, adicione a tag **Archive** à sua política de retenção.</span><span class="sxs-lookup"><span data-stu-id="c97ac-107">Next, add the **Archive** tag to your retention policy.</span></span> <span data-ttu-id="c97ac-108">No centro de administração do Exchange, escolha **diretivas de retenção** > adicione a **tag mover para arquivar** na política > **salvar**.</span><span class="sxs-lookup"><span data-stu-id="c97ac-108">In the Exchange admin center, choose **Retention Policies** > add the **Move to Archive tag** to the policy > **Save**.</span></span>

4. <span data-ttu-id="c97ac-109">Agora [atribua a política de retenção](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) à caixa de correio do usuário específico.</span><span class="sxs-lookup"><span data-stu-id="c97ac-109">Now [Assign the Retention Policy](https://docs.microsoft.com/exchange/security-and-compliance/messaging-records-management/apply-retention-policy) to the specific user's mailbox.</span></span> <span data-ttu-id="c97ac-110">A mesma política será aplicada ao **primário** e à caixa de correio de **arquivamento** .</span><span class="sxs-lookup"><span data-stu-id="c97ac-110">The same policy will be applied to both the **Primary** and the **Archive** mailbox.</span></span>

<span data-ttu-id="c97ac-111">Pode ser necessário forçar o assistente de pasta gerenciada (MFA) para executar e aplicar as novas configurações à caixa de correio do usuário.</span><span class="sxs-lookup"><span data-stu-id="c97ac-111">It may be necessary to force the Managed Folder Assistant (MFA) to run and apply the new settings to the user's mailbox.</span></span> <span data-ttu-id="c97ac-112">Execute o seguinte comando enquanto [estiver conectado ao EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) para iniciar o assistente de pasta gerenciada para uma caixa de correio específica:</span><span class="sxs-lookup"><span data-stu-id="c97ac-112">Run the following command while [connected to EXO PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell?view=exchange-ps) to start the Managed Folder Assistant for a specific mailbox:</span></span>
  
<span data-ttu-id="c97ac-113">Start-ManagedFolderAssistant-identidade<name of the mailbox></span><span class="sxs-lookup"><span data-stu-id="c97ac-113">Start-ManagedFolderAssistant -Identity <name of the mailbox></span></span>

<span data-ttu-id="c97ac-114">Para obter mais informações sobre como configurar uma política de arquivamento, consulte [Configurar uma política de arquivamento e exclusão para caixas de correio](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span><span class="sxs-lookup"><span data-stu-id="c97ac-114">For more information on setting up an archive policy, see [Set up an archive and deletion policy for mailboxes](https://docs.microsoft.com/office365/securitycompliance/set-up-an-archive-and-deletion-policy-for-mailboxes#step-1-enable-archive-mailboxes-for-users).</span></span>
  