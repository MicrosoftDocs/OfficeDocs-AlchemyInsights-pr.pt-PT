---
title: 1336 A pasta RecoverableItems está cheia
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1336"
- "3700003"
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: 6ae608b776332402fe333315f5e4ff6072b0a651
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 09/14/2020
ms.locfileid: "47741278"
---
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="9a6b7-102">A pasta de Itens Recuperáveis está cheia</span><span class="sxs-lookup"><span data-stu-id="9a6b7-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="9a6b7-103">Para caixas de correio Exchange Online, o limite de armazenamento predefinido para a pasta Itens Recuperáveis é de 30 GB.</span><span class="sxs-lookup"><span data-stu-id="9a6b7-103">For Exchange Online mailboxes, the default storage limit for the Recoverable Items folder is 30 GB.</span></span> <span data-ttu-id="9a6b7-104">O limite de armazenamento da pasta Itens Recuperáveis é automaticamente aumentado para 100 GB se a caixa de correio for colocada em Hold de Litígio, porão eDiscovery ou for atribuída a uma política de retenção.</span><span class="sxs-lookup"><span data-stu-id="9a6b7-104">The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to a retention policy.</span></span>

<span data-ttu-id="9a6b7-105">Quando a pasta Itens Recuperáveis atinge o limite de armazenamento, a funcionalidade da caixa de correio é afetada das seguintes formas:</span><span class="sxs-lookup"><span data-stu-id="9a6b7-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>

- <span data-ttu-id="9a6b7-106">O utilizador não pode eliminar os itens da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="9a6b7-106">The user can't delete items from the mailbox.</span></span>

- <span data-ttu-id="9a6b7-107">O Assistente de Pasta Gerida não pode eliminar itens baseados na etiqueta de retenção ou nas definições de pasta geridas.</span><span class="sxs-lookup"><span data-stu-id="9a6b7-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>

- <span data-ttu-id="9a6b7-108">Para caixas de correio que tenham a Recuperação de Item Único ativada ou colocadas em espera, o processo de proteção da página de cópia na escrita não consegue manter versões de itens editados pelo utilizador.</span><span class="sxs-lookup"><span data-stu-id="9a6b7-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>

- <span data-ttu-id="9a6b7-109">Para caixas de correio que tenham registo de auditoria de caixa de correio ativado, não podem ser guardadas entradas de registo de auditoria na sub-dobragem de Auditorias na pasta Itens Recuperáveis.</span><span class="sxs-lookup"><span data-stu-id="9a6b7-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>

<span data-ttu-id="9a6b7-110">Para caixas de correio que não estejam em espera, os administradores podem utilizar o `Search-Mailbox -SearchDumpsterOnly -DeleteContent` comando em Exchange Online PowerShell para eliminar itens na pasta Itens Recuperáveis.</span><span class="sxs-lookup"><span data-stu-id="9a6b7-110">For mailboxes that aren't on hold, admins can use the `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder.</span></span> <span data-ttu-id="9a6b7-111">For more information, see the following topics:</span><span class="sxs-lookup"><span data-stu-id="9a6b7-111">For more information, see the following topics:</span></span>

- [<span data-ttu-id="9a6b7-112">Procurar e eliminar mensagens</span><span class="sxs-lookup"><span data-stu-id="9a6b7-112">Search for and delete messages</span></span>](https://docs.microsoft.com/microsoft-365/compliance/search-for-and-delete-messagesadmin-help)

- [<span data-ttu-id="9a6b7-113">Caixa de correio de pesquisa</span><span class="sxs-lookup"><span data-stu-id="9a6b7-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)

<span data-ttu-id="9a6b7-114">Para caixas de correio que estejam em espera, os administradores têm de remover o porão antes de poderem eliminar itens da pasta Itens Recuperáveis.</span><span class="sxs-lookup"><span data-stu-id="9a6b7-114">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder.</span></span> <span data-ttu-id="9a6b7-115">Para obter mais informações, consulte [eliminar itens na pasta Itens Recuperáveis de caixas de correio baseadas na nuvem em espera](https://docs.microsoft.com/microsoft-365/compliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="9a6b7-115">For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/microsoft-365/compliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>

<span data-ttu-id="9a6b7-116">Para ajudar a evitar que a pasta de Itens Recuperáveis fique cheia, os administradores podem aumentar o limite de armazenamento da pasta Itens Recuperáveis para caixas de correio em espera e configurar uma política de retenção de caixas de correio que transfere os itens da pasta Itens Recuperáveis para a caixa de correio do utilizador.</span><span class="sxs-lookup"><span data-stu-id="9a6b7-116">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox.</span></span> <span data-ttu-id="9a6b7-117">Ver [Aumentar a quota de itens recuperáveis para caixas de correio em espera](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="9a6b7-117">See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/microsoft-365/compliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>
