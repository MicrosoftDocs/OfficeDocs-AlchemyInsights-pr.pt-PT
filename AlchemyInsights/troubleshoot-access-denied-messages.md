---
title: Acesso a resolução de problemas Mensagens negadas
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d678b57a-53ad-4414-9423-d8726a0c532f
ms.openlocfilehash: 6c8ad84123fb58b73b9c378592ce970997893ea2
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 03/10/2021
ms.locfileid: "50704905"
---
# <a name="troubleshoot-access-denied-messages"></a><span data-ttu-id="25ba5-102">Acesso a resolução de problemas Mensagens negadas</span><span class="sxs-lookup"><span data-stu-id="25ba5-102">Troubleshoot Access Denied messages</span></span>

<span data-ttu-id="25ba5-103">Se alguém obteve uma mensagem "Access Denied" para uma pasta partilhada no SharePoint, o administrador de recolha do site pode ter ativado o "modo de bloqueio de permissão de acesso limitado do utilizador".</span><span class="sxs-lookup"><span data-stu-id="25ba5-103">If someone got an "Access Denied" message to a shared folder in SharePoint, the site collection administrator might have enabled "Limited-access user permission lockdown mode."</span></span> <span data-ttu-id="25ba5-104">Para desligar isto:</span><span class="sxs-lookup"><span data-stu-id="25ba5-104">To turn this off:</span></span> 
  
1. <span data-ttu-id="25ba5-105">Navegue no site, clique no ícone Definições e, em seguida, clique em **Definições do Site**.</span><span class="sxs-lookup"><span data-stu-id="25ba5-105">Browse to the site, click the Settings icon, and then click **Site Settings**.</span></span>
    
2. <span data-ttu-id="25ba5-106">Na **Administração da Recolha do Site,** clique **nas funcionalidades de recolha do Site.**</span><span class="sxs-lookup"><span data-stu-id="25ba5-106">Under **Site Collection Administration**, click **Site collection features**.</span></span>
    
3. <span data-ttu-id="25ba5-107">Ao lado do **modo de bloqueio de permissão de acesso limitado** do utilizador, clique em **Desativar**.</span><span class="sxs-lookup"><span data-stu-id="25ba5-107">Next to **Limited-access user permission lockdown mode**, click **Deactivate**.</span></span>
    
<span data-ttu-id="25ba5-108">Uma mensagem Access Negado também pode ocorrer para pastas partilhadas se o site for um site de publicação.</span><span class="sxs-lookup"><span data-stu-id="25ba5-108">An Access Denied message can also occur for shared folders if the site is a publishing site.</span></span> <span data-ttu-id="25ba5-109">Para obter informações, consulte [Acesso Negado ao aceder a uma pasta partilhada](https://answers.microsoft.com/windows/forum/windows_7-files/access-denied-to-share-folder/79fae49d-cddf-4845-8ac8-c141884d85fb).</span><span class="sxs-lookup"><span data-stu-id="25ba5-109">For info, see [Access Denied when accessing a shared folder](https://answers.microsoft.com/windows/forum/windows_7-files/access-denied-to-share-folder/79fae49d-cddf-4845-8ac8-c141884d85fb).</span></span>
  
<span data-ttu-id="25ba5-110">Se alguém recebeu uma mensagem "Access Denied" ao tentar visualizar pedidos de acesso, o utilizador precisa de ser adicionado como administrador de recolha de site ou membro do grupo Owners para o site.</span><span class="sxs-lookup"><span data-stu-id="25ba5-110">If a someone got an "Access Denied" message when trying to view access requests, the user needs to be added as either a site collection administrator or a member of the Owners group for the site.</span></span> <span data-ttu-id="25ba5-111">Para mais informações, consulte [a lista de Pedidos de Acesso Negados a Pedidos de Acesso.](https://go.microsoft.com/fwlink/?linkid=2004220)</span><span class="sxs-lookup"><span data-stu-id="25ba5-111">For more info, see [Access Denied to Access Requests list](https://go.microsoft.com/fwlink/?linkid=2004220).</span></span>
  
<span data-ttu-id="25ba5-112">Se um utilizador recebeu uma mensagem "Access Denied" depois de ter sido removido do Ative Directory no local e depois adicionado de volta, consulte [Access Denied quando uma conta de utilizador estiver sincronizada com a Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span><span class="sxs-lookup"><span data-stu-id="25ba5-112">If a user got an "Access Denied" message after they were removed from Active Directory on-premises and then added back, see [Access Denied when a user account is synced to Microsoft 365](https://go.microsoft.com/fwlink/?linkid=2004318).</span></span>
  

