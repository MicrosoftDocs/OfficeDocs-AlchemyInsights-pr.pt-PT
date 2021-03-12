---
title: Sharepoint Online PowerShell
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 04/21/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000266"
- "1867"
ms.openlocfilehash: b7580f0e609d21bdc13fc07fda0bfd15bdb7a7ca
ms.sourcegitcommit: 0eb4f9bde53395b5fd4b5cd4ffc56ca96db91298
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 03/10/2021
ms.locfileid: "50709081"
---
# <a name="sharepoint-online-powershell"></a>Sharepoint Online PowerShell

Trabalhar com PowerShell ou Scripts dentro do Sharepoint Online? Visite os links abaixo para mais informações.
- [Começar com a SharePoint Online Management Shell](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps)
- [Ligue ao SPO PowerShell com a autenticação multifactor (MFA)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-online/connect-sharepoint-online?view=sharepoint-ps#to-connect-with-multifactor-authentication-mfa)
- [SharePoint Patterns and Practices (PnP)](https://docs.microsoft.com/powershell/sharepoint/sharepoint-pnp/sharepoint-pnp-cmdlets?view=sharepoint-ps) contém uma biblioteca de comandos PowerShell que lhe permite executar ações de gestão complexas em relação ao SPO.

> [!NOTE]
> - Se tiver problemas de ligação com a concha de gestão SPO, [certifique-se](https://docs.microsoft.com/powershell/scripting/developer/module/importing-a-powershell-module?view=powershell-7.1) de que atualizou a versão mais recente e tente re importar o módulo utilizando *"Import-Module Microsoft.Online.SharePoint.PowerShell".*
> - Se estiver a tentar executar scripts de modelos de objetos do lado do cliente, terá de ter os [Componentes de Cliente Online do Sharepoint SDK instalados](https://www.microsoft.com/download/details.aspx?id=42038) na sua máquina local.
> - Se tiver problemas em executar scripts a partir de PowerShell, pode considerar executar o PowerShell como administrador e alterar a [Política de Execução](https://docs.microsoft.com/powershell/module/microsoft.powershell.core/about/about_execution_policies?view=powershell-6).