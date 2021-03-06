---
title: Inventário de dispositivos intune
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/27/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "1281"
- "6700008"
ms.openlocfilehash: 5d2be7485be8578f7fdee3216dc6f3970be67fd1
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 09/14/2020
ms.locfileid: "47667889"
---
# <a name="intune-device-inventory"></a>Inventário de dispositivos intune

A lâmina devices fornece ao administrador informações sobre os dispositivos sob gestão no Intune por cada dispositivo. As informações apresentadas incluem: Hardware, aplicações descobertas, estado de conformidade do dispositivo e estado de configuração do dispositivo.

Os dados de inventário para hardware e aplicações descobertas são recolhidos num ciclo de sete dias. As aplicações e elementos específicos de hardware reportados diferem consoante o sistema operativo do dispositivo e se o dispositivo é de propriedade pessoal ou corporativa.

Para mais informações, [consulte os detalhes do dispositivo no Intune.](https://docs.microsoft.com/intune/device-inventory)

**FAQ**

P: Não estou a receber uma lista completa de aplicações presentes em dispositivos Windows matriculados no Intune. Porque não?

R: Neste momento, apenas aplicações modernas estão listadas para computadores Windows 10 que são identificados como dispositivos corporativos. A Intune não recolhe informações sobre as aplicações Win32 instaladas nestes dispositivos.

P: Por que os números de telefone não são recolhidos de todos os dispositivos?

R: Os telefones categorizados como dispositivos corporativos no Intune não são identificados com o seu número de telefone completo quando, por exemplo, você executou um relatório de inventário de dispositivos móveis. Os números de telefone do dispositivo Bring-you são sempre parcialmente mascarados com asteriscos (****), e mostram apenas os últimos quatro dígitos.