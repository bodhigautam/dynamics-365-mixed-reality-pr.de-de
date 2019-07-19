---
author: bencorn
description: Richten Sie unternehmensübergreifende Anrufe für Dynamics 365 Remote Assist ein, indem Sie externen Zugriff im Microsoft Teams-Administratorcenter aktivieren.
ms.author: becorn
ms.date: 05/06/2019
ms.service: crm-online
ms.topic: article
title: Unternehmensübergreifende Anrufe für Dynamics 365 Remote Assist einrichten
ms.reviewer: v-brycho
ms.openlocfilehash: d7c96ede319cbc891232761102316fc69c5f1df3
ms.sourcegitcommit: a9ae3e613938a7c53b2de2ce787fae6a3499c9ae
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/21/2019
ms.locfileid: "1593624"
---
# <a name="set-up-cross-company-calling-for-dynamics-365-remote-assist-for-admins"></a>Unternehmensübergreifende Anrufe für Dynamics 365 Remote Assist (für Administratoren) einrichten

Benutzer in Ihrer Organisation können persönliche Anrufe mit einem [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)]-Benutzer von einem anderen Unternehmen (Domäne) aus getätigt werden, wenn externer Zugriff in [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] für jede Domäne aktiviert ist. 

> [!NOTE]
> Zu diesem Zeitpunkt sind Gruppenanrufe und Dateifreigabe für unternehmensübergreifende Anrufe nicht verfügbar.

1.  [Aktivieren Sie externen Zugriff](https://docs.microsoft.com/microsoftteams/manage-external-access) in Ihrem [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] Admin Center. Damit können Benutzer in Ihrer Organisation mit Benutzern außerhalb Ihrer Domäne kommunizieren.

    ![Externen Zugriff ermöglichen](media/enable-external-access.PNG "Externen Zugriff ermöglichen")
 
    Standardmäßig können Benutzer mit Benutzern in beliebigen anderen Domänen kommunizieren, für die externer Zugriff aktiviert ist und die externen Zugriff auf Ihre Domäne haben. Falls Sie dieses Verhalten begrenzen möchten, können Sie die zulässige oder gesperrten Domänen hinzufügen. Weitere Informationen finden Sie unter [Externen Zugriff (Verbund) in Microsoft Teams verwalten](https://docs.microsoft.com/microsoftteams/manage-external-access).

2.  Sie können prüfen, ob für einen Kontakt in einer anderen Domäne externer Zugriff im [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)]-Admin Center ihres Unternehmens aktiviert ist. Dazu geben Sie in Teams Desktop die vollständige E-Mail-Adresse des Kontakts ein. Ist für beide Domänen ein externer Zugriff zugelassen ist, wird in [!include[pn-teams](../includes/pn-teams.md)] folgende Meldung angezeigt:

    ![Bestätigungsmeldung](media/access-enabled-confirmation.PNG "Bestätigungsmeldung")
 
### <a name="see-also"></a>Siehe auch

[Dynamics 365 Remote Assist-Benutzerhandbuch](https://docs.microsoft.com/dynamics365/mixed-reality/remote-assist/user-guide#make-and-receive-calls)
