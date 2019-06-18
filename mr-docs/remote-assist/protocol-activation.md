---
author: jevertt
description: Dynamics 365 Remote Assist aus einer anderen App starten (Protokollaktivierung)
ms.author: jevertt
ms.date: 09/21/2018
ms.service: crm-online
ms.topic: article
title: Dynamics 365 Remote Assist aus einer anderen App starten
ms.reviewer: v-brycho
ms.openlocfilehash: 3c11f917f9d948dab2c8f06a70e8b363801c5167
ms.sourcegitcommit: 0cb918a4505c43abfb65ca9aab9e5b3cd71211a0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/22/2019
ms.locfileid: "1594116"
---
# <a name="launch-dynamics-365-remote-assist-from-another-app-protocol-activation"></a><span data-ttu-id="1f3bd-103">Dynamics 365 Remote Assist aus einer anderen App starten (Protokollaktivierung)</span><span class="sxs-lookup"><span data-stu-id="1f3bd-103">Launch Dynamics 365 Remote Assist from another app (protocol activation)</span></span>

<span data-ttu-id="1f3bd-104">Sie können Code in Ihre Anwendung [!include[pn-hololens](../includes/pn-hololens.md)] integrieren, um zu [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] zu wechseln und einen Anruf mit einem Uniform Resource Identifier (URI) zu starten.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-104">You can embed code in your [!include[pn-hololens](../includes/pn-hololens.md)] application to switch to [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] and begin a call using a Uniform Resource Identifier (URI).</span></span>
<span data-ttu-id="1f3bd-105">Angenommen, Sie erstellen eine App zur Wartung eines Helikopters.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-105">For example, let’s say you’re creating a helicopter maintenance app.</span></span> <span data-ttu-id="1f3bd-106">Sie können eine Schaltfläche hinzufügen, über die ein Wartungstechniker einen Experten anrufen kann, wenn er nicht weiterkommt.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-106">You can add a button that a maintenance engineer can use to call an expert if they get stuck.</span></span> <span data-ttu-id="1f3bd-107">Über die Schaltfläche wird [!include[pn-remote-assist](../includes/pn-remote-assist.md)] gestartet und der gewünschte Experte angerufen.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-107">The button will launch [!include[pn-remote-assist](../includes/pn-remote-assist.md)] and call the designated expert.</span></span>

[!include[pn-remote-assist](../includes/pn-remote-assist.md)] <span data-ttu-id="1f3bd-108">unterstützt zwei Methoden für Protokollaktivierung:</span><span class="sxs-lookup"><span data-stu-id="1f3bd-108">supports two methods for protocol activation:</span></span> 

-   <span data-ttu-id="1f3bd-109">"ms-voip-video" ist für videoaktivierte Anrufe.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-109">“ms-voip-video” is for video-enabled calling.</span></span>

-   <span data-ttu-id="1f3bd-110">"ms-voip-call" ist für Nur-Audio-Anrufe.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-110">“ms-voip-call” is for audio-only calling.</span></span>

<span data-ttu-id="1f3bd-111">Beide Methoden verwenden das gleiche Argumentschema, das ein contactID-Feld akzeptiert.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-111">Both methods use the same argument schema, which accepts a “contactID” field.</span></span>
<span data-ttu-id="1f3bd-112">Der URI sieht in etwas folgendermaßen aus:</span><span class="sxs-lookup"><span data-stu-id="1f3bd-112">The URI would look something like this:</span></span>

`
ms-voip-video:?contactids=\<contactID\>
`

<span data-ttu-id="1f3bd-113">Die Kontakt-ID ist die Objekt-ID [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD) des Benutzers.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-113">The contact ID is the user’s [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD) object ID.</span></span>

## <a name="code-sample"></a><span data-ttu-id="1f3bd-114">Beispielcode</span><span class="sxs-lookup"><span data-stu-id="1f3bd-114">Code sample</span></span>

<span data-ttu-id="1f3bd-115">Sie müssen den Code in Ihre App [!include[pn-hololens](../includes/pn-hololens.md)] integrieren.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-115">You’ll need to embed the code in your [!include[pn-hololens](../includes/pn-hololens.md)] app.</span></span> <span data-ttu-id="1f3bd-116">Das folgende Codebeispiel wird in C++ geschrieben, kann jedoch einfach in eine andere Sprache konvertiert werden.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-116">The following code sample is written in C++, but can be easily adapted to another language.</span></span>

```
Platform::String\^ id = objectId-\>Text;
auto uri = ref new Windows::Foundation::Uri("ms-voip-video:?contactids=" + id);
resultText-\>Text = uri-\>AbsoluteUri; 

concurrency::task\<bool\> launchUriOperation(Windows::System::Launcher::LaunchUriAsync(uri));
launchUriOperation.then([this](bool success)   
{         
    if (success)         
    {             
        // URI launched  
        resultText-\>Text += " (URI Launched)"; 
    } 
    else         
    {             
        // URI launch failed             
        resultText-\>Text += " (FAILED)";
    }     
});  
```

<span data-ttu-id="1f3bd-117">Mithilfe des URIs “ms-voip-call:?contactids=” können Sie eine Nur-Audio- anstelle einer Videokonferenz durchführen</span><span class="sxs-lookup"><span data-stu-id="1f3bd-117">To place an audio-only call instead of video, use URI: “ms-voip-call:?contactids=”</span></span>

## <a name="place-a-call-to-test-your-code"></a><span data-ttu-id="1f3bd-118">Tätigen Sie einen Anruf, um Ihren Code zu testen</span><span class="sxs-lookup"><span data-stu-id="1f3bd-118">Place a call to test your code</span></span>

1.  <span data-ttu-id="1f3bd-119">Führen Sie Ihre App auf dem [!include[pn-hololens](../includes/pn-hololens.md)] aus.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-119">Run your app on the [!include[pn-hololens](../includes/pn-hololens.md)].</span></span>

2.  <span data-ttu-id="1f3bd-120">Beginnen Sie den Anruf mit Ihrer App.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-120">Initiate the call from your app.</span></span>

3.  <span data-ttu-id="1f3bd-121">[!include[pn-hololens](../includes/pn-hololens.md)] wird zum Schließen der App angezeigt. Öffnen Sie [!include[pn-remote-assist](../includes/pn-remote-assist.md)], wenn sie nicht bereits geöffnet ist, und melden Sie sich an.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-121">The [!include[pn-hololens](../includes/pn-hololens.md)] will appear to close the app, open [!include[pn-remote-assist](../includes/pn-remote-assist.md)] if it isn’t already open, and sign in.</span></span>

4.  <span data-ttu-id="1f3bd-122">Wenn der Kontaktbereich geladen ist, platziert [!include[pn-remote-assist](../includes/pn-remote-assist.md)] einen Anruf bei dem angegebenen Kontakt.</span><span class="sxs-lookup"><span data-stu-id="1f3bd-122">After the contacts panel is loaded, [!include[pn-remote-assist](../includes/pn-remote-assist.md)] will place a call to the specified contact.</span></span>

### <a name="see-also"></a><span data-ttu-id="1f3bd-123">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="1f3bd-123">See also</span></span>

<span data-ttu-id="1f3bd-124">Genauere Informationen zum Starten einer App mit einem URI finden Sie in [App mit einem URI starten](<https://docs.microsoft.com/en-us/windows/uwp/launch-resume/launch-app-with-uri>).</span><span class="sxs-lookup"><span data-stu-id="1f3bd-124">For more details on launching an app with a URI, see [Launch an app with a URI](<https://docs.microsoft.com/en-us/windows/uwp/launch-resume/launch-app-with-uri>).</span></span>
