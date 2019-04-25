---
title: Identificar a actividade de regra de pasta a receber em registos de auditoria
ms.author: chrisda
author: chrisda
manager: serdars
ms.date: ''
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom: 1368
ms.assetid: ''
ms.openlocfilehash: 9339d9c58056f568dc994b75bffe39f2c8bbdd34
ms.sourcegitcommit: 9d78905c512192ffc4675468abd2efc5f2e4baf4
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 04/23/2019
ms.locfileid: "32417257"
---
# <a name="identify-inbox-rule-activity-in-audit-logs"></a><span data-ttu-id="21a98-102">Identificar a actividade de regra de pasta a receber em registos de auditoria</span><span class="sxs-lookup"><span data-stu-id="21a98-102">Identify inbox rule activity in audit logs</span></span>

<span data-ttu-id="21a98-103">Pode utilizar procura de registo de auditoria em & o Security Center de conformidade para ver eventos de regra de pasta a receber (criar, modificar e eliminar regras da pasta a receber).</span><span class="sxs-lookup"><span data-stu-id="21a98-103">You can use audit log search in the Security & Compliance Center to view inbox rule events (creating, modifying, and deleting inbox rules).</span></span>

1. <span data-ttu-id="21a98-104">Inicie sessão para o [Centro de conformidade do Office 365 segurança &](https://protection.office.com/)</span><span class="sxs-lookup"><span data-stu-id="21a98-104">Log in to the [Office 365 Security & Compliance Center](https://protection.office.com/)</span></span>

2. <span data-ttu-id="21a98-105">Clique em **Procurar e de investigação** e seleccione a **Procura de registo de auditoria**.</span><span class="sxs-lookup"><span data-stu-id="21a98-105">Click **Search and Investigation** and select **Audit Log Search**.</span></span>

3. <span data-ttu-id="21a98-106">Seleccione o intervalo de datas nos campos **data de início** e **data de fim** .</span><span class="sxs-lookup"><span data-stu-id="21a98-106">Select the date range in the **Start date** and **End date** fields.</span></span>

4. <span data-ttu-id="21a98-107">Em **Actividades de correio do Exchange**, verifique se o campo de **actividades** é definido como **InboxRule novo criar/modificar/activar/desactivar a regra de pasta a receber**.</span><span class="sxs-lookup"><span data-stu-id="21a98-107">Under **Exchange Mailbox Activities**, verify the **Activities** field is set to **New-InboxRule Create/modify/enable/disable inbox rule**.</span></span>

5. <span data-ttu-id="21a98-108">Clique em **Procurar**.</span><span class="sxs-lookup"><span data-stu-id="21a98-108">Click **Search**.</span></span>

<span data-ttu-id="21a98-109">Nos resultados, seleccione um registo de auditoria.</span><span class="sxs-lookup"><span data-stu-id="21a98-109">In the results, select an audit record.</span></span> <span data-ttu-id="21a98-110">Na lista de opções de detalhes, clique em **Mais informações**.</span><span class="sxs-lookup"><span data-stu-id="21a98-110">In the details flyout, click **More Information**.</span></span> <span data-ttu-id="21a98-111">Informações sobre as definições de regra de pasta a receber são apresentadas no campo **parâmetros** .</span><span class="sxs-lookup"><span data-stu-id="21a98-111">Information about the inbox rule settings is displayed in the **Parameters** field.</span></span>

<span data-ttu-id="21a98-112">Para mais informações, consulte a [determinar se um utilizador que criou uma regra de pasta a receber](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span><span class="sxs-lookup"><span data-stu-id="21a98-112">For more information, see [Determining if a user created an inbox rule](https://docs.microsoft.com//office365/securitycompliance/auditing-troubleshooting-scenarios#determining-if-a-user-created-an-inbox-rule)</span></span>