---
title: Monitorização existente da resolução de problemas
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "3454"
- "9001450"
ms.openlocfilehash: 2dc9a24c1d0d808e26733738cedbc32d513926a0
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 09/14/2020
ms.locfileid: "47690722"
---
# <a name="troubleshoot-an-existing-monitor"></a><span data-ttu-id="9cb17-102">Resolução de problemas de um monitor existente</span><span class="sxs-lookup"><span data-stu-id="9cb17-102">Troubleshoot an existing monitor</span></span>

<span data-ttu-id="9cb17-103">Experimente estas soluções para resolver problemas num monitor.</span><span class="sxs-lookup"><span data-stu-id="9cb17-103">Try these solutions to troubleshoot a monitor.</span></span> 

<span data-ttu-id="9cb17-104">**Refresque o visor do monitor:**</span><span class="sxs-lookup"><span data-stu-id="9cb17-104">**Refresh your monitor's display:**</span></span>

<span data-ttu-id="9cb17-105">Prima as seguintes teclas ao mesmo tempo: Tecla do Windows + Ctrl + Shift + B. Isto irá refrescar a comunicação com o seu controlador gráfico.</span><span class="sxs-lookup"><span data-stu-id="9cb17-105">Press the following keys at the same time: Windows Key  + Ctrl + Shift + B. This will refresh communication with your graphics driver.</span></span> <span data-ttu-id="9cb17-106">Os seus monitores piscarão momentaneamente e voltarão após alguns segundos.</span><span class="sxs-lookup"><span data-stu-id="9cb17-106">Your monitors will blink momentarily and come back after a few seconds.</span></span>

<span data-ttu-id="9cb17-107">**Hardware do monitor de resolução de problemas:**</span><span class="sxs-lookup"><span data-stu-id="9cb17-107">**Troubleshoot monitor hardware:**</span></span>

1. <span data-ttu-id="9cb17-108">Desligue o cabo que liga o seu PC ao monitor e volte a ligá-lo.</span><span class="sxs-lookup"><span data-stu-id="9cb17-108">Unplug the cable connecting your PC to your monitor, and plug it back in.</span></span>
2. <span data-ttu-id="9cb17-109">Desligue quaisquer dispositivos não essenciais do seu PC (tais como adaptadores ou docas).</span><span class="sxs-lookup"><span data-stu-id="9cb17-109">Disconnect any non-essential devices from your PC (such as adapters or docks).</span></span>

<span data-ttu-id="9cb17-110">**Se instalou recentemente uma atualização no seu PC, pode reverter o controlador de exibição:**</span><span class="sxs-lookup"><span data-stu-id="9cb17-110">**If you recently installed an update on your PC, you can roll back your display driver:**</span></span>

1. <span data-ttu-id="9cb17-111">Selecione **Iniciar,** digitar **o gestor do dispositivo**e selecione Device **Manager** a partir dos resultados.</span><span class="sxs-lookup"><span data-stu-id="9cb17-111">Select **Start**, type **device manager**, and select **Device Manager** from the results.</span></span>
2. <span data-ttu-id="9cb17-112">Expanda a secção **de adaptadores do Ecrã,** clique com o botão direito do adaptador de ecrã e selecione **Propriedades**.</span><span class="sxs-lookup"><span data-stu-id="9cb17-112">Expand the **Display adapters** section, right-click your display adapter, ands select **Properties**.</span></span>
3. <span data-ttu-id="9cb17-113">Navegue no **separador Condutor** e selecione **Roll Back Driver**.</span><span class="sxs-lookup"><span data-stu-id="9cb17-113">Navigate to the **Driver** tab and select **Roll Back Driver**.</span></span> <br>
<span data-ttu-id="9cb17-114">Nota: Se isto não estiver disponível ou estiver acinzentado, selecione **Não** das opções abaixo para passar para o passo seguinte.</span><span class="sxs-lookup"><span data-stu-id="9cb17-114">Note: If this isn't available or is grayed out, select **No** from the options below to move to the next step.</span></span>
4. <span data-ttu-id="9cb17-115">Pode ser necessário reiniciar o seu PC antes que estas alterações entrem em vigor.</span><span class="sxs-lookup"><span data-stu-id="9cb17-115">You may need to restart your PC before these changes take effect.</span></span>

<span data-ttu-id="9cb17-116">**Desinstalar e reinstalar o controlador de exibição:**</span><span class="sxs-lookup"><span data-stu-id="9cb17-116">**Uninstall and reinstall your display driver:**</span></span>

1. <span data-ttu-id="9cb17-117">Selecione **Iniciar,** digitar **o gestor do dispositivo**e selecione Device **Manager** a partir dos resultados.</span><span class="sxs-lookup"><span data-stu-id="9cb17-117">Select **Start**, type **device manager**, and select **Device Manager** from the results.</span></span>
2. <span data-ttu-id="9cb17-118">Expanda a secção **de adaptadores do Ecrã,** clique com o botão direito do adaptador de ecrã e selecione **o dispositivo Desinstalar**.</span><span class="sxs-lookup"><span data-stu-id="9cb17-118">Expand the **Display adapters** section, right-click your display adapter, ands select **Uninstall device**.</span></span> 
3. <span data-ttu-id="9cb17-119">Selecione a caixa ao lado **de Eliminar o software do controlador para este dispositivo** e selecione **Desinstalar**.</span><span class="sxs-lookup"><span data-stu-id="9cb17-119">Select the box next to **Delete the driver software for this device** and select **Uninstall**.</span></span><br>
<span data-ttu-id="9cb17-120">Nota: Pode ser-lhe pedido que reinicie o computador nesta fase.</span><span class="sxs-lookup"><span data-stu-id="9cb17-120">Note: You may be asked to restart your computer at this stage.</span></span> <span data-ttu-id="9cb17-121">Certifique-se de que anota as restantes instruções antes de reiniciar.</span><span class="sxs-lookup"><span data-stu-id="9cb17-121">Make sure to write down the remaining instructions before you restart.</span></span>
4. <span data-ttu-id="9cb17-122">Abra o Gestor de Dispositivos novamente.</span><span class="sxs-lookup"><span data-stu-id="9cb17-122">Open Device Manager again.</span></span>
5. <span data-ttu-id="9cb17-123">Expanda a secção **de adaptadores do Ecrã,** clique com o botão direito no adaptador de ecrã e selecione **'Actualizar' Driver**.</span><span class="sxs-lookup"><span data-stu-id="9cb17-123">Expand the **Display adapters** section, right-click on your display adapter, and select **Update Driver**.</span></span>
6. <span data-ttu-id="9cb17-124">Selecione **Procurar automaticamente para atualizar o software do controlador** e siga as instruções de instalação.</span><span class="sxs-lookup"><span data-stu-id="9cb17-124">Select **Search automatically for update driver software** and follow the installation instructions.</span></span>