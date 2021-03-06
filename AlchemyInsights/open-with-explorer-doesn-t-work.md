---
title: Abrir com o Explorer não funciona
ms.author: toresing
author: tomresing
manager: scotv
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: b8f07022-69fe-4112-a2f6-d3a6cedb966c
ms.openlocfilehash: 5bf28982533d8ca9998605cf3592f317c0ef99b0
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 09/14/2020
ms.locfileid: "47694467"
---
# <a name="open-with-explorer-isnt-working"></a>Abrir com o Explorer não está a funcionar

Se **abrir com o Explorer** ou a View in File **Explorer** não funcionar, certifique-se de que o serviço WebClient está definido para **executar** seguindo os passos abaixo. Por exemplo, pode levar muito tempo a abrir uma biblioteca SharePoint ou OneDrive quando o serviço não está a funcionar. 
  
1. Na caixa de pesquisa do Windows, escreva, selecione a aplicação de ambiente de trabalho Run, escreva serviços.msc e, em seguida, selecione **Enter**.
    
2. Percorra o serviço WebClient e verifique a coluna **Status.** Se o estado de serviço webClient não estiver **a funcionar,** clique duas vezes no serviço, clique em **Iniciar**e, em seguida, clique **em OK**. Ativar o serviço, se necessário, selecionando **manual** ou **automático** na caixa **do tipo Arranque.** 
    
> [!NOTE]
> Para resolver problemas de abertura no Explorador de Ficheiros, consulte [Open in Explorer](https://go.microsoft.com/fwlink/?linkid=871665). Explore a sincronização como uma alternativa melhor: [Sync SharePoint com o novo cliente de sincronização OneDrive](https://go.microsoft.com/fwlink/?linkid=871666). 
  

