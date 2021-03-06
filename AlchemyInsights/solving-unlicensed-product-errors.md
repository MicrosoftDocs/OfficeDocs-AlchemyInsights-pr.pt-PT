---
title: Resolução de erros de produto não licenciados
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
- "3412"
- "9001428"
ms.openlocfilehash: eebfb7cea7ae97921bf3c3667818400a17b5e52e
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/15/2021
ms.locfileid: "51786860"
---
# <a name="suggestions-for-solving-unlicensed-product-errors"></a>Sugestões para resolver erros de "Produto Não Licenciado"

Para resolver erros sobre um "Produto Não Licenciado", experimente o seguinte:

- Verifique se o seu estado de subscrição expirou.
- Certifique-se de que tem uma subscrição que permite licenças de clientes, como aplicações microsoft 365 para negócios ou Business Premium, e [certifique-se de que o utilizador tem uma licença atribuída.](https://docs.microsoft.com/microsoft-365/admin/add-users/add-users) 
- Certifique-se de que o utilizador está a iniciar sessão no Office com a mesma conta que tem a licença atribuída.
- Consulte a [página de saúde](https://docs.microsoft.com/office365/enterprise/view-service-health) do Serviço para ver se existem problemas conhecidos com o serviço.
- Verifique as definições de firewall, antivírus e proxy para confirmar que não estão a bloquear o acesso das aplicações da Microsoft 365 à Internet. Consulte [os intervalos de endereços URLs e IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).

Pode também experimentar as seguintes ações de resolução de problemas: 

- Abra uma aplicação do Office e [assine fora](https://support.office.com/article/5a20dc11-47e9-4b6f-945d-478cb6d92071) de quaisquer contas de utilizador existentes. [Remova](https://docs.microsoft.com/microsoft-365/admin/manage/remove-licenses-from-users) e [reatribua](https://docs.microsoft.com/microsoft-365/admin/manage/assign-licenses-to-users) a licença do Office e, em seguida, [inscreva-se no Office](https://support.office.com/article/628ea040-f265-49de-b986-be09c3ebf8a9) utilizando a conta de utilizador afetada.
- Executar o [Resolução de Problemas de Ativação](https://aka.ms/SARA-OfficeActivation-Alchemy).
- [Reponha o estado de ativação do Office](https://docs.microsoft.com/office365/troubleshoot/activation/reset-office-365-proplus-activation-state). 
- [Realizar uma Reparação Online do Escritório.](https://support.office.com/Article/7821d4b6-7c1d-4205-aa0e-a6b40c5bb88b)

Para soluções adicionais de resolução de problemas, consulte: 

- [Erros de Produto Não Licenciado e de ativação no Office](https://support.office.com/Article/0d23d3c0-c19c-4b2f-9845-5344fedc4380)
- [Erro "Desculpe, mas não conseguimos ligar-nos à sua conta. Tente novamente mais tarde" ao ativar o Office](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365)