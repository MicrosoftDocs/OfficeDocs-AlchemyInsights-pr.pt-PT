---
title: Dinâmica 365 - Mostras de painel errado na interface unificada dynamics 365
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1484"
- "6200024"
ms.openlocfilehash: 3d7258bdd7366f679b048e93926ab7dfe0b956d9
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 11/15/2019
ms.locfileid: "36528562"
---
# <a name="wrong-dashboard-shows-in-dynamics-365-unified-interface"></a><span data-ttu-id="f986a-102">Painel errado mostra na interface unificada dynamics 365</span><span class="sxs-lookup"><span data-stu-id="f986a-102">Wrong dashboard shows in Dynamics 365 unified interface</span></span>

<span data-ttu-id="f986a-103">Há várias razões pelas quais você pode ver um painel diferente do que você espera:</span><span class="sxs-lookup"><span data-stu-id="f986a-103">There are several reasons why you may see a different dashboard than the one you expect:</span></span>

## <a name="the-user-has-set-a-user-default-dashboard"></a><span data-ttu-id="f986a-104">O usuário definiu um painel padrão do usuário</span><span class="sxs-lookup"><span data-stu-id="f986a-104">The user has set a user default dashboard</span></span> 

<span data-ttu-id="f986a-105">Normalmente, você pode identificar que um painel padrão do usuário é definido se o botão **Set As Default** não aparecer na barra de comando do painel.</span><span class="sxs-lookup"><span data-stu-id="f986a-105">Typically you can identify a user default dashboard is set if the **Set As Default** button does not show in the dashboard command bar.</span></span> <span data-ttu-id="f986a-106">O painel padrão do usuário substituirá todos os outros painéis padrão, mesmo que o painel padrão do usuário não esteja no aplicativo atual.</span><span class="sxs-lookup"><span data-stu-id="f986a-106">The user default dashboard will override all other default dashboards, even if the user's default dashboard is not in the current app.</span></span>

<span data-ttu-id="f986a-107">Use a seguinte solução para desdefinir seu painel padrão.</span><span class="sxs-lookup"><span data-stu-id="f986a-107">Use the following workaround to unset their default dashboard.</span></span>

1. <span data-ttu-id="f986a-108">Crie um novo painel pessoal.</span><span class="sxs-lookup"><span data-stu-id="f986a-108">Create a new personal dashboard.</span></span>

2. <span data-ttu-id="f986a-109">Defina esse novo painel como o padrão do usuário.</span><span class="sxs-lookup"><span data-stu-id="f986a-109">Set that new dashboard as the user default.</span></span>

3. <span data-ttu-id="f986a-110">Exclua esse painel.</span><span class="sxs-lookup"><span data-stu-id="f986a-110">Delete that dashboard.</span></span>

## <a name="the-dashboard-is-set-in-the-sitemap"></a><span data-ttu-id="f986a-111">O painel está definido no sitemap</span><span class="sxs-lookup"><span data-stu-id="f986a-111">The dashboard is set in the sitemap</span></span>

<span data-ttu-id="f986a-112">Você pode ter definido um painel padrão da organização selecionando um painel e escolhendo "Set As Default" em "Personalize o sistema".</span><span class="sxs-lookup"><span data-stu-id="f986a-112">You may have set an organization default dashboard by selecting a dashboard and choosing 'Set As Default' under 'Customize The System'.</span></span> <span data-ttu-id="f986a-113">Mas o painel definido no designer do sitemap terá precedência sobre este painel, se o usuário tiver acesso a ele.</span><span class="sxs-lookup"><span data-stu-id="f986a-113">But the dashboard defined in the sitemap designer will take precedence over this dashboard, if the user has access to it.</span></span>

<span data-ttu-id="f986a-114">Para que os usuários vejam o painel que você definiu como padrão da organização, você também pode:</span><span class="sxs-lookup"><span data-stu-id="f986a-114">To have users see the dashboard you've set as the organization default, you can either:</span></span>

* <span data-ttu-id="f986a-115">Defina esse painel no mapa do site</span><span class="sxs-lookup"><span data-stu-id="f986a-115">Set that dashboard in the sitemap</span></span>

* <span data-ttu-id="f986a-116">Remover o acesso ao painel definido pelo mapa do site para esses usuários</span><span class="sxs-lookup"><span data-stu-id="f986a-116">Remove access to the sitemap defined dashboard for those users</span></span>
