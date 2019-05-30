---
author: MatthewJonPaul
description: Dynamics 365 Remote Assist aus einer anderen App starten (Protokollaktivierung)
ms.author: mapau
ms.date: 09/21/2018
ms.service: crm-online
ms.topic: article
title: Dynamics 365 Remote Assist aus einer anderen App starten
ms.reviewer: v-brycho
ms.openlocfilehash: d6ce46c4a5fb6af084bd34fbf30d397e777c6689
ms.sourcegitcommit: 34891391e0a0ffcef6ec9c56cf1d315ac0363ffc
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/15/2019
ms.locfileid: "1576421"
---
# <a name="launch-dynamics-365-remote-assist-from-another-app-protocol-activation"></a>Dynamics 365 Remote Assist aus einer anderen App starten (Protokollaktivierung)

Sie können Code in Ihre Anwendung [!include[pn-hololens](../includes/pn-hololens.md)] integrieren, um zu [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] zu wechseln und einen Anruf mit einem Uniform Resource Identifier (URI) zu starten.
Angenommen, Sie erstellen eine App zur Wartung eines Helikopters. Sie können eine Schaltfläche hinzufügen, über die ein Wartungstechniker einen Experten anrufen kann, wenn er nicht weiterkommt. Über die Schaltfläche wird [!include[pn-remote-assist](../includes/pn-remote-assist.md)] gestartet und der gewünschte Experte angerufen.

[!include[pn-remote-assist](../includes/pn-remote-assist.md)] unterstützt zwei Methoden für Protokollaktivierung: 

-   "ms-voip-video" ist für videoaktivierte Anrufe.

-   "ms-voip-call" ist für Nur-Audio-Anrufe.

Beide Methoden verwenden das gleiche Argumentschema, das ein contactID-Feld akzeptiert.
Der URI sieht in etwas folgendermaßen aus:

`
ms-voip-video:?contactids=\<contactID\>
`

Die Kontakt-ID ist die Objekt-ID [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD) des Benutzers.

## <a name="code-sample"></a>Beispielcode

Sie müssen den Code in Ihre App [!include[pn-hololens](../includes/pn-hololens.md)] integrieren. Das folgende Codebeispiel wird in C++ geschrieben, kann jedoch einfach in eine andere Sprache konvertiert werden.

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

Mithilfe des URIs “ms-voip-call:?contactids=” können Sie eine Nur-Audio- anstelle einer Videokonferenz durchführen

## <a name="place-a-call-to-test-your-code"></a>Tätigen Sie einen Anruf, um Ihren Code zu testen

1.  Führen Sie Ihre App auf dem [!include[pn-hololens](../includes/pn-hololens.md)] aus.

2.  Beginnen Sie den Anruf mit Ihrer App.

3.  [!include[pn-hololens](../includes/pn-hololens.md)] wird zum Schließen der App angezeigt. Öffnen Sie [!include[pn-remote-assist](../includes/pn-remote-assist.md)], wenn sie nicht bereits geöffnet ist, und melden Sie sich an.

4.  Wenn der Kontaktbereich geladen ist, platziert [!include[pn-remote-assist](../includes/pn-remote-assist.md)] einen Anruf bei dem angegebenen Kontakt.

### <a name="see-also"></a>Siehe auch

Genauere Informationen zum Starten einer App mit einem URI finden Sie in [App mit einem URI starten](<https://docs.microsoft.com/en-us/windows/uwp/launch-resume/launch-app-with-uri>).
