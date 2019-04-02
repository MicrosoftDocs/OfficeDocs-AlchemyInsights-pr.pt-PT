---
title: 1336 RecoverableItems pasta está cheia
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1336
ms.assetid: a3a923e8-fece-4a26-b8b6-00970d75275e
ms.openlocfilehash: a048949d5284d018303d03aad26cdf26eee2fb5c
ms.sourcegitcommit: 03a156a9c9740521155a30775492c7dff0982588
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 03/22/2019
ms.locfileid: "30776407"
---
# <a name="the-recoverable-items-folder-is-full"></a><span data-ttu-id="f0a04-102">A pasta de itens recuperável está cheia</span><span class="sxs-lookup"><span data-stu-id="f0a04-102">The Recoverable Items folder is full</span></span>

<span data-ttu-id="f0a04-103">Para caixas de correio Exchange Online no Office 365, o limite de armazenamento predefinida para a pasta itens recuperável é 30 GB.</span><span class="sxs-lookup"><span data-stu-id="f0a04-103">For Exchange Online mailboxes in Office 365, the default storage limit for the Recoverable Items folder is 30 GB.</span></span> <span data-ttu-id="f0a04-104">O limite de armazenamento para a pasta de itens recuperável automaticamente é aumentado para 100 GB se a caixa de correio é colocada em suspensão do litígio, suspenso de detecção de dados electrónicos, ou atribuída a uma política de retenção do Office 365.</span><span class="sxs-lookup"><span data-stu-id="f0a04-104">The storage limit for the Recoverable Items folder is automatically increased to 100 GB if the mailbox is placed on Litigation Hold, eDiscovery hold, or is assigned to an Office 365 retention policy.</span></span>
  
<span data-ttu-id="f0a04-105">Quando a pasta itens recuperável atinge o limite de armazenamento, a funcionalidade de caixa de correio é afectada das seguintes formas:</span><span class="sxs-lookup"><span data-stu-id="f0a04-105">When the Recoverable Items folder reaches the storage limit, mailbox functionality is affected in the following ways:</span></span>
  
- <span data-ttu-id="f0a04-106">O utilizador não é possível eliminar itens da caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="f0a04-106">The user can't delete items from the mailbox.</span></span>
    
- <span data-ttu-id="f0a04-107">O Managed Assistente da pasta não pode eliminar itens com base no código de retenção ou as definições de pasta gerida.</span><span class="sxs-lookup"><span data-stu-id="f0a04-107">The Managed Folder Assistant can't delete items based on retention tag or managed folder settings.</span></span>
    
- <span data-ttu-id="f0a04-108">Para caixas de correio que tenham o único Item recuperação activada ou colocadas em espera, o processo de protecção de página de cópia de escrita não é possível manter versões dos itens editados pelo utilizador.</span><span class="sxs-lookup"><span data-stu-id="f0a04-108">For mailboxes that have Single Item Recovery enabled or are placed on hold, the copy-on-write page protection process can't maintain versions of items edited by the user.</span></span>
    
- <span data-ttu-id="f0a04-109">Para caixas de correio que tenham activado o registo de auditoria da caixa de correio, entradas de registo de auditoria sem caixa de correio podem ser guardadas na subpasta auditorias na pasta itens recuperável.</span><span class="sxs-lookup"><span data-stu-id="f0a04-109">For mailboxes that have mailbox audit logging enabled, no mailbox audit log entries can be saved in the Audits subfolder in the Recoverable Items folder.</span></span>
    
<span data-ttu-id="f0a04-110">Para caixas de correio que não estão em espera, admins pode utilizar o `Search-Mailbox -SearchDumpsterOnly -DeleteContent` comando no PowerShell Online do Exchange para eliminar itens na pasta itens recuperável.</span><span class="sxs-lookup"><span data-stu-id="f0a04-110">For mailboxes that aren't on hold, admins can use the  `Search-Mailbox -SearchDumpsterOnly -DeleteContent` command in Exchange Online PowerShell to delete items in the Recoverable Items folder.</span></span> <span data-ttu-id="f0a04-111">For more information, see the following topics:</span><span class="sxs-lookup"><span data-stu-id="f0a04-111">For more information, see the following topics:</span></span> 
  
- [<span data-ttu-id="f0a04-112">Procurar e eliminar mensagens</span><span class="sxs-lookup"><span data-stu-id="f0a04-112">Search for and delete messages</span></span>](https://docs.microsoft.com/office365/securitycompliance/search-for-and-delete-messagesadmin-help)
    
- [<span data-ttu-id="f0a04-113">Caixa de correio de procura</span><span class="sxs-lookup"><span data-stu-id="f0a04-113">Search-Mailbox</span></span>](https://docs.microsoft.com/powershell/module/exchange/mailboxes/Search-Mailbox)
    
<span data-ttu-id="f0a04-114">Para caixas de correio que estão em espera, admins devem remover o antes de poderem itens eliminados da pasta itens recuperável.</span><span class="sxs-lookup"><span data-stu-id="f0a04-114">For mailboxes that are on hold, admins have to remove the hold before they can deleted items from the Recoverable Items folder.</span></span> <span data-ttu-id="f0a04-115">Para mais informações, consulte [Eliminar itens em itens recuperável mantenha pasta baseada na nuvem caixas de correio](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="f0a04-115">For more information, see [Delete items in the Recoverable Items folder of cloud-based mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/delete-items-in-the-recoverable-items-folder-of-mailboxes-on-hold).</span></span>
  
<span data-ttu-id="f0a04-116">Para ajudar a evitar que a pasta itens recuperável se torne completo, admins pode aumentar o limite de armazenamento dos itens recuperável mantenha a tecla de pasta para caixas de correio e configurar uma política de retenção de caixa de correio que move itens da pasta itens recuperável para arquivo do utilizador caixa de correio.</span><span class="sxs-lookup"><span data-stu-id="f0a04-116">To help prevent the Recoverable Items folder from becoming full, admins can increase the storage limit of the Recoverable Items folder for mailboxes on hold and set up a mailbox retention policy that moves items from the Recoverable Items folder to the user's archive mailbox.</span></span> <span data-ttu-id="f0a04-117">Consulte a [aumentar os itens recuperável mantenha de quota para caixas de correio](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span><span class="sxs-lookup"><span data-stu-id="f0a04-117">See [Increase the Recoverable Items quota for mailboxes on hold](https://docs.microsoft.com/office365/securitycompliance/increase-the-recoverable-quota-for-mailboxes-on-hold).</span></span>
  
