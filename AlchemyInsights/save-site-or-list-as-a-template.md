---
title: Salvar o site ou lista como um modelo
ms.author: pebaum
author: pebaum
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.assetid: 368ff1fa-82cf-4a07-986e-140b212ffc5c
ms.openlocfilehash: 627f49991aaef984f731412045351d7a1862b376
ms.sourcegitcommit: 0f0186044a3597e42ad14c32ca58e7224344dcfa
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 12/15/2019
ms.locfileid: "40048735"
---
# <a name="save-site-or-list-as-a-template"></a><span data-ttu-id="65eac-102">Salvar o site ou lista como um modelo</span><span class="sxs-lookup"><span data-stu-id="65eac-102">Save site or list as a template</span></span>

<span data-ttu-id="65eac-103">Os modelos do site SharePoint são definições pré-construídas projetadas em torno de uma determinada necessidade de negócios.</span><span class="sxs-lookup"><span data-stu-id="65eac-103">SharePoint site templates are prebuilt definitions designed around a particular business need.</span></span> <span data-ttu-id="65eac-104">Para mais informações, veja [usando modelos para criar diferentes tipos de sites sharepoint.](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4)</span><span class="sxs-lookup"><span data-stu-id="65eac-104">For more information, see [Using templates to create different kinds of SharePoint sites](https://support.office.com/article/using-templates-to-create-different-kinds-of-sharepoint-sites-449eccec-ff99-4cf3-b62e-dcfee37e8da4).</span></span>

<span data-ttu-id="65eac-105">Aqui estão alguns problemas/soluções comuns sobre salvar um site ou lista como um modelo no SharePoint Online.</span><span class="sxs-lookup"><span data-stu-id="65eac-105">Here are some common issues/solutions regarding Saving a Site or List as a template in SharePoint Online.</span></span>

<span data-ttu-id="65eac-106">Salvar o botão de modelo de **site/lista não está disponível ou ausente.**</span><span class="sxs-lookup"><span data-stu-id="65eac-106">**Save site/list template button is not available or missing**.</span></span> 

- <span data-ttu-id="65eac-107">Os administradores precisarão permitir o script personalizado para ativar os recursos do modelo.</span><span class="sxs-lookup"><span data-stu-id="65eac-107">Administrators will need to Allow Custom Script to enable the template features.</span></span> <span data-ttu-id="65eac-108">Para etapas detalhadas, exemplos e considerações [consulte Permitir ou impedir o script personalizado.](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script)</span><span class="sxs-lookup"><span data-stu-id="65eac-108">For detailed steps, examples and considerations see [Allow or prevent custom script](https://docs.microsoft.com/sharepoint/allow-or-prevent-custom-script).</span></span>


- <span data-ttu-id="65eac-109">O site Save como comando de modelo não é suportado e pode causar problemas em sites que usam a infraestrutura de publicação de servidores sharepoint.</span><span class="sxs-lookup"><span data-stu-id="65eac-109">The Save site as template command is not supported and can cause problems on sites that use the SharePoint Server Publishing Infrastructure.</span></span>


<span data-ttu-id="65eac-110">**O modelo do site não pode ser criado ou não funciona corretamente**</span><span class="sxs-lookup"><span data-stu-id="65eac-110">**The site template cannot be created or does not work correctly**</span></span>

- <span data-ttu-id="65eac-111">O modelo pode estar faltando um [recurso](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) e não será ativado.</span><span class="sxs-lookup"><span data-stu-id="65eac-111">The template may be missing a [feature](https://social.technet.microsoft.com/wiki/contents/articles/14423.sharepoint-2013-existing-features-guid.aspx) and won’t activate.</span></span> <span data-ttu-id="65eac-112">Se o recurso não estiver disponível para ativar na coleção do site atual, você não pode usar o modelo do site para criar um site.</span><span class="sxs-lookup"><span data-stu-id="65eac-112">If the feature is not available to activate in the current site collection, you cannot use the site template to create a site.</span></span>


- <span data-ttu-id="65eac-113">Verifique se há listas ou bibliotecas excedendo o limite de visualização de [lista](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) de 5.000 itens, pois isso pode bloquear a criação de um modelo do site.</span><span class="sxs-lookup"><span data-stu-id="65eac-113">Check to see if any lists or libraries exceed the [List View Limit Threshold](https://support.office.com/article/Manage-large-lists-and-libraries-in-SharePoint-B8588DAE-9387-48C2-9248-C24122F07C59) of 5000 items as this can block creation of a site template.</span></span>


- <span data-ttu-id="65eac-114">O site pode estar usando muitos recursos e, portanto, o modelo do site excede o limite de 50 megabytes (MB).</span><span class="sxs-lookup"><span data-stu-id="65eac-114">The site may be using too many resources and therefore the site template exceeds the 50 megabyte (MB) limit.</span></span>


- <span data-ttu-id="65eac-115">Há problemas para exibir dados de uma lista que usa uma coluna de pesquisa.</span><span class="sxs-lookup"><span data-stu-id="65eac-115">There are problems displaying data from a list that uses a lookup column.</span></span> <span data-ttu-id="65eac-116">Para obter mais informações, consulte a [lista gerada pelo Modelo não exibir dados da lista de pesquisa correta no SharePoint Online.](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data)</span><span class="sxs-lookup"><span data-stu-id="65eac-116">For more information, see [Template-generated list doesn’t display data from the correct lookup list in SharePoint Online](https://docs.microsoft.com/sharepoint/support/lists-and-libraries/template-generated-list-incorrect-data).</span></span>


<span data-ttu-id="65eac-117">Para obter informações mais detalhadas sobre problemas e soluções comuns, por favor, faça referência, [crie e use modelos](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989)do site.</span><span class="sxs-lookup"><span data-stu-id="65eac-117">For more detailed information on common problems and solutions please reference, [Create and use site templates](https://support.office.com/article/Create-and-use-site-templates-60371B0F-00E0-4C49-A844-34759EBDD989).</span></span>

