---
title: Problemas de início de sessão em aplicações do Office
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9000571"
- "2556"
ms.openlocfilehash: 08bb0a94066f071f2ba0e9c54378f0d479191496
ms.sourcegitcommit: 699ac3b0d66e0640f8e933eba3c2a4ba1cfcf3c7
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 07/30/2019
ms.locfileid: "35938303"
---
# <a name="blank-sign-in-screen-in-office-apps"></a><span data-ttu-id="496c2-102">Ecrã de início de sessão em branco em aplicações do Office</span><span class="sxs-lookup"><span data-stu-id="496c2-102">Blank sign-in screen in Office apps</span></span>

<span data-ttu-id="496c2-103">Para corrigir este problema, tente o seguinte:</span><span class="sxs-lookup"><span data-stu-id="496c2-103">To fix this issue, try the following:</span></span>
- <span data-ttu-id="496c2-104">Instale as actualizações mais recentes para o [Windows](https://support.microsoft.com/help/4027667/windows-10-update) e [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span><span class="sxs-lookup"><span data-stu-id="496c2-104">Install the latest updates for [Windows](https://support.microsoft.com/help/4027667/windows-10-update) and [Office](https://support.office.com/article/update-office-and-your-computer-with-microsoft-update-2ab296f3-7f03-43a2-8e50-46de917611c5).</span></span>
- <span data-ttu-id="496c2-105">Repor Opções do Internet Explorer: vá para **Ferramentas** > **Opções da Internet** > **Avançadas** > **Repor definições do Internet Explorer** (note que irá perder as definições personalizadas) e, em seguida, tente iniciar novamente sessão no Office.</span><span class="sxs-lookup"><span data-stu-id="496c2-105">Reset Internet Explorer options: Go to **Tools** > **Internet Options** > **Advanced** > **Reset Internet Explorer Settings** (note that you will lose custom settings), and then try signing in to Office again.</span></span>
- <span data-ttu-id="496c2-106">Desactive o Windows Defender aplicação Guard (WDAG) ou qualquer programa de firewall ou antivírus semelhante:</span><span class="sxs-lookup"><span data-stu-id="496c2-106">Disable the Windows Defender Application Guard (WDAG) or any similar firewall or anti-virus program:</span></span>
    1. <span data-ttu-id="496c2-107">No painel de controlo, vá para **programas**e, em seguida, escolha **Activar funcionalidades do Windows ou desactivar**.</span><span class="sxs-lookup"><span data-stu-id="496c2-107">In Control Panel, go to **Programs**, and then choose **Turn Windows features on or off**.</span></span>
    2. <span data-ttu-id="496c2-108">Se estiver activada a protecção de aplicação do Windows Defender, tente desactivá-la.</span><span class="sxs-lookup"><span data-stu-id="496c2-108">If Windows Defender Application Guard is enabled, try disabling it.</span></span><br/>
    <span data-ttu-id="496c2-109">**Nota:** Tem de reiniciar o computador.</span><span class="sxs-lookup"><span data-stu-id="496c2-109">**Note:** You may need to restart the computer.</span></span>
- <span data-ttu-id="496c2-110">Certifique-se de que a Microsoft.AAD.BrokerPlugin [Das WAM Plug-in](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) não está a ser bloqueado por qualquer aplicação ou programa de firewall/anti-antivírus.</span><span class="sxs-lookup"><span data-stu-id="496c2-110">Ensure that the Microsoft.AAD.BrokerPlugin [AAD WAM plug-in](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016#symptom-1) is not being blocked by any application or firewall/anti-virus program.</span></span>
- <span data-ttu-id="496c2-111">[Office Limpar credenciais](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) utilizando o Gestor de credenciais do Windows.</span><span class="sxs-lookup"><span data-stu-id="496c2-111">[Clear Office credentials](https://docs.microsoft.com/office/troubleshoot/error-messages/another-account-already-signed-in#step-3-clear-cached-credentials-on-the-computer) using Windows Credential Manager.</span></span><br/>
    <span data-ttu-id="496c2-112">**Nota:** Os caminhos de registo para o Office 2016 foram alterados para 16,0.</span><span class="sxs-lookup"><span data-stu-id="496c2-112">**Note:** The registry paths for Office 2016 have changed to 16.0.</span></span> <span data-ttu-id="496c2-113">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span><span class="sxs-lookup"><span data-stu-id="496c2-113">(Ex: \Software\Microsoft\Office\16.0\Common\Identity\)</span></span>

<span data-ttu-id="496c2-114">Para mais informações, consulte [problemas de ligação no início de sessão-in após a actualização do Office de 2016 compilação 16.0.7967 10 do Windows](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span><span class="sxs-lookup"><span data-stu-id="496c2-114">For more information, see [Connection issues in sign-in after update to Office 2016 build 16.0.7967 on Windows 10](https://docs.microsoft.com/office365/troubleshoot/administration/connection-issue-when-sign-in-office-2016).</span></span>