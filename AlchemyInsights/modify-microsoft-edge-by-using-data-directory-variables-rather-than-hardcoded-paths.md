---
title: Modifique o Microsoft Edge utilizando variáveis de diretório de dados em vez de caminhos codificados
ms.author: v-smandalika
author: v-smandalika
manager: dansimp
ms.date: 12/03/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: ''
ms.custom:
- "9003873"
- "6926"
ms.openlocfilehash: 5c40aa1d7f61fbd2842839a5839899af8ab439f2
ms.sourcegitcommit: 523098560e54a50184a99c974809dfbfffadacb5
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 12/09/2020
ms.locfileid: "49679148"
---
# <a name="modify-microsoft-edge-by-using-data-directory-variables-rather-than-hardcoded-paths"></a>Modifique o Microsoft Edge utilizando variáveis de diretório de dados em vez de caminhos codificados

Por exemplo, no Windows, para armazenar os dados de perfil sob os dados de aplicações locais de um utilizador e não na localização padrão, dedetuuse a política **userDataDir** para **${local_app_data}\Edge\Profile**. 

Para saber mais, consulte [as variáveis de diretório de dados do utilizador do Microsoft Edge](https://docs.microsoft.com/deployedge/edge-learnmore-create-user-directory-vars).