---
title: Perguntas sobre como usar a ferramenta de implantação do Office (ODT)
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 4/26/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 3e88e0f3-c86d-4ab8-b076-59d0552318f9
ms.openlocfilehash: 604fc200517316de6e0194bd64e6eb3039cfa61b
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 10/18/2019
ms.locfileid: "36553551"
---
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a><span data-ttu-id="bc114-102">Perguntas sobre como usar a ferramenta de implantação do Office (ODT)</span><span class="sxs-lookup"><span data-stu-id="bc114-102">Questions about how to use the Office Deployment Tool (ODT)</span></span>

<span data-ttu-id="bc114-103">Transfira a ferramenta de implementação do Office a partir do [centro de transferências da Microsoft](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span><span class="sxs-lookup"><span data-stu-id="bc114-103">Download the Office Deployment Tool from the [Microsoft Download Center](http://go.microsoft.com/fwlink/p/?LinkID=626065).</span></span>
  
<span data-ttu-id="bc114-104">Depois de baixar o arquivo, execute o arquivo executável de extração automática, que contém o executável da ferramenta de implantação do Office (Setup. exe) e um arquivo de configuração de exemplo (Configuration. xml).</span><span class="sxs-lookup"><span data-stu-id="bc114-104">After downloading the file, run the self-extracting executable file, which contains the Office Deployment Tool executable (setup.exe) and a sample configuration file (configuration.xml).</span></span>
  
 <span data-ttu-id="bc114-105">**Para excluir ou remover produtos do Office 365 ProPlus de computadores cliente:**</span><span class="sxs-lookup"><span data-stu-id="bc114-105">**To exclude or remove Office 365 ProPlus products from client computers:**</span></span>
  
<span data-ttu-id="bc114-106">Ao instalar o Office 365 ProPlus, você pode excluir produtos específicos.</span><span class="sxs-lookup"><span data-stu-id="bc114-106">When installing Office 365 ProPlus, you can exclude specific products.</span></span> <span data-ttu-id="bc114-107">Para fazer isso, siga as etapas para instalar o Office com a ODT, mas inclua o elemento ExcludeApp no arquivo de configuração.</span><span class="sxs-lookup"><span data-stu-id="bc114-107">To do so, follow the steps for installing Office with the ODT, but include the ExcludeApp element in your configuration file.</span></span> <span data-ttu-id="bc114-108">Por exemplo, esse arquivo de configuração instala todos os produtos do Office 365 ProPlus, exceto o Publisher:</span><span class="sxs-lookup"><span data-stu-id="bc114-108">For example, this configuration file installs all the Office 365 ProPlus products except Publisher:</span></span>
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[<span data-ttu-id="bc114-109">Visão geral da ferramenta de implantação do Office</span><span class="sxs-lookup"><span data-stu-id="bc114-109">Overview of the Office Deployment Tool</span></span>](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

