---
title: Identificar o endereço IP e o cliente nos registos de auditoria
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1367
ms.assetid: ''
ms.openlocfilehash: 7e30a638de5926aa11b8ae637613a48076d7bdc9
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/23/2019
ms.locfileid: "32417011"
---
# <a name="identify-ip-address-and-client-in-audit-logs"></a><span data-ttu-id="cc2af-102">Identificar o endereço IP e o cliente nos registos de auditoria</span><span class="sxs-lookup"><span data-stu-id="cc2af-102">Identify IP address and client in audit logs</span></span>

<span data-ttu-id="cc2af-103">O endereço IP que corresponde a uma actividade por um utilizador ou administrador é mostrado nos registos de auditoria.</span><span class="sxs-lookup"><span data-stu-id="cc2af-103">The IP address that corresponds to an activity by a user or administrator is shown in the Audit Logs.</span></span> <span data-ttu-id="cc2af-104">As informações de cliente também estão registadas.</span><span class="sxs-lookup"><span data-stu-id="cc2af-104">The client information is also logged.</span></span> <span data-ttu-id="cc2af-105">Eis os passos para identificar essas informações</span><span class="sxs-lookup"><span data-stu-id="cc2af-105">Here are the steps to identifying such information</span></span>

1. <span data-ttu-id="cc2af-106">Inicie sessão para o [Centro de conformidade do Office 365 segurança &](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="cc2af-106">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="cc2af-107">Clique em **Procurar e de investigação** e seleccione a **Procura de registo de auditoria**.</span><span class="sxs-lookup"><span data-stu-id="cc2af-107">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

   <span data-ttu-id="cc2af-108">Se estiver interessado numa actividade específica, seleccione-a lista de **actividades** .</span><span class="sxs-lookup"><span data-stu-id="cc2af-108">If you're interested in a specific activity, select it from **Activities** list.</span></span> <span data-ttu-id="cc2af-109">Caso contrário, todas as actividades serão devolvidas para o utilizador seleccionado (predefinição).</span><span class="sxs-lookup"><span data-stu-id="cc2af-109">If not, all activities will be returned for the selected user (default setting).</span></span>

   <span data-ttu-id="cc2af-110">**Nota**: certas actividades podem não estar disponíveis no menu de **actividades** ; No entanto, os itens de auditoria será devolvido se **Mostrar os resultados para todas as actividades** é seleccionada (predefinição).</span><span class="sxs-lookup"><span data-stu-id="cc2af-110">**Note**: Certain activities may not be available in the **Activities** menu; however, those audit items will be returned if **Show Results for all activities** is selected (default setting).</span></span>

3. <span data-ttu-id="cc2af-111">Especificar o nome de utilizador no campo **utilizadores** , seleccione o intervalo de data apropriada para a actividade e, em seguida, clique em **Procurar**.</span><span class="sxs-lookup"><span data-stu-id="cc2af-111">Specify the username in the **Users** field, select the appropriate date range for the activity, and then click **Search**.</span></span>

<span data-ttu-id="cc2af-112">Os resultados, pode ver o endereço IP para essa actividade no painel de resultados.</span><span class="sxs-lookup"><span data-stu-id="cc2af-112">In the results, you can see the IP address for that activity in the results pane.</span></span> <span data-ttu-id="cc2af-113">Seleccione o registo de auditoria para ver informações detalhadas na lista de opções **Detalhes** (por exemplo, cliente, utilizador que executou a acção, etc.).</span><span class="sxs-lookup"><span data-stu-id="cc2af-113">Select the audit record to see detailed information in the **Details** flyout (for example, Client, User that performed action, etc.).</span></span>

<span data-ttu-id="cc2af-114">Para mais informações, consulte a [localização do endereço IP do computador utilizado para aceder a uma conta comprometida](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span><span class="sxs-lookup"><span data-stu-id="cc2af-114">For more information, see [Finding the IP address of the computer used to access a compromised account](https://docs.microsoft.com/office365/securitycompliance/auditing-troubleshooting-scenarios#finding-the-ip-address-of-the-computer-used-to-access-a-compromised-account).</span></span>