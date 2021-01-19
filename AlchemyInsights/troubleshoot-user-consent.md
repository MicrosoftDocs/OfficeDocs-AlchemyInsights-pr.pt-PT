---
title: Resolução de problemas consentimento do utilizador
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 01/18/2021
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004353"
- "7785"
ms.openlocfilehash: 7249bafe1b047c66d9351a79f1782cfcc1a936a1
ms.sourcegitcommit: 7b213fd5e8a3fdb5c602673dc194d576d372ac96
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 01/18/2021
ms.locfileid: "49901633"
---
# <a name="troubleshoot-user-consent"></a><span data-ttu-id="197a3-102">Resolução de problemas consentimento do utilizador</span><span class="sxs-lookup"><span data-stu-id="197a3-102">Troubleshoot user consent</span></span>

1. <span data-ttu-id="197a3-103">Pode configurar como os utilizadores finais concordam com as aplicações através do Portal Azure ou PowerShell.</span><span class="sxs-lookup"><span data-stu-id="197a3-103">You can configure how end-users consent to applications through the Azure Portal or PowerShell.</span></span> <span data-ttu-id="197a3-104">Consulte [as definições de consentimento do Utilizador](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent?tabs=azure-portal#user-consent-settings) para obter mais informações.</span><span class="sxs-lookup"><span data-stu-id="197a3-104">See [User consent settings](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent?tabs=azure-portal#user-consent-settings) for more information.</span></span>
1. <span data-ttu-id="197a3-105">Um administrador também pode usar a [API do Gráfico microsoft](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent?tabs=azure-portal#user-consent-settings) para conceder consentimento a permissões delegadas em nome de um único utilizador.</span><span class="sxs-lookup"><span data-stu-id="197a3-105">An administrator can also use the [Microsoft Graph API](https://docs.microsoft.com/azure/active-directory/manage-apps/configure-user-consent?tabs=azure-portal#user-consent-settings) to grant consent to delegated permissions on behalf of a single user.</span></span> <span data-ttu-id="197a3-106">Para mais informações, consulte [Obter acesso em nome de um utilizador](https://docs.microsoft.com/graph/auth-v2-user).</span><span class="sxs-lookup"><span data-stu-id="197a3-106">For more information, see [Get access on behalf of a user](https://docs.microsoft.com/graph/auth-v2-user).</span></span>
1. <span data-ttu-id="197a3-107">[Erros de Consentimento do Utilizador](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-error): este artigo discute erros que podem ocorrer durante o processo de consentimento para uma aplicação.</span><span class="sxs-lookup"><span data-stu-id="197a3-107">[User Consent Errors](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-error): this article discusses errors that can occur during the process of consenting to an application.</span></span> <span data-ttu-id="197a3-108">Se estiver a resolver pedidos de consentimento inesperados que não contenham mensagens de erro, consulte [Cenários de Autenticação para Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-error).</span><span class="sxs-lookup"><span data-stu-id="197a3-108">If you are troubleshooting unexpected consent prompts that do not contain any error messages, see [Authentication Scenarios for Azure AD](https://docs.microsoft.com/azure/active-directory/manage-apps/application-sign-in-unexpected-user-consent-error).</span></span>