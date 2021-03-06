---
title: Etiquetas de sensibilidade que não aparecem
ms.author: pebaum
author: pebaum
manager: laurawi
ms.date: 04/21/2020
ms.audience: admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.custom:
- "1778"
- "9000181"
ms.openlocfilehash: 6a64e001be115c8e5553a0d8c97b8cb815922c69
ms.sourcegitcommit: c6692ce0fa1358ec3529e59ca0ecdfdea4cdc759
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 09/15/2020
ms.locfileid: "47801195"
---
# <a name="sensitivity-labels-not-appearing"></a>Etiquetas de sensibilidade que não aparecem

As etiquetas de sensibilidade permitem classificar e ajudar a proteger o seu conteúdo sensível. Podem ser criados no centro de conformidade Microsoft 365, no centro de segurança Microsoft 365 ou no Microsoft 365 security & Compliance Center, sob classificação > de sensibilidade. Para saber mais sobre esta funcionalidade, consulte [a visão geral dos rótulos de sensibilidade.](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels)

Se configurar as suas etiquetas de sensibilidade, mas não estiverem presentes nas aplicações da Microsoft 365, verifique o seguinte:

- Confirme que a etiqueta de sensibilidade foi publicada para os [utilizadores](https://docs.microsoft.com/microsoft-365/compliance/sensitivity-labels#what-label-policies-can-do) e grupos que deseja.

- Confirme que o utilizador está a utilizar uma aplicação que suporta etiquetas de sensibilidade - veja [etiquetas de sensibilidade no seu documento](https://support.office.com/article/apply-sensitivity-labels-to-your-documents-and-email-within-office-2f96e7cd-d5a4-403b-8bd7-4cc636bae0f9?#bkmk_whereavailable).

- Se estiver [a migrar etiquetas de Proteção de Informação Azure,](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels)esteja atento às considerações [aqui](https://docs.microsoft.com/azure/information-protection/configure-policy-migrate-labels#considerations-for-unified-labels)enumeradas.

- Suporte à prevenção de perdas de dados (DLP): Atualmente, apenas os rótulos de retenção podem ser usados como condição nas políticas de DLP.  O suporte para rótulos de sensibilidade numa política de DLP ainda não está disponível, mas estamos a trabalhar nisso.

- Quando a encriptação é ativada num rótulo de sensibilidade, pode escolher qualquer um dos dois:
    - Atribuir permissões agora
    - Deixe que os utilizadores atribuam permissões


Para obter mais informações sobre possíveis questões, consulte [questões conhecidas com etiquetas de sensibilidade](https://support.office.com/article/known-issues-with-sensitivity-labels-in-office-b169d687-2bbd-4e21-a440-7da1b2743edc).