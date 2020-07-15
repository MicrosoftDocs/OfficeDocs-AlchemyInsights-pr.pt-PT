---
title: Problemas com máquinas de embarque
ms.author: pebaum
author: pebaum
manager: scotv
ms.date: 07/14/2020
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.collection: Adm_O365
ms.custom:
- "6023"
- "9002913"
ms.openlocfilehash: 19b516dc21472e2c80a8b9046f802b329d15e4d6
ms.sourcegitcommit: 45c2aaeee58c0be466b76c7f0cd71e796d3c8f76
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 07/15/2020
ms.locfileid: "45141657"
---
# <a name="issues-with-onboarding-machines"></a><span data-ttu-id="84618-102">Problemas com máquinas de embarque</span><span class="sxs-lookup"><span data-stu-id="84618-102">Issues with onboarding machines</span></span>

<span data-ttu-id="84618-103">Pode ter problemas com máquinas de bordo para o serviço MDATP.</span><span class="sxs-lookup"><span data-stu-id="84618-103">You might have issues with onboarding machines to MDATP service.</span></span> <span data-ttu-id="84618-104">Se conseguir aceder à máquina do utilizador final, siga estes passos:</span><span class="sxs-lookup"><span data-stu-id="84618-104">If you can access the end-user machine, follow these steps:</span></span>

1. <span data-ttu-id="84618-105">Descarregue a ferramenta de diagnóstico [de Análise de Conectividade do Cliente.](https://aka.ms/mdatpanalyzer)</span><span class="sxs-lookup"><span data-stu-id="84618-105">Download the [Client Connectivity Analyzer](https://aka.ms/mdatpanalyzer) diagnostic tool.</span></span>
2. <span data-ttu-id="84618-106">Extrair e executar MDATPAnalyzer.cmd.</span><span class="sxs-lookup"><span data-stu-id="84618-106">Extract and run MDATPAnalyzer.cmd.</span></span>
3. <span data-ttu-id="84618-107">Localizar o registo de diagnóstico na pasta chamada MDATPClientAnalyzerResult, a mesma pasta onde a ferramenta Analyzer é descarregada.</span><span class="sxs-lookup"><span data-stu-id="84618-107">Locate the diagnostic log in the folder called MDATPClientAnalyzerResult, the same folder where the Analyzer tool is downloaded.</span></span>
4. <span data-ttu-id="84618-108">Reveja o ficheiro de registo, MDATPClientAnalyzer.txt, para encontrar problemas de configuração de conectividade ou procuração de internet.</span><span class="sxs-lookup"><span data-stu-id="84618-108">Review the log file, MDATPClientAnalyzer.txt, to find connectivity or internet proxy settings issues.</span></span>