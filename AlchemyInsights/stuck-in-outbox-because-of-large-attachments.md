---
title: Preso na caixa de saída por causa de grandes anexos
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.audience: Admin
ms.topic: article
ROBOTS: NOINDEX, NOFOLLOW
localization_priority: Normal
ms.collection: Adm_O365
ms.custom:
- "2713"
- "9000768"
ms.openlocfilehash: d5fb20fcc146be67c5a04de0640ed4efd625311a
ms.sourcegitcommit: 8004ee243b5c68ff9532224a2e6c69dda0abbd0b
ms.translationtype: MT
ms.contentlocale: pt-PT
ms.lasthandoff: 10/10/2019
ms.locfileid: "37441316"
---
# <a name="fix-messages-that-are-stuck-in-the-outbox"></a><span data-ttu-id="ebe04-102">Corrigir mensagens que estão presas na caixa de saída</span><span class="sxs-lookup"><span data-stu-id="ebe04-102">Fix messages that are stuck in the Outbox</span></span>

<span data-ttu-id="ebe04-103">Recomendamos que você comece executando o cenário "Estou [tendo problemas para enviar, receber ou localizar mensagens de email"](https://aka.ms/SaRA-OutlookSendReceive) da ferramenta assistente de [recuperação e suporte da Microsoft](https://diagnostics.office.com/#/) .</span><span class="sxs-lookup"><span data-stu-id="ebe04-103">We recommend that you start by running the scenario ["I’m having problems sending, receiving, or finding email messages"](https://aka.ms/SaRA-OutlookSendReceive) from the [Microsoft Support and Recovery Assistant](https://diagnostics.office.com/#/) tool.</span></span>

<span data-ttu-id="ebe04-104">Quando uma mensagem fica presa na sua caixa de saída, as causas mais prováveis são:</span><span class="sxs-lookup"><span data-stu-id="ebe04-104">When a message gets stuck in your Outbox, the most likely causes are:</span></span>
- <span data-ttu-id="ebe04-105">Grandes anexos.</span><span class="sxs-lookup"><span data-stu-id="ebe04-105">Large attachments.</span></span>
- <span data-ttu-id="ebe04-106">A opção **enviar imediatamente quando conectada** não está habilitada.</span><span class="sxs-lookup"><span data-stu-id="ebe04-106">The **Send immediately when connected** option is not enabled.</span></span>

<span data-ttu-id="ebe04-107">Para remover anexos grandes:</span><span class="sxs-lookup"><span data-stu-id="ebe04-107">To remove large attachments:</span></span> 

1. <span data-ttu-id="ebe04-108">No Outlook, selecione **Enviar/receber** > **trabalho offline**.</span><span class="sxs-lookup"><span data-stu-id="ebe04-108">In Outlook, select **Send / Receive** > **Work Offline**.</span></span> 
2. <span data-ttu-id="ebe04-109">No painel de navegação, selecione **caixa de saída**.</span><span class="sxs-lookup"><span data-stu-id="ebe04-109">In the navigation pane, select **Outbox**.</span></span> <span data-ttu-id="ebe04-110">A partir daqui, você pode:</span><span class="sxs-lookup"><span data-stu-id="ebe04-110">From here, you can:</span></span> 
    - <span data-ttu-id="ebe04-111">Exclua a mensagem (selecione-a e, em seguida, selecione **excluir**).</span><span class="sxs-lookup"><span data-stu-id="ebe04-111">Delete the message (select it and then select **Delete**).</span></span>
    - <span data-ttu-id="ebe04-112">Arraste a mensagem para a pasta Rascunhos, clique duas vezes para abri-la e remover o anexo selecioná-lo e, em seguida, selecione **excluir**).</span><span class="sxs-lookup"><span data-stu-id="ebe04-112">Drag the message to your Drafts folder, double-click to open it, and remove the attachment select it and then select **Delete**).</span></span>
