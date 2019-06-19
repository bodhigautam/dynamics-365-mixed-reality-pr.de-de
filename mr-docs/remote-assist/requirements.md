---
author: jevertt
description: Technische Anforderungen für die Bereitstellung und Verwendung von Microsoft Dynamics 365 Remote Assist
ms.author: jevertt
ms.date: 4/01/2019
ms.service: crm-online
ms.topic: article
title: Anforderungen für Dynamics 365 Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: 191c3880a4d1a4c0a4d77ba393147dea8df508c7
ms.sourcegitcommit: 0cb918a4505c43abfb65ca9aab9e5b3cd71211a0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/22/2019
ms.locfileid: "1594121"
---
# <a name="requirements-for-setting-up-dynamics-365-remote-assist"></a>Anforderungen für die Einrichtung von Dynamics 365 Remote Assist

In der folgenden Tabelle sind technischer Anforderungen für die Bereitstellung und Verwendung von [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] in Ihrer Organisation aufgelistet.

## <a name="device-requirements"></a>Gerätanforderungen

| **Gerät**               | **Betriebssystemanforderungen**                                                                                                                                                  | **Details**                                                                                                                                                                                                                    |
|--------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [!include[pn-hololens](../includes/pn-hololens.md)]                 | Build 10.0.14393.0 oder höher. [!include[pn-hololens](../includes/pn-hololens.md)] Ab Build 10.0.14393.0 wird [!include[pn-remote-assist](../includes/pn-remote-assist.md)] unterstützt. Es wird empfohlen [!include[pn-hololens](../includes/pn-hololens.md)] auf neuere Versionen zu aktualisieren, falls verfügbar. | In [Updates von HoloLens verwalten](https://docs.microsoft.com/en-us/HoloLens/hololens-updates) finden Sie Anweisungen zur Verwendung von [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Update for Business, Mobile Device Management (MDM) und [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] Server Update Services (WSUS). |
| [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 PC (optional) | Beliebige [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 Build.| Ein PC mit [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 kann mithilfe von [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] mit [!include[pn-hololens](../includes/pn-hololens.md)] verwendet werden.|
|Mobiles Gerät (optional)|Beliebiges iOS- oder [!include[tn-android](../includes/tn-android.md)-Smartphone oder -Tablet, auf dem [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md) Mobile installiert ist.|Ein Smartphone oder Tablet, auf dem [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md) Mobile ausgeführt wird, kann mit [!include[pn-hololens](../includes/pn-hololens.md)] verwendet werden.|

## <a name="licensing-and-product-requirements"></a>Lizenzierungs- und Produktanforderungen

| **Erforderliches Produkt**|**Details**|**Weitere Informationen**|
|---------------|-------------------------------------------------------|----------------------------------------------------------|
|[!include[pn-remote-assist](../includes/pn-remote-assist.md)]|[!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Software<br></br>**Hinweis** [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] ist im [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Abonnement für Einzelpersonen, die eine [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Lizenz in [!include[pn-hololens](../includes/pn-hololens.md)] verwenden, enthalten. Für Einzelpersonen (Experten), die mit einem [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer von [!include[pn-hololens](../includes/pn-hololens.md)] kommunizieren, ist außerdem eine [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)]-Lizenz erforderlich. [!include[pn-teams](../includes/pn-teams.md)] steht diesen Benutzern eventuell [als kostenloser Download](https://teams.microsoft.com/downloads) zur Verfügung.| [Remote Assist kaufen und bereitstellen](../licensing/buy-and-deploy.md)|
|[!include[pn-azure](../includes/pn-azure.md)] Active Directory-Konto ([!include[pn-azure](../includes/pn-azure.md)])|Erforderlich für: <ul><li>Abonnements erwerben und Lizenzen zuweisen. Jeder lizenzierte Benutzer benötigt ein [!include[pn-azure](../includes/pn-azure.md)] AD-Konto. </li><li>Apps im [!include[cc-microsoft](../includes/cc-microsoft.md)] Store für Unternehmen verteilen. </li><li>Benutzer, wenn sie sich bei der App anmelden. </ul> | [Erste Schritte mit Azure AD](https://docs.microsoft.com/en-us/azure/active-directory/fundamentals/get-started-azure-ad) |
| [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] (optional). **Beachten Sie**, dass die [!include[pn-field-service](../includes/pn-field-service.md)]-Version 8.2 oder jünger erforderlich ist. |Wenn Sie [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)]-Buchungen in [!include[pn-remote-assist](../includes/pn-remote-assist.md)] anzeigen möchten, erfordert [!include[pn-remote-assist](../includes/pn-remote-assist.md)] eine [!include[pn-dyn-365](../includes/pn-dyn-365.md)]-Lizenz. Um in [!include[pn-remote-assist](../includes/pn-remote-assist.md)] [!include[pn-power-bi](../includes/pn-power-bi.md)]-Dashboards anzuzeigen, die mit [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)]-Buchungen verknüpft sind, benötigen Benutzer eine gültige [!include[pn-power-bi](../includes/pn-power-bi.md)]-Lizenz. | [Weitere Informationen zu Dynamics 365 for Field Service](https://dynamics.microsoft.com/en-us/field-service/overview/)|

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
[Microsoft Teams mit Remote Assist einrichten und verwenden](use-microsoft-teams-with-remote-assist.md)<br/>
[Anleitungsvideos](videos.md)<br/>
[Häufig gestellte Fragen](faq.md)<br/>
