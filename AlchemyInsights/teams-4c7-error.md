---
title: Erro das equipas 4c7
ms.author: pebaum
author: pebaum
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3472"
- "9001211"
ms.openlocfilehash: 51f2aa936e803b63bcbdf73b89959cd3a1757751
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/15/2021
ms.locfileid: "51786680"
---
# <a name="4c7-error-in-microsoft-teams"></a>Erro 4c7 nas Equipas da Microsoft

Este erro ocorre porque as equipas da Microsoft requerem autenticação de formulários. Quando implementa serviços da Federação de Diretórios Ativos (AD FS), a autenticação de formulários não está ativada para a intranet por predefinição. Se a autenticação integrada do Windows falhar, é-lhe pedido que faça sedutação utilizando a Autenticação de Formulários.

Para resolver este problema, ative a autenticação de formulários utilizando o encaixe da Consola de Gestão da Microsoft (MMC) AD FS no computador que tem a cópia local do Ative Directory. Para tal, siga estes passos: 

1. No painel de navegação, procure políticas **de autenticação.**
2. Em **Ações** no painel de detalhes, **selecione Editar Autenticação Primária Global.**
3. No separador **Intranet,** selecione **Autenticação de Formulários.**
4. Selecione **OK** (ou **Aplique).**