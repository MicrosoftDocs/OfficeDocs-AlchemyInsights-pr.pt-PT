---
title: Utilize linhas de segurança Microsoft Intune para configurar dispositivos Windows 10
ms.author: v-aiyengar
author: AshaIyengar21
manager: dansimp
ms.date: 12/03/2020
ms.audience: Admin
ms.topic: article
ms.service: o365-administration
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "9004135"
- "7211"
ms.openlocfilehash: 24257f1ac5752df1598d08fcfdb95ee2642adfea
ms.sourcegitcommit: c069f1b53567ad14711c423740f120439a312a60
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 12/04/2020
ms.locfileid: "49573534"
---
# <a name="use-microsoft-intune-security-baselines-to-configure-windows-10-devices"></a><span data-ttu-id="6e951-102">Utilize linhas de segurança Microsoft Intune para configurar dispositivos Windows 10</span><span class="sxs-lookup"><span data-stu-id="6e951-102">Use Microsoft Intune security baselines to configure Windows 10 devices</span></span>

<span data-ttu-id="6e951-103">As linhas de segurança intune ajudam a proteger os utilizadores e dispositivos.</span><span class="sxs-lookup"><span data-stu-id="6e951-103">Intune security baselines help protect users and devices.</span></span> <span data-ttu-id="6e951-104">As linhas de base de segurança são os grupos pré-configurados das definições do Windows utilizados para aplicar um grupo conhecido de definições e valores predefinidos recomendados pelas equipas de segurança relevantes.</span><span class="sxs-lookup"><span data-stu-id="6e951-104">Security baselines are Windows settings' pre-configured groups used to apply a known group of settings and default values recommended by the relevant security teams.</span></span> <span data-ttu-id="6e951-105">Ao criar um perfil de base de segurança no Intune, cria-se um modelo que consiste em múltiplos perfis de configuração do dispositivo.</span><span class="sxs-lookup"><span data-stu-id="6e951-105">By creating a security baseline profile in Intune, you create a template that consists of multiple device-configuration profiles.</span></span>

<span data-ttu-id="6e951-106">Quando implementa linhas de segurança para grupos de utilizadores ou dispositivos, as definições são aplicadas em dispositivos que funcionam no Windows 10 ou posteriormente.</span><span class="sxs-lookup"><span data-stu-id="6e951-106">When you deploy security baselines to groups of users or devices, the settings are applied to devices that run on Windows 10 or later.</span></span> <span data-ttu-id="6e951-107">Por exemplo, o MD Security Baseline automaticamente (1) permite que o BitLocker para unidades amovíveis, (2) requer a palavra-passe para desbloquear um dispositivo, e (3) desativa a autenticação básica.</span><span class="sxs-lookup"><span data-stu-id="6e951-107">For example, MDM Security Baseline automatically (1) enables BitLocker for removable drives, (2) requires the password for unlocking a device, and (3) disables basic authentication.</span></span> <span data-ttu-id="6e951-108">Quando um valor predefinido não funcionar para o seu ambiente, personalize a linha de base para aplicar as definições de que necessita.</span><span class="sxs-lookup"><span data-stu-id="6e951-108">When a default value doesn't work for your environment, customize the baseline to apply the settings you need.</span></span>

<span data-ttu-id="6e951-109">As linhas de base de segurança também ajudam a estabelecer um fluxo de trabalho seguro de ponta a ponta na Microsoft 365.</span><span class="sxs-lookup"><span data-stu-id="6e951-109">Security baselines also help establish an end-to-end secure workflow in Microsoft 365.</span></span> <span data-ttu-id="6e951-110">Seguem-se alguns benefícios:</span><span class="sxs-lookup"><span data-stu-id="6e951-110">The following are some benefits of this:</span></span>

- <span data-ttu-id="6e951-111">Uma linha de base de segurança inclui as melhores práticas e recomendações para configurações que afetam a segurança.</span><span class="sxs-lookup"><span data-stu-id="6e951-111">A security baseline includes the best practices and recommendations for settings that affect security.</span></span> <span data-ttu-id="6e951-112">Uma vez que a Intune é parceira da equipa de segurança do Windows que cria linhas de base para políticas de grupo, estas recomendações baseiam-se numa orientação sólida e numa vasta experiência.</span><span class="sxs-lookup"><span data-stu-id="6e951-112">Because Intune partners with the Windows security team that creates baselines for group policies, these recommendations are based on solid guidance and extensive experience.</span></span>
- <span data-ttu-id="6e951-113">Se é novo no Intune e não sabe por onde começar, então as linhas de segurança irão ajudá-lo a criar rapidamente e a implementar um perfil seguro.</span><span class="sxs-lookup"><span data-stu-id="6e951-113">If you're new to Intune and unsure of where to start, then security baselines will help you quickly create and deploy a secure profile.</span></span>
- <span data-ttu-id="6e951-114">Se você usa atualmente uma política de grupo, então migrar para Intune para fins de gestão é muito mais fácil com linhas de base de segurança, porque eles são incorporados no Intune e incluem capacidades de ponta para gestão.</span><span class="sxs-lookup"><span data-stu-id="6e951-114">If you currently use a group policy, then migrating to Intune for management purposes is much easier with security baselines, because they are built into Intune and include cutting-edge capabilities for management.</span></span>

<span data-ttu-id="6e951-115">Para saber mais, consulte [as linhas de base de segurança do Windows](https://go.microsoft.com/fwlink/?linkid=2141503) e a [gestão de dispositivos móveis.](https://go.microsoft.com/fwlink/?linkid=2141701)</span><span class="sxs-lookup"><span data-stu-id="6e951-115">To learn more, see [Windows security baselines](https://go.microsoft.com/fwlink/?linkid=2141503) and [Mobile device management](https://go.microsoft.com/fwlink/?linkid=2141701).</span></span>