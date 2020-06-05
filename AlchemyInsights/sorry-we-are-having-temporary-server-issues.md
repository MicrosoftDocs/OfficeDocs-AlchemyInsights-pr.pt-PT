---
title: Corrigir aplicações da Microsoft 365 Desculpe, estamos tendo mensagem temporária de problemas de servidor
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3420"
- "9001430"
ms.openlocfilehash: 6db04a437de8e50af349b5c690791981ae872f14
ms.sourcegitcommit: f28dafa0f727870038f72bc904da926daf4ec07b
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 06/05/2020
ms.locfileid: "44582714"
---
# <a name="fixing-the-microsoft-365-apps-sorry-we-are-having-temporary-server-issues-message"></a><span data-ttu-id="8f91c-102">Correção das aplicações microsoft 365 "Desculpe, estamos tendo problemas temporários de servidor"</span><span class="sxs-lookup"><span data-stu-id="8f91c-102">Fixing the Microsoft 365 apps "Sorry, we are having temporary server issues" message</span></span>

<span data-ttu-id="8f91c-103">Se receber esta mensagem, experimente o seguinte:</span><span class="sxs-lookup"><span data-stu-id="8f91c-103">If you receive this message, try the following:</span></span>

1. <span data-ttu-id="8f91c-104">Verifique as definições de firewall, antivírus e proxy para confirmar que não estão a bloquear o acesso à Internet às aplicações da Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="8f91c-104">Check your firewall, antivirus software, and proxy settings to confirm that they are not blocking Internet access to Microsoft 365 apps.</span></span> <span data-ttu-id="8f91c-105">Consulte [os intervalos de endereços URLs e IP](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span><span class="sxs-lookup"><span data-stu-id="8f91c-105">See [URLs and IP address ranges](https://docs.microsoft.com/office365/enterprise/urls-and-ip-address-ranges).</span></span>

2. <span data-ttu-id="8f91c-106">Ir para **start**  >  **run**e, em seguida, escrever **serviços.msc**.</span><span class="sxs-lookup"><span data-stu-id="8f91c-106">Go to **Start** > **Run**, and then type **services.msc**.</span></span> <span data-ttu-id="8f91c-107">Certifique-se de que todos os seguintes serviços estão em funcionamento:</span><span class="sxs-lookup"><span data-stu-id="8f91c-107">Make sure that the following services are all running:</span></span>
    - <span data-ttu-id="8f91c-108">Configuração automática de dispositivos ligados à rede</span><span class="sxs-lookup"><span data-stu-id="8f91c-108">Network Connected Devices Auto-Setup</span></span>
    - <span data-ttu-id="8f91c-109">Serviço de Lista de Rede</span><span class="sxs-lookup"><span data-stu-id="8f91c-109">Network List Service</span></span>
    - <span data-ttu-id="8f91c-110">Consciência de localização da rede</span><span class="sxs-lookup"><span data-stu-id="8f91c-110">Network Location Awareness</span></span>
    - <span data-ttu-id="8f91c-111">Registo de eventos do Windows</span><span class="sxs-lookup"><span data-stu-id="8f91c-111">Windows Event Log</span></span>

<span data-ttu-id="8f91c-112">Se um destes serviços não estiver a funcionar, tente iniciá-lo.</span><span class="sxs-lookup"><span data-stu-id="8f91c-112">If one of these services is not running, try to start it.</span></span> <span data-ttu-id="8f91c-113">Se tiver algum problema em iniciar o serviço, executar o seguinte comando abrindo um pedido de comando com permissões elevadas:</span><span class="sxs-lookup"><span data-stu-id="8f91c-113">If you have a problem starting the service, run the following command by opening a command prompt with elevated permissions:</span></span>

<span data-ttu-id="8f91c-114">**sfc /scannow**</span><span class="sxs-lookup"><span data-stu-id="8f91c-114">**sfc /scannow**</span></span>

<span data-ttu-id="8f91c-115">Depois de terminar este comando, reinicie o computador.</span><span class="sxs-lookup"><span data-stu-id="8f91c-115">After this command finishes, restart the computer.</span></span>

<span data-ttu-id="8f91c-116">Para obter informações detalhadas, consulte ["Desculpe, não podemos ligar-nos à sua conta. Por favor, tente novamente mais tarde" erro quando ativar](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span><span class="sxs-lookup"><span data-stu-id="8f91c-116">For detailed information, see ["Sorry, we can't connect to your account. Please try again later" error when you activate](https://docs.microsoft.com/office/troubleshoot/activation-installation/issue-when-activate-office-from-office-365).</span></span>