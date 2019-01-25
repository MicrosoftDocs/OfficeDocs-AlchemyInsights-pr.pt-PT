---
title: Regra do DLP para e.u.a. / número do passaporte Reino Unido não funcionar
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: fc178b8b-943b-4346-a2bd-a75c6af6f80f
ms.openlocfilehash: 716d1030d93ce006c36d7925fb132e974ae8feb4
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 01/24/2019
ms.locfileid: "29484156"
---
<span data-ttu-id="3a663-p101">Está a ter problemas com o **Data Loss Prevention (DLP)** não funcionar para que contenha conteúdo uma **dos e.u.a. / número do passaporte UK** quando utilizar um tipo de informações sensíveis do DLP em O365? Nesse caso, certifique-se o conteúdo contém as informações necessárias para que a política do DLP está à procura quando é avaliado.</span><span class="sxs-lookup"><span data-stu-id="3a663-p101">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **US/UK Passport Number** when using a DLP sensitive information type in O365? If so, make sure your content contains the needed information for what the DLP policy is looking for when it is evaluated.</span></span> 
  
<span data-ttu-id="3a663-104">Por exemplo, para um **dos e.u.a. / número do passaporte UK** política configurada com um nível de confiança de 75%, os seguintes são avaliados e deve ser detectados para a regra accionar</span><span class="sxs-lookup"><span data-stu-id="3a663-104">For example, for a **US/UK Passport Number** policy configured with a confidence level of 75%, the following are evaluated and must be detected for the rule to trigger</span></span> 
  
- <span data-ttu-id="3a663-105">**[Formato:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nove algarismos</span><span class="sxs-lookup"><span data-stu-id="3a663-105">**[Format:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-77)** Nine digits</span></span> 
    
- <span data-ttu-id="3a663-106">**[Padrão:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nove algarismos consecutivos.</span><span class="sxs-lookup"><span data-stu-id="3a663-106">**[Pattern:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-77)** Nine consecutive digits</span></span> 
    
- <span data-ttu-id="3a663-107">**[Soma de verificação:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** Não, não existe nenhum soma de verificação</span><span class="sxs-lookup"><span data-stu-id="3a663-107">**[Checksum:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-76)** No, there is no Checksum</span></span> 
    
- <span data-ttu-id="3a663-108">**[Definição:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** Uma política do DLP corresponde a 75% de certeza de que detectou este tipo de informações sensíveis se, num raio de 300 caracteres:</span><span class="sxs-lookup"><span data-stu-id="3a663-108">**[Definition:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-77)** A DLP policy is 75% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="3a663-109">A função Func_usa_uk_passport localiza conteúdo que corresponda ao padrão.</span><span class="sxs-lookup"><span data-stu-id="3a663-109">The function Func_usa_uk_passport finds content that matches the pattern.</span></span>
    
  - <span data-ttu-id="3a663-110">Foi encontrada uma palavra-chave de Keyword_passport.</span><span class="sxs-lookup"><span data-stu-id="3a663-110">A keyword from Keyword_passport is found.</span></span>
    
    <span data-ttu-id="3a663-111">Por exemplo, o seguinte exemplo daria origem para o **dos e.u.a. / número do passaporte UK** política: número de Estados Unidos Passport 123456789</span><span class="sxs-lookup"><span data-stu-id="3a663-111">For example, the following sample would trigger for the **US/UK Passport Number** policy: U.S. Passport number 123456789</span></span> 
    
<span data-ttu-id="3a663-112">Para mais informações sobre o que é necessário para dos e.u.a. / número do passaporte UK para ser detectado para o seu conteúdo, consulte a secção seguinte deste artigo: [localizar o que o sensíveis a maiúsculas e tipos de informação dos e.u.a. / número do passaporte UK](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span><span class="sxs-lookup"><span data-stu-id="3a663-112">For more information on what is required for a US/UK Passport Number to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for US/UK Passport Number](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us--uk-passport-number)</span></span>
  
<span data-ttu-id="3a663-113">Utilizando um tipo de informações sensíveis incorporados diferentes, consulte o artigo seguinte para obter informações sobre o que é necessário para outros tipos: [Procurar o que o sensíveis a maiúsculas e tipos de informação](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="3a663-113">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  
