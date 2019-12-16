---
title: Falta de fluxo de trabalho não conseguiu ativar
ms.author: pebaum
author: pebaum
ms.date: 12/3/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: e46ae8c5-3d81-457e-8c77-f7c1cbe267c4
ms.openlocfilehash: 3df1ddc1059c4cd6cc3f9f42dc157d20be79a63a
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 12/15/2019
ms.locfileid: "40052624"
---
# <a name="missing-workflow-failed-to-activate"></a><span data-ttu-id="f65f9-102">Falta de fluxo de trabalho não conseguiu ativar</span><span class="sxs-lookup"><span data-stu-id="f65f9-102">Missing Workflow Failed to Activate</span></span>

<span data-ttu-id="f65f9-103">Em uma coleção de sites do Microsoft SharePoint, você não pode adicionar um fluxo de trabalho globalmente reutilizável (como "Aprovação - SharePoint 2010") a uma lista ou biblioteca.</span><span class="sxs-lookup"><span data-stu-id="f65f9-103">In a Microsoft SharePoint site collection, you can't add a globally reusable workflow (such as "Approval - SharePoint 2010") to a list or library.</span></span>
  
<span data-ttu-id="f65f9-104">Para resolver este problema, siga estas etapas:</span><span class="sxs-lookup"><span data-stu-id="f65f9-104">To resolve this issue, follow these steps:</span></span> 
  
1. <span data-ttu-id="f65f9-105">Abra o site raiz da coleção do site em SharePoint Designer 2013.</span><span class="sxs-lookup"><span data-stu-id="f65f9-105">Open the root website of the site collection in SharePoint Designer 2013.</span></span>
  
2. <span data-ttu-id="f65f9-106">**objetos do site,** selecione fluxos de **trabalho.**</span><span class="sxs-lookup"><span data-stu-id="f65f9-106">Under **Site Objects**, select **Workflows**.</span></span> 
  
3. <span data-ttu-id="f65f9-107">Na **nova** seção da fita **workflows,** selecione fluxo de **trabalho reutilizável.**</span><span class="sxs-lookup"><span data-stu-id="f65f9-107">In the **New** section of the **Workflows** ribbon, select **Reusable Workflow**.</span></span> 
  
4. <span data-ttu-id="f65f9-108">No formulário criar fluxo de **trabalho reutilizável,** digite o nome \*\* *Repair2010* \*\*.</span><span class="sxs-lookup"><span data-stu-id="f65f9-108">On the **Create Reusable Workflow** form, enter the name \*\* *Repair2010* \*\*.</span></span> <span data-ttu-id="f65f9-109">Para **o tipo de plataforma,** clique no fluxo de trabalho **sharepoint 2010**e, em seguida, clique na **OK.**</span><span class="sxs-lookup"><span data-stu-id="f65f9-109">For **Platform Type**, click **SharePoint 2010 Workflow**, and then click **OK**.</span></span> 
  
1. <span data-ttu-id="f65f9-110">Na seção **Save** da fita **workflow,** **selecione Publicar**.</span><span class="sxs-lookup"><span data-stu-id="f65f9-110">In the **Save** section of the **Workflow** ribbon, select **Publish**.</span></span> 
  
2. <span data-ttu-id="f65f9-111">Na seção **gerenciar** da fita **workflow,** selecione **Publicar Globalmente**.</span><span class="sxs-lookup"><span data-stu-id="f65f9-111">In the **Manage** section of the **Workflow** ribbon, select **Publish Globally**.</span></span> <span data-ttu-id="f65f9-112">Na caixa de diálogo de confirmação que aparece, selecione **OK**.</span><span class="sxs-lookup"><span data-stu-id="f65f9-112">In the confirmation dialog box that appears, select **OK**.</span></span> 
  
3. <span data-ttu-id="f65f9-113">Em um navegador da web, localizar o site raiz da coleção do site, e, em seguida, acessar **site Configurações Características** \> **de coleta do site.**</span><span class="sxs-lookup"><span data-stu-id="f65f9-113">In a web browser, locate the root website of the site collection, and then access **Site Settings** \> **Site Collection Features**.</span></span> <span data-ttu-id="f65f9-114">Em seguida, alternar o recurso **de fluxos** de trabalho:</span><span class="sxs-lookup"><span data-stu-id="f65f9-114">Then, toggle the **Workflows** feature:</span></span> 
  
<span data-ttu-id="f65f9-115">· Se o recurso for *ativado,* clique **em desativar** e, em seguida, clique **em Ativar.**</span><span class="sxs-lookup"><span data-stu-id="f65f9-115">· If the feature is  *Activated*  , click **Deactivate,** and then click **Activate**.</span></span> 
  
<span data-ttu-id="f65f9-116">· Se o recurso for *desativado,* clique **em Ativar.**</span><span class="sxs-lookup"><span data-stu-id="f65f9-116">· If the feature is  *Deactivated*  , click **Activate**.</span></span> 
  
<span data-ttu-id="f65f9-117">Para mais informações, consulte o seguinte [artigo.](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409)</span><span class="sxs-lookup"><span data-stu-id="f65f9-117">For more information please refer to the following [article](https://go.microsoft.com/fwlink/?linkid=2047770&amp;clcid=0x409).</span></span>
  

