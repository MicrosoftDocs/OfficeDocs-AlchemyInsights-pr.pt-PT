---
title: Problemas de sessão nas aplicações da Microsoft 365
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
- "9000571"
- "2556"
ms.openlocfilehash: e6cbab7401fd6168041e7fc31ac97e3be036536d
ms.sourcegitcommit: 8bc60ec34bc1e40685e3976576e04a2623f63a7c
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/15/2021
ms.locfileid: "51833050"
---
# <a name="blank-sign-in-screen-in-microsoft-365-apps"></a><span data-ttu-id="f12ab-102">Ecrã de sindução em branco nas aplicações da Microsoft 365</span><span class="sxs-lookup"><span data-stu-id="f12ab-102">Blank sign-in screen in Microsoft 365 apps</span></span>

<span data-ttu-id="f12ab-103">Para corrigir este problema, experimente o seguinte:</span><span class="sxs-lookup"><span data-stu-id="f12ab-103">To fix this issue, try the following:</span></span>
- <span data-ttu-id="f12ab-104">Instale as atualizações mais recentes para [windows](https://support.microsoft.com/help/4027667/windows-10-update) e [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span><span class="sxs-lookup"><span data-stu-id="f12ab-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="f12ab-105">Redefinir as opções do Internet Explorer: Vá a **Ferramentas**  >  **Opções** de Internet  >    >  **Versões avançadas do Internet Reset (note** que perderá as definições personalizadas) e tente iniciar novamente a sessão no Office.</span><span class="sxs-lookup"><span data-stu-id="f12ab-105">Reset Internet Explorer options: Go to **Tools** > **Internet Options** > **Advanced** > **Reset Internet Explorer Settings** (note that you will lose custom settings), and then try signing in to Office again.</span></span>
- <span data-ttu-id="f12ab-106">Desative a Proteção de Aplicações do Windows Defender (WDAG) ou qualquer programa semelhante de firewall ou antivírus:</span><span class="sxs-lookup"><span data-stu-id="f12ab-106">Disable the Windows Defender Application Guard (WDAG) or any similar firewall or anti-virus program:</span></span>
    1. <span data-ttu-id="f12ab-107">No Painel de Controlo, vá a Programas e, em seguida, escolha as **funcionalidades** **Turn Windows ligados ou desligados**.</span><span class="sxs-lookup"><span data-stu-id="f12ab-107">In Control Panel, go to **Programs**, and then choose **Turn Windows features on or off**.</span></span>
    2. <span data-ttu-id="f12ab-108">Se o Windows Defender Application Guard estiver ativado, tente desativá-lo.</span><span class="sxs-lookup"><span data-stu-id="f12ab-108">If Windows Defender Application Guard is enabled, try disabling it.</span></span><br/>
    <span data-ttu-id="f12ab-109">**Nota:** Pode ser necessário reiniciar o computador.</span><span class="sxs-lookup"><span data-stu-id="f12ab-109">**Note:** You may need to restart the computer.</span></span>
- <span data-ttu-id="f12ab-110">Certifique-se de que o plug-in Microsoft.AAD.BrokerPlugin [AAD WAM](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) não está a ser bloqueado por qualquer aplicação ou programa de firewall/antivírus.</span><span class="sxs-lookup"><span data-stu-id="f12ab-110">Ensure that the Microsoft.AAD.BrokerPlugin [AAD WAM plug-in](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) is not being blocked by any application or firewall/anti-virus program.</span></span>
- <span data-ttu-id="f12ab-111">[Credenciais de Escritório Claro](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) usando Gestor credencial do Windows.</span><span class="sxs-lookup"><span data-stu-id="f12ab-111">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="f12ab-112">**Nota:** Os percursos de registo do Office 2016 mudaram para 16,0.</span><span class="sxs-lookup"><span data-stu-id="f12ab-112">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="f12ab-113">(Ex: \Software\Microsoft\Office\16.0\Common\Identidade\)</span><span class="sxs-lookup"><span data-stu-id="f12ab-113">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>

<span data-ttu-id="f12ab-114">Para obter mais informações, consulte [os problemas de ligação no sôm-in após a atualização do Office 2016 construir 16.0.7967 no Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span><span class="sxs-lookup"><span data-stu-id="f12ab-114">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>