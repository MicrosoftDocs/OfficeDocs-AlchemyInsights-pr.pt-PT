---
title: Acesso negado ao visualizar um fluxo de trabalho
ms.author: pebaum
author: Techwriter40
ms.date: 11/27/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 47ceb983-f9a4-4c55-a40c-03d5c3d75dc9
ms.openlocfilehash: 4ca65583fbd98867026e9e3cc8f36fe38798aa85
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 10/18/2019
ms.locfileid: "36747759"
---
# <a name="access-denied-when-viewing-a-workflow"></a>Acesso negado ao visualizar um fluxo de trabalho

SharePoint 2013 fluxos de trabalho que tentam enviar um email para um grupo do SharePoint podem falhar com uma mensagem de erro "acesso negado" se a associação do grupo do SharePoint não estiver definida para todos.
  
 **Para resolver esse problema, execute estas etapas:**
  
 1. Permitir que todos vejam os membros do grupo do SharePoint.
  
 2. Remova o grupo do SharePoint da linha para ou CC do email.
  
 3. Adicione explicitamente os usuários à linha para ou CC se a visibilidade da associação não puder ser alterada para o grupo do SharePoint.
  
Para ver mais detalhes, consulte [http não autorizado para/_vti_bin/Client.svc/SP.Utilities.Utility.SendEmail](https://go.microsoft.com/fwlink/?linkid=2044694&amp;clcid=0x409).
  