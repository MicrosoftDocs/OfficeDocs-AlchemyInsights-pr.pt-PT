---
title: Activar ATP do Office 365 para SharePoint, OneDrive e equipas da Microsoft
ms.author: deniseb
author: denisebmsft
manager: laurawi
ms.date: 04/01/2019
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Admin_O365
ms.custom: 3100021
ms.openlocfilehash: ae2f574663ae3233a056589c2d5a578171f3b2f4
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/23/2019
ms.locfileid: "32403044"
---
# <a name="enable-office-365-advanced-threat-protection-for-sharepoint-online-onedrive-and-microsoft-teams"></a><span data-ttu-id="ede88-102">Activar a protecção do Office 365 ameaça avançadas para SharePoint Online, OneDrive e equipas da Microsoft</span><span class="sxs-lookup"><span data-stu-id="ede88-102">Enable Office 365 Advanced Threat Protection for SharePoint Online, OneDrive, and Microsoft Teams</span></span>

1. <span data-ttu-id="ede88-103">Vá para https://protection.office.com e iniciar sessão.</span><span class="sxs-lookup"><span data-stu-id="ede88-103">Go to https://protection.office.com and sign in.</span></span>
2. <span data-ttu-id="ede88-104">Escolher **Gestão ameaças** > **política** > **Anexos seguros**.</span><span class="sxs-lookup"><span data-stu-id="ede88-104">Choose **Threat management** > **Policy** > **Safe Attachments**.</span></span>
3. <span data-ttu-id="ede88-105">Seleccione **Activar ATP para SharePoint, OneDrive e equipas da Microsoft**e, em seguida, clique em **Guardar**.</span><span class="sxs-lookup"><span data-stu-id="ede88-105">Select **Turn on ATP for SharePoint, OneDrive, and Microsoft Teams**, and then click **Save**.</span></span>
4. <span data-ttu-id="ede88-106">(Recomendado) Como um administrador global ou um administrador do SharePoint Online, execute o cmdlet [Conjunto SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) com o parâmetro **DisallowInfectedFileDownload** definido como *true*.</span><span class="sxs-lookup"><span data-stu-id="ede88-106">(Recommended) As a global administrator or a SharePoint Online administrator, run the [Set-SPOTenant](https://docs.microsoft.com/powershell/module/sharepoint-online/Set-SPOTenant?view=sharepoint-ps) cmdlet with the **DisallowInfectedFileDownload** parameter set to *true*.</span></span>
5. <span data-ttu-id="ede88-107">(Recomendado) [Configurar alertas](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) para ficheiros detectados.</span><span class="sxs-lookup"><span data-stu-id="ede88-107">(Recommended) [Set up alerts](https://docs.microsoft.com/office365/securitycompliance/turn-on-atp-for-spo-odb-and-teams#set-up-alerts-for-detected-files) for detected files.</span></span>

> [!NOTE]
> <span data-ttu-id="ede88-108">ATP será nPara pesquisa todos os ficheiros só no Online do SharePoint, OneDrive ou Teams da Microsoft.</span><span class="sxs-lookup"><span data-stu-id="ede88-108">ATP will nto scan every single file in SharePoint Online, OneDrive, or Microsoft Teams.</span></span> <span data-ttu-id="ede88-109">Ficheiros são analisados de forma assíncrona, através de um processo que utiliza eventos de actividade de partilha e de convidado, bem como heurística avançada e sinais de ameaça para identificar ficheiros maliciosos.</span><span class="sxs-lookup"><span data-stu-id="ede88-109">Files are scanned asynchronously, through a process that uses sharing and guest activity events, along with smart heuristics and threat signals to identify malicious files.</span></span> <span data-ttu-id="ede88-110">Consulte [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span><span class="sxs-lookup"><span data-stu-id="ede88-110">See [https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams](https://docs.microsoft.com/office365/securitycompliance/atp-for-spo-odb-and-teams).</span></span>