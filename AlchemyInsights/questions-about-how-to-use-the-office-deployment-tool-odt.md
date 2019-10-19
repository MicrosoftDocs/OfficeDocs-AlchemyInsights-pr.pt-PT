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
# <a name="questions-about-how-to-use-the-office-deployment-tool-odt"></a>Perguntas sobre como usar a ferramenta de implantação do Office (ODT)

Transfira a ferramenta de implementação do Office a partir do [centro de transferências da Microsoft](http://go.microsoft.com/fwlink/p/?LinkID=626065).
  
Depois de baixar o arquivo, execute o arquivo executável de extração automática, que contém o executável da ferramenta de implantação do Office (Setup. exe) e um arquivo de configuração de exemplo (Configuration. xml).
  
 **Para excluir ou remover produtos do Office 365 ProPlus de computadores cliente:**
  
Ao instalar o Office 365 ProPlus, você pode excluir produtos específicos. Para fazer isso, siga as etapas para instalar o Office com a ODT, mas inclua o elemento ExcludeApp no arquivo de configuração. Por exemplo, esse arquivo de configuração instala todos os produtos do Office 365 ProPlus, exceto o Publisher:
  
```
<Add SourcePath="\\Server\share" Version="15.1.2.3" OfficeClientEdition="32">
    <Product ID="O365ProPlusRetail" >
      <Language ID="en-us" />
      <ExcludeApp ID="Publisher" />
    </Product>
</Add>
```

[Visão geral da ferramenta de implantação do Office](https://docs.microsoft.com/deployoffice/overview-of-the-office-2016-deployment-tool)
  

