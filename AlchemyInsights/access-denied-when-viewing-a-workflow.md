---
title: Acesso negado ao visualizar um Fluxo de Trabalho
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 710775e8b2dee98969df7a4c8410a3e61181aaf6
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 09/14/2020
ms.locfileid: "47688813"
---
# <a name="access-denied-when-viewing-a-workflow"></a><span data-ttu-id="c4c7e-102">Acesso negado ao visualizar um Fluxo de Trabalho</span><span class="sxs-lookup"><span data-stu-id="c4c7e-102">Access denied when viewing a Workflow</span></span>

<span data-ttu-id="c4c7e-103">Fluxos de trabalho sharePoint 2013 que tentam enviar um e-mail para um grupo SharePoint podem falhar com uma mensagem de erro "Access Denied" se a adesão do grupo SharePoint não for definida para Todos.</span><span class="sxs-lookup"><span data-stu-id="c4c7e-103">SharePoint 2013 Workflows that attempt to send an email to a SharePoint group can fail with an "Access Denied" error message if the membership of the SharePoint group is not set to Everyone.</span></span>
  
 <span data-ttu-id="c4c7e-104">**Para resolver esta questão, faça estes passos:**</span><span class="sxs-lookup"><span data-stu-id="c4c7e-104">**To resolve this issue, do these steps:**</span></span>
  
 1. <span data-ttu-id="c4c7e-105">Permitir que todos vejam os membros do grupo SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c4c7e-105">Allow everybody to see the members of the SharePoint group.</span></span>
  
 2. <span data-ttu-id="c4c7e-106">Remova o grupo SharePoint da linha To ou CC do e-mail.</span><span class="sxs-lookup"><span data-stu-id="c4c7e-106">Remove the SharePoint group from the To or CC line of the email.</span></span>
  
 3. <span data-ttu-id="c4c7e-107">Adicione explicitamente os utilizadores à linha To ou CC se a visibilidade da adesão não puder ser alterada para o grupo SharePoint.</span><span class="sxs-lookup"><span data-stu-id="c4c7e-107">Explicitly add the users to the To or CC line if the membership visibility cannot be changed for SharePoint group.</span></span>
  
<span data-ttu-id="c4c7e-108">Para ver mais detalhes consulte [HTTP Não Autorizado para /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span><span class="sxs-lookup"><span data-stu-id="c4c7e-108">To view more details please refer to [HTTP Unauthorized to /_vti_bin/client.svc/sp.utilities.utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).</span></span>
  