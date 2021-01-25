---
title: Consulta da Microsoft Graph API
ms.author: v-jmathew
author: v-jmathew
manager: scotv
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004345"
- "7846"
ms.openlocfilehash: 527e88c7b3cb1cc4f5535e3b0d2bc4d8d1163336
ms.sourcegitcommit: 029c4697b77ce996d41ca74c4fa86de1bb84bd99
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 01/25/2021
ms.locfileid: "49974682"
---
# <a name="querying-the-microsoft-graph-api"></a><span data-ttu-id="a449f-102">Consulta da Microsoft Graph API</span><span class="sxs-lookup"><span data-stu-id="a449f-102">Querying the Microsoft Graph API</span></span>

<span data-ttu-id="a449f-103">Este tópico também pode aplicar-se aos desenvolvedores que ainda utilizam AZure AD Graph API.</span><span class="sxs-lookup"><span data-stu-id="a449f-103">This topic may also apply to developers still using Azure AD Graph API.</span></span> <span data-ttu-id="a449f-104">No entanto, recomenda-se **vivamente** que utilize o Microsoft Graph para todos os cenários de gestão de diretórios, identidades e acessos.</span><span class="sxs-lookup"><span data-stu-id="a449f-104">However, it is **strongly** recommended that you use Microsoft Graph for all your directory, identity, and access management scenarios.</span></span>

<span data-ttu-id="a449f-105">**Questões de autenticação ou autorização**</span><span class="sxs-lookup"><span data-stu-id="a449f-105">**Authentication or authorization issues**</span></span>

- <span data-ttu-id="a449f-106">Se a sua aplicação **não conseguir adquirir fichas** para ligar para o Microsoft Graph, escolha **Problema com a obtenção de um token de acesso (Autenticação)** da categoria Microsoft Graph para obter ajuda e suporte mais específicos sobre este tópico.</span><span class="sxs-lookup"><span data-stu-id="a449f-106">If your app is **unable to acquire tokens** to call Microsoft Graph, pick **Problem with getting an access token (Authentication)** Microsoft Graph category to get more specific help and support on this topic.</span></span>
- <span data-ttu-id="a449f-107">Se a sua aplicação estiver **a receber erros de autorização de 401 ou 403** ao ligar para o Microsoft Graph, escolha a categoria **API de um erro negado de acesso (Autorização)** da Microsoft para obter ajuda e suporte mais específicos sobre este tópico.</span><span class="sxs-lookup"><span data-stu-id="a449f-107">If your app is **receiving 401 or 403 authorization errors** when calling Microsoft Graph, pick the **Getting an access denied error (Authorization)** Microsoft Graph API category to get more specific help and support on this topic.</span></span>

<span data-ttu-id="a449f-108">**Quero usar o Microsoft Graph, mas não sei por onde começar.**</span><span class="sxs-lookup"><span data-stu-id="a449f-108">**I want to use Microsoft Graph, but not sure where to start**</span></span>

<span data-ttu-id="a449f-109">Para saber mais sobre o Microsoft Graph, consulte:</span><span class="sxs-lookup"><span data-stu-id="a449f-109">To learn more about Microsoft Graph, see:</span></span>

