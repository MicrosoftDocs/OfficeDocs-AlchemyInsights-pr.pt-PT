---
title: Dynamics 365 forma regras de negócios - regra de negócios não disparar por um formulário
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1926"
- "6200018"
ms.openlocfilehash: 3cdd2175083e864b3bffc57a70bb6c6220843fad
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 11/15/2019
ms.locfileid: "37769350"
---
# <a name="onchange-event-does-not-occur-if-the-field-is-changed-programmatically"></a><span data-ttu-id="f3754-102">O evento OnChange não ocorre se o campo for alterado programaticamente</span><span class="sxs-lookup"><span data-stu-id="f3754-102">OnChange event does not occur if the field is changed programmatically</span></span>

<span data-ttu-id="f3754-103">O evento *OnChange* não ocorre se o campo for alterado programaticamente usando o *atributo.* [método setValue.](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue)</span><span class="sxs-lookup"><span data-stu-id="f3754-103">The *OnChange* event does not occur if the field is changed programmatically using the *attribute.*[setValue](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/setvalue) method.</span></span> <span data-ttu-id="f3754-104">Se você quiser que os manipuladores de eventos para o evento *OnChange* sejam executados depois de definir o valor, você deve usar o método *formContext.data.entity atribuir* o método [fireOnchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) em seu código.</span><span class="sxs-lookup"><span data-stu-id="f3754-104">If you want event handlers for the *OnChange* event to run after you set the value you must use the *formContext.data.entity attribute* [fireOnchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/attributes/fireonchange) method in your code.</span></span>

[https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange](https://docs.microsoft.com/dynamics365/customer-engagement/developer/clientapi/reference/events/attribute-onchange)
