---
title: Regra do DLP para SSN não funcionar
ms.author: cmcatee
author: cmcatee-MSFT
manager: mnirkhe
ms.date: 11/5/2018
ms.audience: ITPro
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Priority
ms.assetid: ac265ee6-c946-476e-9bf0-0ea0e8adc98a
ms.openlocfilehash: b92d122b774d97cd2e44cc0880dc5001065b57cc
ms.sourcegitcommit: e2864efcfb493b6e46b662b746661a61232bdba7
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 01/24/2019
ms.locfileid: "29484626"
---
<span data-ttu-id="4d271-p101">Está a ter problemas com o **Data Loss Prevention (DLP)** não funcionar para o conteúdo que contém um **Número da Segurança Social (SSN)** quando utilizar um tipo de informações sensíveis no Office 365? Se assim for, certifique-se que o conteúdo contém as informações necessárias para que a política do DLP está à procura.</span><span class="sxs-lookup"><span data-stu-id="4d271-p101">Are you having problems with **Data Loss Prevention (DLP)** not working for content containing a **Social Security Number (SSN)** when using a sensitive information type in Office 365? If so, make sure your content contains the needed information for what the DLP policy is looking.</span></span> 
  
<span data-ttu-id="4d271-104">Por exemplo, para uma política de SSN configurada com um nível de confiança de 85%, a seguir é avaliados e deve ser detectada para a regra accionar:</span><span class="sxs-lookup"><span data-stu-id="4d271-104">For example, for an SSN policy configured with a confidence level of 85%, the following are evaluated and must be detected for the rule to trigger:</span></span>
  
- <span data-ttu-id="4d271-105">**[Formato:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 dígitos, que poderão ser um padrão formatado ou não formatado</span><span class="sxs-lookup"><span data-stu-id="4d271-105">**[Format:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#format-80)** 9 digits, which may be in a formatted or unformatted pattern</span></span> 
    
- <span data-ttu-id="4d271-106">**[Padrão:](https://msconnect.microsoft.com/https:/docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Quatro funções procure SSNs na quatro padrões diferentes:</span><span class="sxs-lookup"><span data-stu-id="4d271-106">**[Pattern:](https://msconnect.microsoft.com/https:/docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80)** Four functions look for SSNs in four different patterns:</span></span> 
    
  - <span data-ttu-id="4d271-107">Func_ssn localiza SSNs com pré-2011 forte formatação que são formatados com travessões ou espaços (ddd-dd-dddd ou ddd dd dddd)</span><span class="sxs-lookup"><span data-stu-id="4d271-107">Func_ssn finds SSNs with pre-2011 strong formatting that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>
    
  - <span data-ttu-id="4d271-108">Func_unformatted_ssn localiza SSNs com pré-2011 forte formatação que está formatada como nove dígitos consecutivos (ddddddddd)</span><span class="sxs-lookup"><span data-stu-id="4d271-108">Func_unformatted_ssn finds SSNs with pre-2011 strong formatting that are unformatted as nine consecutive digits (ddddddddd)</span></span>
    
  - <span data-ttu-id="4d271-109">Func_randomized_formatted_ssn localiza SSNs post 2011 formatados com travessões ou espaços (ddd-dd-dddd ou ddd dd dddd)</span><span class="sxs-lookup"><span data-stu-id="4d271-109">Func_randomized_formatted_ssn finds post-2011 SSNs that are formatted with dashes or spaces (ddd-dd-dddd OR ddd dd dddd)</span></span>
    
  - <span data-ttu-id="4d271-110">Func_randomized_unformatted_ssn localiza post 2011 SSNs que estão formatados como nove dígitos consecutivos (ddddddddd)</span><span class="sxs-lookup"><span data-stu-id="4d271-110">Func_randomized_unformatted_ssn finds post-2011 SSNs that are unformatted as nine consecutive digits (ddddddddd)</span></span>
    
- <span data-ttu-id="4d271-111">**[Soma de verificação:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** Não, não existe nenhum soma de verificação</span><span class="sxs-lookup"><span data-stu-id="4d271-111">**[Checksum:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#checksum-79)** No, there is no Checksum</span></span> 
    
- <span data-ttu-id="4d271-112">**[Definição:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** Uma política DLP é de 85% de certeza de que detectou este tipo de informações sensíveis se, num raio de 300 caracteres:</span><span class="sxs-lookup"><span data-stu-id="4d271-112">**[Definition:](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#definition-80)** A DLP policy is 85% confident that it's detected this type of sensitive information if, within a proximity of 300 characters:</span></span> 
    
  - <span data-ttu-id="4d271-113">A [função Func_ssn](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) localiza conteúdo que corresponda ao padrão.</span><span class="sxs-lookup"><span data-stu-id="4d271-113">The [function Func_ssn](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#pattern-80) finds content that matches the pattern.</span></span> 
    
  - <span data-ttu-id="4d271-p102">Foi encontrada uma palavra-chave de [Keyword_ssn](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) . Inclui exemplos de palavras-chave: *Segurança Social, de Segurança Social #, seg. Soc, SSN* . Por exemplo, o seguinte exemplo daria origem para a política do DLP SSN: **SSN: 489-36-8350**</span><span class="sxs-lookup"><span data-stu-id="4d271-p102">A keyword from [Keyword_ssn](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#keyword_ssn) is found. Examples of keywords includes:  *Social Security, Social Security#, Soc Sec ,SSN*  . For example, the following sample would trigger for the DLP SSN policy: **SSN: 489-36-8350**</span></span>
    
<span data-ttu-id="4d271-117">Para mais informações sobre o que é necessário para SSNs ser detectado para o seu conteúdo, consulte a secção seguinte deste artigo: [O que o sensíveis a maiúsculas e tipos de informação procure SSNs](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span><span class="sxs-lookup"><span data-stu-id="4d271-117">For more information on what is required for SSNs to be detected for your content, see the following section in this article: [What the Sensitive Information Types look for SSNs](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for#us-social-security-number-ssn)</span></span>
  
<span data-ttu-id="4d271-118">Utilizando um tipo de informações sensíveis incorporados diferentes, consulte o artigo seguinte para obter informações sobre o que é necessário para outros tipos: [Procurar o que o sensíveis a maiúsculas e tipos de informação](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span><span class="sxs-lookup"><span data-stu-id="4d271-118">Using a different built-in sensitive information type, see the following article for information on what is required for other types: [What the Sensitive Information Types look for](https://docs.microsoft.com/en-us/office365/securitycompliance/what-the-sensitive-information-types-look-for)</span></span>
  
