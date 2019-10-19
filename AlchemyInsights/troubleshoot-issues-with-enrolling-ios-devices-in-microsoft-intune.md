---
title: Solucionar problemas com a inscrição de dispositivos iOS no Microsoft Intune
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 10/24/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: d717bcc9-1cc1-44f6-b5e6-c1bc059c1973
ms.openlocfilehash: bdbfe7bae00a4c5cfa0edbe9a37522cc98e52401
ms.sourcegitcommit: 037331d71f06750d972c0b6278b23bb15c4806ca
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 10/18/2019
ms.locfileid: "36507014"
---
# <a name="troubleshoot-issues-with-enrolling-ios-devices-in-microsoft-intune"></a>Solucionar problemas com a inscrição de dispositivos iOS no Microsoft Intune

Revise os recursos listados abaixo para resolver o problema agora. 
  
Algumas mensagens de erro comuns e etapas de resolução:
  
- **Cap dispositivo atingido** O usuário tem mais dispositivos inscritos do que o limite do dispositivo. Revise esses documentos para [remover um dispositivo](https://docs.microsoft.com/intune/devices-wipe) ou [alterar o limite do dispositivo](https://docs.microsoft.com/intune/enrollment-restrictions-set#set-device-limit-restrictions).
    
- **Este serviço não é suportado. Nenhuma política de inscrição:** o Apple Push Notification Service (APNS) precisa ser configurado ou renovado. Revise [este documento](https://docs.microsoft.com/intune/apple-mdm-push-certificate-get) para obter instruções sobre como fazer isso. 
    
- **Tipo de licença de usuário inválido ou nome de usuário não reconhecido:** O usuário precisa receber uma licença do Intune ou do EMS. Revise esses documentos para atribuir uma licença por meio de: [centro de administração do Office](https://docs.microsoft.com/intune/licenses-assign) ou [portal do Azure](https://docs.microsoft.com/azure/active-directory/license-users-groups).
    
Recursos adicionais para ajudar a resolver o problema:
  
1. Use o [portal de solução de problemas do Intune](https://devicemanagement.microsoft.com/#blade/Microsoft_Intune_DeviceSettings/TroubleshootBlade) para diagnosticar e resolver falhas de registro comuns. Revise [este documento](https://docs.microsoft.com/intune/help-desk-operators) para obter mais detalhes. 
    
2. Revise esses documentos para obter uma lista de erros comuns que impedem o registro e as resoluções para cada um: [Guia de solução de problemas](https://support.microsoft.com/help/4039809/troubleshooting-ios-device-enrollment-in-intune) e solução de [problemas doc](https://docs.microsoft.com/intune-classic/troubleshoot/troubleshoot-device-enrollment-in-intune).
    
3. [Saiba como inscrever dispositivos IOS no Microsoft Intune](https://docs.microsoft.com/intune/ios-enroll).
    

