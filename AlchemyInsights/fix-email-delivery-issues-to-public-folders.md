---
title: Corrija problemas de entrega de e-mail para pastas públicas via correio
ms.author: chrisda
author: chrisda
manager: dansimp
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1956"
- "3500007"
ms.openlocfilehash: 74a26306766ed7952a3bbbcb06f1f0113a113024
ms.sourcegitcommit: 9fd002ce49ad9a7e58c3eb997a8063e2e1feab55
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 10/06/2020
ms.locfileid: "48366475"
---
# <a name="fix-email-delivery-issues-to-mail-enabled-public-folders"></a>Corrija problemas de entrega de e-mail para pastas públicas via correio

Se os remetentes externos não puderem enviar mensagens para as suas pastas públicas ativadas por correio e os remetentes receberem o erro: **não foi possível encontrar (550 5.4.1)**, verifique se o domínio de e-mail da pasta pública está configurado como um domínio de retransmissão interno em vez de um domínio autoritário:

1. Abra o [Centro de Administração Exchange (EAC)](https://docs.microsoft.com/Exchange/exchange-admin-center).

2. Ir para **o fluxo de correio** \> **Domínios aceitos,** selecione o domínio aceite e, em seguida, clique em **Editar**.

3. Na página de propriedades que abre, se o tipo de domínio estiver definido como **Autoritário,** altere o valor para **relé Interno** e, em seguida, clique em **Guardar**.

Se os remetentes externos receberem o **erro, não tem permissão (550 5.7.13)**, executar o seguinte comando no [Exchange Online PowerShell](https://docs.microsoft.com/powershell/exchange/exchange-online/connect-to-exchange-online-powershell/connect-to-exchange-online-powershell) para ver as permissões para utilizadores anónimos na pasta pública:

`Get-PublicFolderClientPermission -Identity "<PublicFolderIdentity>" -User Anonymous` Por exemplo, `Get-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous` .

Para permitir que utilizadores externos enviem e-mails para esta pasta pública, adicione o acesso createItems ao utilizador Anonymous. Por exemplo, `Add-PublicFolderClientPermission -Identity "\Customer Discussion" -User Anonymous -AccessRights CreateItems` .
