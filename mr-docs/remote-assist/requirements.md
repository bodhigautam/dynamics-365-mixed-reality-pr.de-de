---
author: MatthewJonPaul
description: Technische Anforderungen für die Bereitstellung und Verwendung von Microsoft Dynamics 365 Remote Assist
ms.author: mapau
ms.date: 4/01/2019
ms.service: crm-online
ms.topic: article
title: Anforderungen für Dynamics 365 Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: 7ae3b24bcc25f6b07147511ea22102162cdb5dcc
ms.sourcegitcommit: 157b70ec12e7cc459231aa5e32d311ebc09727d8
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2019
ms.locfileid: "1575543"
---
# <a name="requirements-for-setting-up-dynamics-365-remote-assist"></a>Anforderungen für die Einrichtung von Dynamics 365 Remote Assist

In der folgenden Tabelle sind technischer Anforderungen für die Bereitstellung und Verwendung von [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] in Ihrer Organisation aufgelistet.

## <a name="device-requirements"></a>Gerätanforderungen

| **Gerät**               | **Betriebssystemanforderungen**                                                                                                                                                  | **Details**                                                                                                                                                                                                                    |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [!include[pn-hololens](../includes/pn-hololens.md)]                 | Build 10.0.14393.0 oder höher. [!include[pn-hololens](../includes/pn-hololens.md)] Ab Build 10.0.14393.0 wird [!include[pn-remote-assist](../includes/pn-remote-assist.md)] unterstützt. Es wird empfohlen [!include[pn-hololens](../includes/pn-hololens.md)] auf neuere Versionen zu aktualisieren, falls verfügbar. | In [Updates von HoloLens verwalten](https://docs.microsoft.com/en-us/HoloLens/hololens-updates) finden Sie Anweisungen zur Verwendung von [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update for Business, Mobile Device Management (MDM) und [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Server Update Services (WSUS). |
| [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC (optional) | Beliebige [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 Build.| Ein [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC kann mit [!include[pn-hololens](../includes/pn-hololens.md)] mithilfe von [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] verwendet werden.|
|Mobiles Gerät (optional)|Beliebiges IOS- oder Android-Smartphone oder -Tablet mit Microsoft Teams Mobile-App.|Ein Smartphone oder Tablet, auf dem Microsoft Teams Mobile-App ausgeführt wird, kann mit HoloLens verwendet werden.|

## <a name="licensing-and-product-requirements"></a>Lizenzierungs- und Produktanforderungen

| **Produkt erforderlich**|**Details**|**Weitere Informationen**|
|---------------|-------------------------------------------------------|----------------------------------------------------------|
|Remote Assist|Remote Assist-Software<br></br>**Hinweis** Microsoft Teams ist im Remote Assist-Abonnement für Personen enthalten, die eine Remote Assist-Lizenz in HoloLens verwenden. Eine Microsoft Teams-Lizenz ist auch für Personen (Experten) erforderlich, die mit einem Benutzer von Remote Assist auf HoloLens kommunizieren. Teams kann für diese Benutzer als [kostenloser Download unter](https://teams.microsoft.com/downloads) zur Verfügung stehen.| [Remote Assist kaufen und bereitstellen](../licensing/buy-and-deploy.md)|
|Azure Active Directory (Azure AD) Konto|Erforderlich für: <ul><li>Abonnements erwerben und Lizenzen zuweisen. Für jeden lizenzierten Benutzer ist ein Azure AD-Konto erforderlich. </li><li>Apps über Microsoft Store für Unternehmen verteilen. </li><li>Benutzer, wenn sie sich bei der App anmelden. </ul> | [Erste Schritte mit Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/get-started-azure-ad) |
| Dynamics 365 for Field Service (optional). **Beachten Sie**, dass die Field Service Version 8.2 oder später erforderlich ist. |Remote Assist erfordert eine Dynamics 365-Lizenz, wenn Sie Buchungen von Dynamics 365 for Field Service in Remote Assist anzeigen möchten. Um Power BI-Dashboards anzuzeigen, die mit Dynamics 365 for Field Service-Buchungen in Remote Assist verknüpft sind, benötigen Benutzer eine gültige Power BI-Lizenz. | [Weitere Informationen zu Dynamics 365 for Field Service](https://dynamics.microsoft.com/en-us/field-service/overview/)|

## <a name="network-requirements"></a>Netzwerkanforderungen

Die empfohlene Bandbreite für optimale Leistung von [!include[pn-remote-assist](../includes/pn-remote-assist.md)] beträgt 1,5. MB/s.
Audio-/Videoanrufe können in Umgebungen mit verringerter Bandbreite möglich seine, Sie erleben möglicherweise Beeinträchtigungen der Funktion [!include[pn-hololens](../includes/pn-hololens.md)] was die Benutzerfreundlichkeit beeinträchtigt. Um die Netzwerkbandbreite Ihres Unternehmens zu testen, führen Sie die folgenden Schritte aus:

1.  Lassen Sie einen Benutzer von [!include[pn-teams](../includes/pn-teams.md)] einen Videoanruf mit einem anderen [!include[pn-teams](../includes/pn-teams.md)] Benutzer beginnen.

2.  Fügen Sie einen separaten Videoanruf zwischen einem dritten und vierten Benutzer und einen weiteren für einen fünften und sechsten Benutzer hinzu.

3.  Setzt das Hinzufügen von Videoanrufern zum Belastungstest Ihre Netzwerkbandbreite fort, bis Sie überzeugt sind, dass sich mehrere Benutzer gleichzeitig in Videoanrufen verbinden können.

Weitere Informationen finden Sie in [Das Netzwerk Ihrer Organisation für Microsoft Teams vorbereiten](https://docs.microsoft.com/en-us/MicrosoftTeams/prepare-network).

### <a name="see-also"></a>Siehe auch
[Überblick über Remote Assist](index.md)<br/>
[Remote Assist kostenlos testen](try-remote-assist-free.md)<br/>
[Remote Assist kaufen und bereitstellen](buy-and-deploy-remote-assist.md)<br>
[Benutzerhandbuch](user-guide.md)<br/>
[Microsoft Teams einrichten und mit Remote Assist verwenden](use-microsoft-teams-with-remote-assist.md)<br/>
[Anleitungsvideos](https://go.microsoft.com/fwlink/p/?linkid=2021485)<br/>
[Häufig gestellte Fragen](faq.md)<br/>
