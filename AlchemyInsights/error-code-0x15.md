---
title: Código de Erro 0x15
ms.author: pebaum
author: pebaum
ms.date: 04/21/2020
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "919"
- "2000022"
ms.assetid: 0d566afe-b21f-4f1b-8ca9-4b4d3b0f5435
description: Se estiver a receber um erro ao ativar o Office 2013 nas implementações dos Serviços de Ambiente de Trabalho Remoto (RDS), considere ativar a ADAL editando o registo.
ms.openlocfilehash: 566d63cbe37d295b3546b9d7d5b14dfc8e8fe0ec
ms.sourcegitcommit: 55eff703a17e500681d8fa6a87eb067019ade3cc
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/22/2020
ms.locfileid: "43703149"
---
# <a name="error-while-activation-office-2013-on-remote-desktop-services"></a>Erro durante a ativação do Office 2013 em Serviços de Ambiente de Trabalho Remoto

Se estiver a receber um erro ao ativar o Office 2013 nas implementações dos Serviços de Ambiente de Trabalho Remoto (RDS), considere ativar a ADAL editando o registo.
  
|**Chave de registo**|**Tipo**|**Valor**|
|:-----|:-----|:-----|
|HKEY_CURRENT_USER\Software\Microsoft\Office\15.0\Common\Identity\enableaDAL  <br/> |REG_DWORD  <br/> |1  <br/> |

Para mais informações, consulte [Enable Modern Authentication for Office 2013 nos dispositivos Windows](https://docs.microsoft.com/office365/admin/security-and-compliance/enable-modern-authentication).
  
> [!NOTE]
>  O ADAL está ativado por padrão nas Aplicações Microsoft 365 para empresas e Office 2016. Os Serviços de Ambiente de Trabalho Remoto (RDS) foram previamente nomeados Serviços de Terminal.
  