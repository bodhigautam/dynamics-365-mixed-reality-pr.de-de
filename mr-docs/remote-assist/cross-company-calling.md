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
# <a name="set-up-cross-company-calling-for-dynamics-365-remote-assist-for-admins"></a><span data-ttu-id="1c6aa-103">Unternehmensübergreifende Anrufe für Dynamics 365 Remote Assist (für Administratoren) einrichten</span><span class="sxs-lookup"><span data-stu-id="1c6aa-103">Set up cross-company calling for Dynamics 365 Remote Assist (for admins)</span></span>

<span data-ttu-id="1c6aa-104">Benutzer in Ihrer Organisation können persönliche Anrufe mit einem [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)]-Benutzer von einem anderen Unternehmen (Domäne) aus getätigt werden, wenn externer Zugriff in [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] für jede Domäne aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="1c6aa-104">Users in your organization can make or receive a one-on-one call with a [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] user from another company (domain) if external access is enabled in [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] for each domain.</span></span> 

> [!NOTE]
> <span data-ttu-id="1c6aa-105">Zu diesem Zeitpunkt sind Gruppenanrufe und Dateifreigabe für unternehmensübergreifende Anrufe nicht verfügbar.</span><span class="sxs-lookup"><span data-stu-id="1c6aa-105">At this time, group calling and file sharing is not available for cross-company calling.</span></span>

1.  <span data-ttu-id="1c6aa-106">[Aktivieren Sie externen Zugriff](https://docs.microsoft.com/microsoftteams/manage-external-access) in Ihrem [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] Admin Center.</span><span class="sxs-lookup"><span data-stu-id="1c6aa-106">[Enable external access](https://docs.microsoft.com/microsoftteams/manage-external-access) in your [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] admin center.</span></span> <span data-ttu-id="1c6aa-107">Damit können Benutzer in Ihrer Organisation mit Benutzern außerhalb Ihrer Domäne kommunizieren.</span><span class="sxs-lookup"><span data-stu-id="1c6aa-107">This allows users in your organization to make calls and chat with users outside your domain.</span></span>

    <span data-ttu-id="1c6aa-108">![Externen Zugriff ermöglichen](media/enable-external-access.PNG "Externen Zugriff ermöglichen")</span><span class="sxs-lookup"><span data-stu-id="1c6aa-108">![Enable external access](media/enable-external-access.PNG "Enable external access")</span></span>
 
    <span data-ttu-id="1c6aa-109">Standardmäßig können Benutzer mit Benutzern in beliebigen anderen Domänen kommunizieren, für die externer Zugriff aktiviert ist und die externen Zugriff auf Ihre Domäne haben.</span><span class="sxs-lookup"><span data-stu-id="1c6aa-109">By default, users can communicate with users in any other domain that has external access turned on and that has allowed external access with your domain.</span></span> <span data-ttu-id="1c6aa-110">Falls Sie dieses Verhalten begrenzen möchten, können Sie die zulässige oder gesperrten Domänen hinzufügen.</span><span class="sxs-lookup"><span data-stu-id="1c6aa-110">If you want to restrict this behavior, you can add allowed or blocked domains.</span></span> <span data-ttu-id="1c6aa-111">Weitere Informationen finden Sie unter [Externen Zugriff (Verbund) in Microsoft Teams verwalten](https://docs.microsoft.com/microsoftteams/manage-external-access).</span><span class="sxs-lookup"><span data-stu-id="1c6aa-111">For more information, see [Manage external access (federation) in Microsoft Teams](https://docs.microsoft.com/microsoftteams/manage-external-access).</span></span>

2.  <span data-ttu-id="1c6aa-112">Sie können prüfen, ob für einen Kontakt in einer anderen Domäne externer Zugriff im [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)]-Admin Center ihres Unternehmens aktiviert ist. Dazu geben Sie in Teams Desktop die vollständige E-Mail-Adresse des Kontakts ein.</span><span class="sxs-lookup"><span data-stu-id="1c6aa-112">To check to see if a contact in another domain has external access enabled in their company’s [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] admin center, try typing the contact's full email address in Teams Desktop.</span></span> <span data-ttu-id="1c6aa-113">Ist für beide Domänen ein externer Zugriff zugelassen ist, wird in [!include[pn-teams](../includes/pn-teams.md)] folgende Meldung angezeigt:</span><span class="sxs-lookup"><span data-stu-id="1c6aa-113">When external access is allowed between both domains, [!include[pn-teams](../includes/pn-teams.md)] shows the following message:</span></span>

    <span data-ttu-id="1c6aa-114">![Bestätigungsmeldung](media/access-enabled-confirmation.PNG "Bestätigungsmeldung")</span><span class="sxs-lookup"><span data-stu-id="1c6aa-114">![Confirmation message](media/access-enabled-confirmation.PNG "Confirmation message")</span></span>
 
### <a name="see-also"></a><span data-ttu-id="1c6aa-115">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="1c6aa-115">See also</span></span>

[<span data-ttu-id="1c6aa-116">Dynamics 365 Remote Assist-Benutzerhandbuch</span><span class="sxs-lookup"><span data-stu-id="1c6aa-116">Dynamics 365 Remote Assist user guide</span></span>](https://docs.microsoft.com/dynamics365/mixed-reality/remote-assist/user-guide#make-and-receive-calls)
