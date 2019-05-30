---
author: ornellaalt
description: Gerätoptionen und technische Anforderungen für Dynamics 365 Layout
ms.author: ornella
ms.date: 5/15/2019
ms.service: crm-online
ms.topic: article
title: Gerätoptionen und technische Anforderungen für Dynamics 365 Layout
ms.reviewer: v-brycho
ms.openlocfilehash: ab8c20ca8991abfd5604c7c09597e19a96aa786b
ms.sourcegitcommit: 34891391e0a0ffcef6ec9c56cf1d315ac0363ffc
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/15/2019
ms.locfileid: "1576446"
---
# <a name="device-options-and-technical-requirements-for-dynamics-365-layout"></a>Gerätoptionen und technische Anforderungen für Dynamics 365 Layout

[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-layout](../includes/pn-dyn-365-layout.md)] funktioniert mit einem Microsoft-Gerät [!include[pn-hololens](../includes/pn-hololens.md)] oder mit einem [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] immersiven Mixed Reality-Headset mit Motion-Controllern.

## <a name="hololens-requirements"></a>Anforderungen für den HoloLens

| **Betriebssystemanforderungen**          | **Details**                                                                                                                           |
|------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| Build 10.0.17134.77 oder höher. | Informationen um Upgrade auf diesen Build finden Sie unter [HoloLens aktualisieren](https://support.microsoft.com/help/12643/hololens-update-hololens). |

> [!NOTE]
> Sie können den [!include[pn-hololens](../includes/pn-hololens.md)] Clicker mit [!include[pn-layout](../includes/pn-layout.md)] verwenden, aber die Funktionalität ist eingeschränkt. Sie können den Clicker verwenden, um Menüoptionen zu verwenden und einen Scan eines Raums durchzuführen, aber Sie können damit keine Objekte verändern.


## <a name="windows-mixed-reality-headset-requirements"></a>Windows Mixed Reality Headset-Anforderungen

| **Anforderungen**                          | **Details**                                                                                                                                                                                                                                                                                                                          |
|-------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC mit Build 17134.0 oder später | Die [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC muss das Headset unterstützen können. In den [Windows Mixed Reality PC-Hardwarerichtlinien](https://support.microsoft.com/en-us/help/4039260/windows-10-mixed-reality-pc-hardware-guidelines) finden Sie die jeweiligen Hardwareanforderungen. Wir empfehlen, die [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Mixed Reality Ultra-Hardwarerichtlinien zu befolgen. |
| Motion-Controller                        | Motion-Controller sind Hardwarezubehör, mit dem Benutzer in Mixed Reality Schritte durchführen können. Weitere Informationen finden Sie unter [Motion-Controller](https://docs.microsoft.com/en-us/windows/mixed-reality/motion-controllers).                                                                                                                     |

<a name="technical-requirements"></a>Technische Anforderungen
----------------------

| **Anforderungen**                   | **Details**                                                                                                                                                                                                                                                                                                                                                                                             | **Weitere Informationen**                                                                                                                                                |
|------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD)  | Erforderlich zum Anmelden bei [!include[pn-layout](../includes/pn-layout.md)] und für die App-Distribution über [Microsoft Store für Unternehmen](https://docs.microsoft.com/en-us/microsoft-store/sign-up-microsoft-store-for-business).                                                                                                                                                                                                               | [Erste Schritte mit Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/get-started-azure-ad)                                                     |
| Netzwerkkonnektivität               | Internetzugriff ist zum Herunterladen der App und zum Nutzen seiner sämtlichen Funktionen erforderlich. Keine Bandbreiteanforderungen vorhanden.                                                                                                                                                                                                                                                                                    |                                                                                                                                                               |
| Apps zum Freigeben    | Videoanrufe oder Bildschirmfreigaben erfordern eine separate App wie [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] auf [!include[pn-hololens](../includes/pn-hololens.md)] oder Skype oder Skype for Business auf immersiven Headsets. <br> <br>  Ein [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC, der den Spezifikationen [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] von Mixed Reality Ultra entspricht, ist auch für Videoanrufe oder Bildschirmfreigaben erforderlich, wenn [!include[pn-layout](../includes/pn-layout.md)] mit einem immersiven Headset verwendet wird.                                                                                                                                                                                                               | [Remote Assist](../remote-assist/user-guide.md) <br> <br>  [Windows Mixed Reality PC-Hardwarerichtlinien](https://support.microsoft.com/en-us/help/4039260/windows-10-mixed-reality-pc-hardware-guidelines)                     |               
| [!include[pn-dyn-365-import-tool](../includes/pn-dyn-365-import-tool.md)] | [!include[pn-import-tool](../includes/pn-import-tool.md)] wird auf [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PCs ausgeführt und muss die vorhandenen 3D-Modell von Ihrem PC auf [!include[pn-layout](../includes/pn-layout.md)] übertragen, damit sie auf dem [!include[pn-hololens](../includes/pn-hololens.md)] oder auf immersiven Headsets angezeigt und bearbeitet werden können. Das [!include[pn-import-tool](../includes/pn-import-tool.md)] muss auch die Maße von [!include[pn-visio](../includes/pn-visio.md)] auf das [!include[pn-hololens](../includes/pn-hololens.md)] oder auf immersive Headsets übertragen. | [Import Tool](https://docs.microsoft.com/en-us/dynamics365/mixed-reality/import-tool)    |

### <a name="see-also"></a>Siehe auch
[Testen Sie Dynamics 365 Layout kostenlos](try-layout-free.md)<br/>
[Dynamics 365 Layout kaufen und bereitstellen](buy-and-deploy-layout.md)<br>
[Benutzerhandbuch](user-guide.md)<br/>
[Anleitungsvideos](https://go.microsoft.com/fwlink/p/?linkid=2021489)<br/>
[Häufig gestellte Fragen](faq.md)<br/>
