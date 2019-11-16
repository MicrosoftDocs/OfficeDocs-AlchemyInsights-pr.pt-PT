---
title: ConsistênciaGuia / fonteComportamento âncora
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 5/2/2018
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom: ''
ms.assetid: 6a44f797-acc7-4cbe-aa5a-47e2581fabf5
ms.openlocfilehash: f0ff94a8e46f1fb4e0ac8653c51f8f651e29498b
ms.sourcegitcommit: b43f77221f47b50c41197a448a9c26c423ce1ad5
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 11/15/2019
ms.locfileid: "36517004"
---
# <a name="consistencyguid--sourceanchor-behavior"></a><span data-ttu-id="17f85-102">ConsistênciaGuia / fonteComportamento âncora</span><span class="sxs-lookup"><span data-stu-id="17f85-102">ConsistencyGuid / sourceAnchor behavior</span></span>

<span data-ttu-id="17f85-103">O Azure AD Connect (versão 1.1.524.0 e depois) agora facilita o uso de msDS-ConsistencyGuid como atributo fonteAnchor.</span><span class="sxs-lookup"><span data-stu-id="17f85-103">Azure AD Connect (version 1.1.524.0 and after) now facilitates the use of msDS-ConsistencyGuid as sourceAnchor attribute.</span></span> <span data-ttu-id="17f85-104">Ao usar esse recurso, o AD Connect configura automaticamente as regras de sincronização para:</span><span class="sxs-lookup"><span data-stu-id="17f85-104">When using this feature, Azure AD Connect automatically configures the synchronization rules to:</span></span>
  
- <span data-ttu-id="17f85-105">Use msDS-ConsistencyGuid como o atributo de origemAnchor para objetos do usuário.</span><span class="sxs-lookup"><span data-stu-id="17f85-105">Use msDS-ConsistencyGuid as the sourceAnchor attribute for User objects.</span></span> <span data-ttu-id="17f85-106">ObjectGUID é usado para outros tipos de objetos.</span><span class="sxs-lookup"><span data-stu-id="17f85-106">ObjectGUID is used for other object types.</span></span>
    
- <span data-ttu-id="17f85-107">Para qualquer objeto de usuário de anúncio no local cujo atributo msDS-ConsistencyGuid não é preenchido, o Azure AD Connect escreve seu valor objectguid de volta ao atributo msDS-ConsistencyGuid no Diretório Ativo no local.</span><span class="sxs-lookup"><span data-stu-id="17f85-107">For any given on-premises AD User object whose msDS-ConsistencyGuid attribute isn't populated, Azure AD Connect writes its objectGUID value back to the msDS-ConsistencyGuid attribute in on-premises Active Directory.</span></span> <span data-ttu-id="17f85-108">Depois que o atributo msDS-ConsistencyGuid é preenchido, o Azure AD Connect exporta o objeto para o AD do Azure.</span><span class="sxs-lookup"><span data-stu-id="17f85-108">After the msDS-ConsistencyGuid attribute is populated, Azure AD Connect then exports the object to Azure AD.</span></span>
    
 <span data-ttu-id="17f85-109">**Nota:** Uma vez que um objeto de DA no local é importado para o Azure AD Connect (ou seja, importado para o Espaço Conector de AD e projetado para o Metaverse), você não pode mais alterar seu valor de fonteAnchor.</span><span class="sxs-lookup"><span data-stu-id="17f85-109">**Note:** Once an on-premises AD object is imported into Azure AD Connect (that is, imported into the AD Connector Space and projected into the Metaverse), you cannot change its sourceAnchor value anymore.</span></span> <span data-ttu-id="17f85-110">Para especificar o valor de origemAnchor para um determinado objeto de DD no local, configure seu atributo msDS-ConsistencyGuid antes de ser importado para o Azure AD Connect.</span><span class="sxs-lookup"><span data-stu-id="17f85-110">To specify the sourceAnchor value for a given on-premises AD object, configure its msDS-ConsistencyGuid attribute before it is imported into Azure AD Connect.</span></span> 
  
<span data-ttu-id="17f85-111">Para mais informações sobre SourceAnchor e ConsistencyGuid, consulte o seguinte: [Azure AD Connect: Conceitos de design](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span><span class="sxs-lookup"><span data-stu-id="17f85-111">For more information on SourceAnchor and ConsistencyGuid, refer to the following: [Azure AD Connect: Design concepts](https://docs.microsoft.com/azure/active-directory/connect/active-directory-aadconnect-design-concepts)</span></span>
  

