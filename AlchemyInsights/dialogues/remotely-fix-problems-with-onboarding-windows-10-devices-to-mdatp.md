---
title: Corrige remotamente problemas com o acesso a dispositivos do Windows 10 para o Microsoft Defender Advanced Threat Protection
ms.author: v-jmathew
author: v-jmathew
manager: dansimp
audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000760"
- "7391"
ms.openlocfilehash: 5473d090f6d4680f9a62f34f943ac6cea53b2079
ms.sourcegitcommit: 4883f1f89d4c6ca23161e9a43ff206ad21d4f09b
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 03/08/2021
ms.locfileid: "50694849"
---
# <a name="remotely-fix-problems-with-onboarding-windows-10-devices-to-microsoft-defender-advanced-threat-protection"></a><span data-ttu-id="fb70c-102">Corrige remotamente problemas com o acesso a dispositivos do Windows 10 para o Microsoft Defender Advanced Threat Protection</span><span class="sxs-lookup"><span data-stu-id="fb70c-102">Remotely fix problems with onboarding Windows 10 devices to Microsoft Defender Advanced Threat Protection</span></span>

<span data-ttu-id="fb70c-103">Se conseguir aceder ao computador remoto, siga estes passos:</span><span class="sxs-lookup"><span data-stu-id="fb70c-103">If you can access the remote computer, follow these steps:</span></span>

1. <span data-ttu-id="fb70c-104">Descarregue a ferramenta de diagnóstico [de Análise de Conectividade do Cliente.](https://go.microsoft.com/fwlink/?linkid=2143466)</span><span class="sxs-lookup"><span data-stu-id="fb70c-104">Download the [Client Connectivity Analyzer](https://go.microsoft.com/fwlink/?linkid=2143466) diagnostic tool.</span></span>
2. <span data-ttu-id="fb70c-105">Extrair e executar MDATPAnalyzer.cmd.</span><span class="sxs-lookup"><span data-stu-id="fb70c-105">Extract and run MDATPAnalyzer.cmd.</span></span>
3. <span data-ttu-id="fb70c-106">Localize o registo de diagnóstico na pasta MDATPClientAnalyzerResult, que é a mesma pasta onde a ferramenta Analyzer foi descarregada.</span><span class="sxs-lookup"><span data-stu-id="fb70c-106">Locate the diagnostic log in the MDATPClientAnalyzerResult folder, which is the same folder where the Analyzer tool was downloaded.</span></span>
4. <span data-ttu-id="fb70c-107">Para encontrar problemas com configurações de conectividade ou procuração na Internet, reveja o ficheiro de registo MDATPClientAnalyzer.txt.</span><span class="sxs-lookup"><span data-stu-id="fb70c-107">To find issues with connectivity or Internet proxy settings, review the log file MDATPClientAnalyzer.txt.</span></span>

<span data-ttu-id="fb70c-108">Para saber mais, consulte [problemas com máquinas de embarque.](https://go.microsoft.com/fwlink/?linkid=2143634)</span><span class="sxs-lookup"><span data-stu-id="fb70c-108">To learn more, see [Issues with onboarding machines](https://go.microsoft.com/fwlink/?linkid=2143634).</span></span>