3. <span data-ttu-id="ebe04-113">Se você receber um erro que diz que o Outlook está tentando transmitir a mensagem, feche o Outlook.</span><span class="sxs-lookup"><span data-stu-id="ebe04-113">If you receive an error that says Outlook is trying to transmit the message, close Outlook.</span></span> <span data-ttu-id="ebe04-114">Pode demorar alguns instantes para sair.</span><span class="sxs-lookup"><span data-stu-id="ebe04-114">It may take a few moments to exit.</span></span> <span data-ttu-id="ebe04-115">Se o Outlook não fechar, pressione Ctrl + Alt + Delete e selecione **iniciar Gerenciador de tarefas**.</span><span class="sxs-lookup"><span data-stu-id="ebe04-115">If Outlook doesn’t close, press Ctrl+Alt+Delete and select **Start Task Manager**.</span></span> <span data-ttu-id="ebe04-116">No Gerenciador de tarefas, selecione a guia **processos** , role para baixo até Outlook. exe e selecione **finalizar processo**.</span><span class="sxs-lookup"><span data-stu-id="ebe04-116">In Task Manager, select the **Processes** tab, scroll down to outlook.exe, and select **End Process**.</span></span>
4. <span data-ttu-id="ebe04-117">Depois que o Outlook fecha, reinicie-o e repita as etapas 2 e 3.</span><span class="sxs-lookup"><span data-stu-id="ebe04-117">After Outlook closes, restart it and repeat steps 2 and 3.</span></span> 
5. <span data-ttu-id="ebe04-118">Depois de remover o anexo, clique em **Enviar/receber** > **trabalho offline** para retomar o trabalho online.</span><span class="sxs-lookup"><span data-stu-id="ebe04-118">After you remove the attachment, click **Send / Receive** > **Work Offline** to resume working online.</span></span> 

<span data-ttu-id="ebe04-119">As mensagens também ficam presas na caixa de saída quando você clica em **Enviar**, mas você não está conectado.</span><span class="sxs-lookup"><span data-stu-id="ebe04-119">Messages also get stuck in the Outbox when you click **Send**, but you are not connected.</span></span> <span data-ttu-id="ebe04-120">Clique em **Enviar/receber** e veja o botão **trabalhar offline** .</span><span class="sxs-lookup"><span data-stu-id="ebe04-120">Click **Send / Receive** and look at the **Work Offline** button.</span></span> <span data-ttu-id="ebe04-121">Se for azul, você está desconectado.</span><span class="sxs-lookup"><span data-stu-id="ebe04-121">If it's blue, you're disconnected.</span></span> <span data-ttu-id="ebe04-122">Selecione-o para se conectar (o botão fica branco) e clique em **enviar tudo**.</span><span class="sxs-lookup"><span data-stu-id="ebe04-122">Select it to connect (the button turns white) and click **Send All**.</span></span>
 
<span data-ttu-id="ebe04-123">Para habilitar o **envio imediatamente quando conectado**:</span><span class="sxs-lookup"><span data-stu-id="ebe04-123">To enable **Send immediately when connected**:</span></span>
 
- <span data-ttu-id="ebe04-124">Selecione \*\*\*\* > \*\*\*\* opções >  de arquivo**avançadas**.</span><span class="sxs-lookup"><span data-stu-id="ebe04-124">Select **File** > **Options** >  **Advanced**.</span></span>
<span data-ttu-id="ebe04-125">Na seção **Enviar e receber** , selecione **enviar imediatamente quando conectado**e, em seguida, escolha **OK**.</span><span class="sxs-lookup"><span data-stu-id="ebe04-125">In the **Send and receive** section, select **Send immediately when connected**, and then choose **OK**.</span></span>
 
<span data-ttu-id="ebe04-126">Para obter detalhes completos, consulte:</span><span class="sxs-lookup"><span data-stu-id="ebe04-126">For full details see:</span></span>
- [<span data-ttu-id="ebe04-127">Vídeo: enviar ou excluir um e-mail preso</span><span class="sxs-lookup"><span data-stu-id="ebe04-127">Video: Send or delete a stuck email</span></span>](https://support.office.com/article/Video-Send-or-delete-an-email-stuck-in-your-outbox-26d5d34a-4e5f-444a-a9e8-44db04a94dec) 
- [<span data-ttu-id="ebe04-128">O email permanece na pasta caixa de saída até que você inicie manualmente uma operação de envio/recebimento no Outlook</span><span class="sxs-lookup"><span data-stu-id="ebe04-128">Email stays in the Outbox folder until you manually initiate a send/receive operation in Outlook</span></span>](https://support.microsoft.com/help/2797572/email-stays-in-the-outbox-folder-until-you-manually-initiate-a-send-re)