- [<span data-ttu-id="a449f-110">Visão geral do Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="a449f-110">Overview of Microsoft Graph</span></span>](https://docs.microsoft.com/graph/overview)
- [<span data-ttu-id="a449f-111">Visão geral da gestão de identidade e acesso no Gráfico do Microsoft</span><span class="sxs-lookup"><span data-stu-id="a449f-111">Overview of Identity and Access Management in Microsoft Graph</span></span>](https://docs.microsoft.com/graph/azuread-identity-access-management-concept-overview)
- [<span data-ttu-id="a449f-112">Começar a construir aplicativos Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="a449f-112">Getting started building Microsoft Graph apps</span></span>](https://docs.microsoft.com/graph/)
- <span data-ttu-id="a449f-113">**Microsoft Graph Explorer** - Teste ApIs de Gráfico microsoft no seu inquilino ou inquilino de demonstração</span><span class="sxs-lookup"><span data-stu-id="a449f-113">**Microsoft Graph Explorer** - Test Microsoft Graph APIs in your tenant or a demo tenant</span></span>

<span data-ttu-id="a449f-114">**Quero usar o Microsoft Graph, mas suporta as APIs do diretório v1.0 que preciso?**</span><span class="sxs-lookup"><span data-stu-id="a449f-114">**I want to use Microsoft Graph, but does it support the v1.0 directory APIs I need?**</span></span>

<span data-ttu-id="a449f-115">O Microsoft Graph é a API recomendada para a gestão de diretórios, identidades e acessos.</span><span class="sxs-lookup"><span data-stu-id="a449f-115">Microsoft Graph is the recommended API for directory, identity, and access management.</span></span> <span data-ttu-id="a449f-116">No entanto, existem ainda algumas lacunas entre o que é possível no Azure AD Graph e microsoft Graph.</span><span class="sxs-lookup"><span data-stu-id="a449f-116">However, there are still a few gaps between what is possible in Azure AD Graph and Microsoft Graph.</span></span> <span data-ttu-id="a449f-117">Reveja os seguintes artigos, que destacam as diferenças mais atualizadas para ajudar na sua escolha:</span><span class="sxs-lookup"><span data-stu-id="a449f-117">Review the following articles, which highlight the most up-to-date differences to assist in your choice:</span></span>

- [<span data-ttu-id="a449f-118">Diferenças de tipo de recurso entre gráfico AD Ad Azure e Gráfico microsoft</span><span class="sxs-lookup"><span data-stu-id="a449f-118">Resource type differences between Azure AD Graph and Microsoft Graph</span></span>](https://docs.microsoft.com/graph/migrate-azure-ad-graph-resource-differences)
- [<span data-ttu-id="a449f-119">Diferenças de propriedade entre O Gráfico AD AZure e Gráfico microsoft</span><span class="sxs-lookup"><span data-stu-id="a449f-119">Property differences between Azure AD Graph and Microsoft Graph</span></span>](https://docs.microsoft.com/graph/migrate-azure-ad-graph-property-differences)
- [<span data-ttu-id="a449f-120">Diferenças de método entre Azure AD e Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="a449f-120">Method differences between Azure AD and Microsoft Graph</span></span>](https://docs.microsoft.com/graph/migrate-azure-ad-graph-method-differences)

<span data-ttu-id="a449f-121">**Quando questiono o objeto do *utilizador,* muitas das suas propriedades estão em falta**</span><span class="sxs-lookup"><span data-stu-id="a449f-121">**When I query the *user* object, many of its properties are missing**</span></span>

<span data-ttu-id="a449f-122">`GET https://graph.microsoft.com/v1.0/users` apenas devolve 11 propriedades, uma vez que o Microsoft Graph seleciona automaticamente um conjunto predefinido de propriedades do *utilizador* para devolver.</span><span class="sxs-lookup"><span data-stu-id="a449f-122">`GET https://graph.microsoft.com/v1.0/users` only returns 11 properties, as Microsoft Graph auto-selects a default set of *user* properties to return.</span></span> <span data-ttu-id="a449f-123">Se precisar de outras propriedades *do utilizador,* utilize $select para escolher as propriedades de que a sua aplicação necessita.</span><span class="sxs-lookup"><span data-stu-id="a449f-123">If you need other *user* properties, use $select to pick the properties your application needs.</span></span> <span data-ttu-id="a449f-124">Experimente primeiro no **Microsoft Graph Explorer.**</span><span class="sxs-lookup"><span data-stu-id="a449f-124">Try it out in **Microsoft Graph Explorer** first.</span></span>

<span data-ttu-id="a449f-125">**Alguns valores de propriedade do utilizador são *nulos,* embora eu saiba que estão definidos**</span><span class="sxs-lookup"><span data-stu-id="a449f-125">**Some user property values are *null* even though I know they are set**</span></span>

<span data-ttu-id="a449f-126">A explicação mais provável é que o pedido tinha sido concedido à permissão *User.ReadBasic.All.*</span><span class="sxs-lookup"><span data-stu-id="a449f-126">The most likely explanation is that the application had been granted the *User.ReadBasic.All* permission.</span></span> <span data-ttu-id="a449f-127">Isto permite que a aplicação leia um conjunto limitado de propriedades do utilizador, devolvendo todas as outras propriedades como nulas, mesmo que tenham sido previamente definidas.</span><span class="sxs-lookup"><span data-stu-id="a449f-127">This allows the application to read a limited set of user properties, returning all other properties as null even if they have been previously set.</span></span> <span data-ttu-id="a449f-128">Tente conceder a aplicação *User.Read.All* permission in instead.</span><span class="sxs-lookup"><span data-stu-id="a449f-128">Try granting the application *User.Read.All* permission instead.</span></span>

<span data-ttu-id="a449f-129">Para obter mais informações, consulte [as permissões do utilizador do Microsoft Graph](https://docs.microsoft.com/graph/permissions-reference#user-permissions).</span><span class="sxs-lookup"><span data-stu-id="a449f-129">For more information, see [Microsoft Graph user permissions](https://docs.microsoft.com/graph/permissions-reference#user-permissions).</span></span>

<span data-ttu-id="a449f-130">**Estou com dificuldade em usar parâmetros de consulta OData para filtrar dados nos meus pedidos**</span><span class="sxs-lookup"><span data-stu-id="a449f-130">**I'm having trouble using OData query parameters to filter data in my requests**</span></span>

<span data-ttu-id="a449f-131">Embora o Microsoft Graph suporte uma vasta gama de parâmetros de consulta OData, muitos desses parâmetros não são totalmente suportados por serviços de diretório (recursos que herdam do *directórioObject)* no Microsoft Graph.</span><span class="sxs-lookup"><span data-stu-id="a449f-131">While Microsoft Graph supports a wide range of the OData query parameters, many of those parameters are not fully supported by directory services (resources that inherit from *directoryObject*) in Microsoft Graph.</span></span> <span data-ttu-id="a449f-132">As mesmas limitações que estavam presentes no Azure AD Graph persistem na maior parte do Microsoft Graph:</span><span class="sxs-lookup"><span data-stu-id="a449f-132">The same limitations that were present in Azure AD Graph persist for the most part in Microsoft Graph:</span></span>

1. <span data-ttu-id="a449f-133">**Não apoiado:**$count, $search e $filter em *valores nulos* ou *não nulos*</span><span class="sxs-lookup"><span data-stu-id="a449f-133">**Not supported**: $count, $search, and $filter on *null* or *not null* values</span></span>
2. <span data-ttu-id="a449f-134">**Não suportado**: $filter sobre determinadas propriedades (ver tópicos de recursos sobre os quais as propriedades são filtradas)</span><span class="sxs-lookup"><span data-stu-id="a449f-134">**Not supported**: $filter on certain properties (see resource topics on which properties are filterable)</span></span>
3. <span data-ttu-id="a449f-135">**Não suportado:** paging, filtragem e triagem ao mesmo tempo</span><span class="sxs-lookup"><span data-stu-id="a449f-135">**Not supported**: paging, filtering, and sorting at the same time</span></span>
4. <span data-ttu-id="a449f-136">**Não suportado:** filtrar uma relação.</span><span class="sxs-lookup"><span data-stu-id="a449f-136">**Not supported**: filtering on a relationship.</span></span> <span data-ttu-id="a449f-137">Por exemplo - encontre todos os membros do grupo de engenharia que estão no Reino Unido.</span><span class="sxs-lookup"><span data-stu-id="a449f-137">For example - find all members of the engineering group that are in the UK.</span></span>
5. <span data-ttu-id="a449f-138">**Suporte parcial**: $orderby no *utilizador* (só no nome do utilizador e no userPrincipalName) e *no grupo*</span><span class="sxs-lookup"><span data-stu-id="a449f-138">**Partial support**: $orderby on *user* (displayName and userPrincipalName only) and *group*</span></span>
6. <span data-ttu-id="a449f-139">**Suporte parcial**: $filter (suporta apenas *o suporte eq*, começa *com*, *ou*, *e* limitou *qualquer suporte*) $expand (expandir as relações de um único objeto devolve todas as relações, mas expandir uma coleção de relacionamentos de objetos é limitada)</span><span class="sxs-lookup"><span data-stu-id="a449f-139">**Partial support**: $filter (supports only *eq*, *startswith*, *or*, *and*, and limited *any*) support, $expand (expanding a single object's relationships returns all relationships, but expanding a collection of objects' relationships is limited)</span></span>

<span data-ttu-id="a449f-140">Para obter mais informações, consulte [Personalizar respostas com parâmetros de consulta.](https://docs.microsoft.com/graph/query-parameters)</span><span class="sxs-lookup"><span data-stu-id="a449f-140">For more information, see [Customize responses with query parameters](https://docs.microsoft.com/graph/query-parameters).</span></span>

<span data-ttu-id="a449f-141">**A API que estou a ligar não funciona, onde posso fazer mais testes?**</span><span class="sxs-lookup"><span data-stu-id="a449f-141">**The API I'm calling doesn't work - where can I do more testing?**</span></span>

<span data-ttu-id="a449f-142">**Microsoft Graph Explorer** - Teste APIs do Microsoft Graph no seu inquilino ou inquilino de demonstração e também confira as consultas de **amostra** no Microsoft Graph Explorer.</span><span class="sxs-lookup"><span data-stu-id="a449f-142">**Microsoft Graph Explorer** - Test Microsoft Graph APIs in your tenant or a demo tenant and also check out the **sample queries** in Microsoft Graph Explorer.</span></span>

<span data-ttu-id="a449f-143">**Quando faço perguntas sobre dados, parece que recebo um conjunto de dados incompleto**</span><span class="sxs-lookup"><span data-stu-id="a449f-143">**When I query for data it seems like I get an incomplete data set back**</span></span>

<span data-ttu-id="a449f-144">Se estiver a consultar uma coleção (como *utilizadores),* o Microsoft Graph utiliza os limites da página do lado do servidor para que os resultados sejam sempre devolvidos com um tamanho de página padrão.</span><span class="sxs-lookup"><span data-stu-id="a449f-144">If you are querying a collection (like *users*), Microsoft Graph uses server-side page limits so results are always returned with a default page-size.</span></span> <span data-ttu-id="a449f-145">A sua aplicação deve sempre esperar página através de coleções devolvidas do serviço.</span><span class="sxs-lookup"><span data-stu-id="a449f-145">Your app should always expect to page through collections returned from the service.</span></span>

<span data-ttu-id="a449f-146">Para mais informações, consulte:</span><span class="sxs-lookup"><span data-stu-id="a449f-146">For more information, see:</span></span>

- [<span data-ttu-id="a449f-147">As melhores práticas do Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="a449f-147">Microsoft Graph best practices</span></span>](https://docs.microsoft.com/graph/best-practices-concept)
- [<span data-ttu-id="a449f-148">Paging dados do Microsoft Graph na sua app</span><span class="sxs-lookup"><span data-stu-id="a449f-148">Paging Microsoft Graph data in your app</span></span>](https://docs.microsoft.com/graph/paging)

<span data-ttu-id="a449f-149">**A minha aplicação é muito lenta e também está a ser estrangulada. Que melhorias posso fazer?**</span><span class="sxs-lookup"><span data-stu-id="a449f-149">**My app is too slow and is also getting throttled. What improvements can I make?**</span></span>

<span data-ttu-id="a449f-150">Dependendo do seu cenário, existem várias opções à sua disposição para tornar a sua aplicação mais performante e, em alguns casos, menos propensa a ser estrangulada pelo serviço (quando está a fazer demasiadas chamadas).</span><span class="sxs-lookup"><span data-stu-id="a449f-150">Depending on your scenario, there are a variety of different options at your disposal to make your application more performant, and in some cases, less prone to being throttled by the service (when you are making too many calls).</span></span>

<span data-ttu-id="a449f-151">Para saber mais informações, consulte os artigos:</span><span class="sxs-lookup"><span data-stu-id="a449f-151">To learn more, see:</span></span>

- [<span data-ttu-id="a449f-152">As melhores práticas do Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="a449f-152">Microsoft Graph best practices</span></span>](https://docs.microsoft.com/graph/best-practices-concept)
- [<span data-ttu-id="a449f-153">Pedidos de loteamento</span><span class="sxs-lookup"><span data-stu-id="a449f-153">Batching requests</span></span>](https://docs.microsoft.com/graph/json-batching)
- [<span data-ttu-id="a449f-154">Mudanças de faixa através da consulta delta</span><span class="sxs-lookup"><span data-stu-id="a449f-154">Track changes through delta query</span></span>](https://docs.microsoft.com/graph/delta-query-overview)
- [<span data-ttu-id="a449f-155">Ser notificado das alterações através de webhooks</span><span class="sxs-lookup"><span data-stu-id="a449f-155">Get notified of changes through webhooks</span></span>](https://docs.microsoft.com/graph/webhooks)
- [<span data-ttu-id="a449f-156">Orientação de estrangulamento</span><span class="sxs-lookup"><span data-stu-id="a449f-156">Throttling guidance</span></span>](https://docs.microsoft.com/graph/throttling)

<span data-ttu-id="a449f-157">**Onde posso encontrar mais informações sobre erros e questões conhecidas?**</span><span class="sxs-lookup"><span data-stu-id="a449f-157">**Where can I find more information on errors and known issues?**</span></span>

- [<span data-ttu-id="a449f-158">Informações de resposta a erros do Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="a449f-158">Microsoft Graph error response information</span></span>](https://docs.microsoft.com/graph/errors)
- [<span data-ttu-id="a449f-159">Problemas conhecidos com o Microsoft Graph</span><span class="sxs-lookup"><span data-stu-id="a449f-159">Known issues with Microsoft Graph</span></span>](https://docs.microsoft.com/graph/known-issues)

<span data-ttu-id="a449f-160">**Onde posso verificar o estado da disponibilidade de serviço e conectividade?**</span><span class="sxs-lookup"><span data-stu-id="a449f-160">**Where can I check status of service availability and connectivity?**</span></span>

<span data-ttu-id="a449f-161">A disponibilidade de serviço e conectividade dos serviços subjacentes que podem ser acedidos através do Microsoft Graph podem ter impacto na disponibilidade e desempenho globais do Microsoft Graph.</span><span class="sxs-lookup"><span data-stu-id="a449f-161">The service availability and connectivity of the underlying services that can be accessed through Microsoft Graph can impact the overall availability and performance of Microsoft Graph.</span></span>

- <span data-ttu-id="a449f-162">Para a saúde do serviço de diretório ativo Azure, verifique o estado dos serviços de **Segurança + Identidade** listados na página de estado do [Azure](https://azure.microsoft.com/status/).</span><span class="sxs-lookup"><span data-stu-id="a449f-162">For Azure Active Directory service health, check the status of **Security + Identity** services listed in the [Azure status page](https://azure.microsoft.com/status/).</span></span>
- <span data-ttu-id="a449f-163">Para os serviços do Office que contribuem para o Microsoft Graph, verifique o estado dos serviços listados no [Painel de Saúde do Office Service](https://portal.office.com/adminportal/home#/servicehealth).</span><span class="sxs-lookup"><span data-stu-id="a449f-163">For Office services that contribute to Microsoft Graph, check the status of services listed in the [Office Service Health Dashboard](https://portal.office.com/adminportal/home#/servicehealth).</span></span>
