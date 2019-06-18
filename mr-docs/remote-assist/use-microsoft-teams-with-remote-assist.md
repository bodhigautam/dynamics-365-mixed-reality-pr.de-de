---
author: bencorn
description: Microsoft Teams mit Remote Assist zur telefonischen Zusammenarbeit einrichten und verwenden
ms.author: bencorn
ms.date: 06/04/2019
ms.service: crm-online
ms.topic: article
title: " Microsoft Teams mit Remote Assist einrichten und verwenden"
ms.reviewer: v-brycho
ms.openlocfilehash: 2964049fad93daffca716a447c9ece9420b21f95
ms.sourcegitcommit: 80c2a9dc71cab3914d3a96d37904bd1e16e4b450
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/03/2019
ms.locfileid: "1617254"
---
# <a name="set-up-and-use-microsoft-teams-with-remote-assist-to-collaborate-on-a-call"></a><span data-ttu-id="9a8c4-103">Microsoft Teams mit Remote Assist zur telefonischen Zusammenarbeit einrichten und verwenden</span><span class="sxs-lookup"><span data-stu-id="9a8c4-103">Set up and use Microsoft Teams with Remote Assist to collaborate on a call</span></span>

<span data-ttu-id="9a8c4-104">Ein [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)]-Benutzer auf [!include[pn-hololens](../includes/pn-hololens.md)] kann während eines Videoanrufs mit einem Kollegen (typischerweise ein Experte auf einem bestimmten Gebiet) zusammenarbeiten, indem er [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] verwendet.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-104">A [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] user on [!include[pn-hololens](../includes/pn-hololens.md)] can work collaboratively with a colleague (typically an expert in a particular field) during a video call by using [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)].</span></span> <span data-ttu-id="9a8c4-105">Der Experte kann alles sehen, was der Benutzer [!include[pn-remote-assist](../includes/pn-remote-assist.md)] sieht, und sie können holografisch zeichnen und zusammen kommentieren.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-105">The expert can see everything that the [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user sees, and they can holographically draw and annotate together.</span></span> <span data-ttu-id="9a8c4-106">Nehmen wir beispielsweise an, ein Außendienstmitarbeiter wartet eine sehr komplexe Maschine und ist sich nicht sicher, wie er ein Problem lösen kann.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-106">For example, let’s say a first-line worker is servicing a very complex machine and isn’t sure how to solve a problem.</span></span> <span data-ttu-id="9a8c4-107">Der Außendienstmitarbeiter kann überall auf der Welt einen Experten anrufen und sich von diesem bei der Wartung mit Anmerkungen oder Dateien unterstützen lassen.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-107">The first-line worker can call an expert anywhere in the world and have the expert assist with the servicing using annotations or files.</span></span>

<span data-ttu-id="9a8c4-108">Die Einrichtung dieser Zusammenarbeit mit [!include[pn-teams](../includes/pn-teams.md)] ist einfach und für die Zuhilfenahme des Experten entstehen keine Kosten.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-108">Setting up this collaboration using [!include[pn-teams](../includes/pn-teams.md)] is simple and it’s free for the expert.</span></span>

<span data-ttu-id="9a8c4-109">Benötigen Sie weitere Hilfe?</span><span class="sxs-lookup"><span data-stu-id="9a8c4-109">Need more help?</span></span> <span data-ttu-id="9a8c4-110">[Unter „Häufig gestellte Fragen zu Remote Assist“](faq.md) finden Sie Antworten auf typische Fragen.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-110">[Check out Remote Assist FAQ](faq.md) for answers to common questions.</span></span>

<span data-ttu-id="9a8c4-111">[Sehen Sie sich die Anleitungsvideos](videos.md) zu [!include[pn-remote-assist](../includes/pn-remote-assist.md)] an.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-111">[Watch how-to videos](videos.md) about [!include[pn-remote-assist](../includes/pn-remote-assist.md)].</span></span>

## <a name="what-youll-need"></a><span data-ttu-id="9a8c4-112">Was Sie benötigen</span><span class="sxs-lookup"><span data-stu-id="9a8c4-112">What you’ll need</span></span>


<span data-ttu-id="9a8c4-113">Der [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer (Außendienstmitarbeiter) mit [!include[pn-HoloLens](../includes/pn-HoloLens.md)] benötigt:</span><span class="sxs-lookup"><span data-stu-id="9a8c4-113">The [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user (first-line worker) on [!include[pn-HoloLens](../includes/pn-HoloLens.md)] needs:</span></span>

-   [<span data-ttu-id="9a8c4-114">Ein Abonnement von Remote Assist.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-114">A subscription to Remote Assist.</span></span>](../licensing/buy-and-deploy.md) <span data-ttu-id="9a8c4-115">Das [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Abonnement beinhaltet ein Abonnement von [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)].</span><span class="sxs-lookup"><span data-stu-id="9a8c4-115">The [!include[pn-remote-assist](../includes/pn-remote-assist.md)] subscription includes a subscription to [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)].</span></span>

-   <span data-ttu-id="9a8c4-116">Ein [!include[pn-hololens](../includes/pn-hololens.md)] mit dem [Update für Windows 10 vom April 2018](https://support.microsoft.com/en-us/help/12643) (oder höher).</span><span class="sxs-lookup"><span data-stu-id="9a8c4-116">A [!include[pn-hololens](../includes/pn-hololens.md)] running the [Windows 10 April 2018 Update](https://support.microsoft.com/en-us/help/12643) (or later).</span></span>

-   <span data-ttu-id="9a8c4-117">Ein [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)]-Konto.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-117">An [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] account.</span></span>

<span data-ttu-id="9a8c4-118">Der Experte benötigt:</span><span class="sxs-lookup"><span data-stu-id="9a8c4-118">The expert needs:</span></span>

-   <span data-ttu-id="9a8c4-119">Einen PC, auf dem [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 mit der neuesten Version von [Microsoft Teams](https://products.office.com/microsoft-teams/group-chat-software) läuft oder ein mobiles Gerät, auf dem [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] Mobile ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-119">A PC running [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 with the latest version of [Microsoft Teams](https://products.office.com/microsoft-teams/group-chat-software) or a mobile device running [!include[pn-microsoft-teams](../includes/pn-microsoft-teams.md)] Mobile.</span></span> <span data-ttu-id="9a8c4-120">Der Experte verwendet [!include[pn-teams](../includes/pn-teams.md)], um mit dem [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer von [!include[pn-HoloLens](../includes/pn-HoloLens.md)] zu kommunizieren.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-120">The expert uses [!include[pn-teams](../includes/pn-teams.md)] to communicate with the [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user on [!include[pn-HoloLens](../includes/pn-HoloLens.md)].</span></span> [!include[pn-teams](../includes/pn-teams.md)] <span data-ttu-id="9a8c4-121">kann eventuell [kostenlos heruntergeladen werden](https://teams.microsoft.com/downloads).</span><span class="sxs-lookup"><span data-stu-id="9a8c4-121">may be available [as a free download](https://teams.microsoft.com/downloads).</span></span>

-   <span data-ttu-id="9a8c4-122">Ein kostenloses [!include[cc-microsoft](../includes/cc-microsoft.md)]-Konto.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-122">A free [!include[cc-microsoft](../includes/cc-microsoft.md)] account.</span></span> <span data-ttu-id="9a8c4-123">Der Experte hat mitunter bereits ein [!include[cc-microsoft](../includes/cc-microsoft.md)]-Konto, wenn er sich im [!include[cc-microsoft](../includes/cc-microsoft.md)] App Store, bei Skype, Xbox, Hotmail oder Outlook.com registriert hat.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-123">The expert might already have a [!include[cc-microsoft](../includes/cc-microsoft.md)] account if they signed up for the [!include[cc-microsoft](../includes/cc-microsoft.md)] App Store, Skype, Xbox, Hotmail, or Outlook.com.</span></span> <span data-ttu-id="9a8c4-124">Verfügt der Experte noch nicht über ein [!include[cc-microsoft](../includes/cc-microsoft.md)]-Konto, kann er sich unter [https://account.microsoft.com/account](https://account.microsoft.com/account) für eines registrieren.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-124">If the expert doesn’t already have a [!include[cc-microsoft](../includes/cc-microsoft.md)] account, they can sign up for one by going to [https://account.microsoft.com/account](https://account.microsoft.com/account).</span></span>

## <a name="setup"></a><span data-ttu-id="9a8c4-125">Einrichtung</span><span class="sxs-lookup"><span data-stu-id="9a8c4-125">Setup</span></span>

<span data-ttu-id="9a8c4-126">Einen Experten können Sie mit [!include[pn-teams](../includes/pn-teams.md)] in drei einfachen Schritten eingliedern und mit ihm zusammenarbeiten:</span><span class="sxs-lookup"><span data-stu-id="9a8c4-126">You can onboard an expert and collaborate using [!include[pn-teams](../includes/pn-teams.md)] in three easy steps:</span></span>

| <span data-ttu-id="9a8c4-127">**Schritt**</span><span class="sxs-lookup"><span data-stu-id="9a8c4-127">**Step**</span></span> | <span data-ttu-id="9a8c4-128">**Beschreibung**</span><span class="sxs-lookup"><span data-stu-id="9a8c4-128">**Description**</span></span>                                                                  | <span data-ttu-id="9a8c4-129">**Wer führt diesen Schritt aus?**</span><span class="sxs-lookup"><span data-stu-id="9a8c4-129">**Who does this step?**</span></span>           |
|----------|----------------------------------------------------------------------------------|-----------------------------------|
|    <span data-ttu-id="9a8c4-130">1.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-130">1.</span></span>      | <span data-ttu-id="9a8c4-131">Aktivieren Sie einen Gastzugang für [!include[pn-teams](../includes/pn-teams.md)]</span><span class="sxs-lookup"><span data-stu-id="9a8c4-131">Enable guest access for [!include[pn-teams](../includes/pn-teams.md)]</span></span>                                                    | <span data-ttu-id="9a8c4-132">Administrator</span><span class="sxs-lookup"><span data-stu-id="9a8c4-132">Administrator</span></span>                     |
|    <span data-ttu-id="9a8c4-133">2.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-133">2.</span></span>      | <span data-ttu-id="9a8c4-134">Laden Sie den Experten ein, als Gast einem Team beizutreten, indem Sie sein [!include[cc-microsoft](../includes/cc-microsoft.md)]-Konto verwenden,</span><span class="sxs-lookup"><span data-stu-id="9a8c4-134">Invite the expert to join a team as a guest using the expert’s [!include[cc-microsoft](../includes/cc-microsoft.md)] account</span></span> | <span data-ttu-id="9a8c4-135">Administrator oder [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer und -Experte (zum Download [!include[pn-teams](../includes/pn-teams.md)])</span><span class="sxs-lookup"><span data-stu-id="9a8c4-135">Administrator or [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user and expert (to download [!include[pn-teams](../includes/pn-teams.md)])</span></span> |
|    <span data-ttu-id="9a8c4-136">3.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-136">3.</span></span>      | <span data-ttu-id="9a8c4-137">Tätigen Sie einen Anruf</span><span class="sxs-lookup"><span data-stu-id="9a8c4-137">Place a call</span></span>                                                                     | [!include[pn-remote-assist](../includes/pn-remote-assist.md)]<span data-ttu-id="9a8c4-138">-Benutzer oder -Experte</span><span class="sxs-lookup"><span data-stu-id="9a8c4-138">user or expert</span></span>     |

### <a name="step-1-enable-guest-access-for-teams"></a><span data-ttu-id="9a8c4-139">Schritt 1: Aktivieren Sie einen Gastzugang für Teams</span><span class="sxs-lookup"><span data-stu-id="9a8c4-139">Step 1: Enable guest access for teams</span></span>

1.  <span data-ttu-id="9a8c4-140">Wenn Sie der Administrator des hauptsächlichen [!include[pn-azure](../includes/pn-azure.md)]-Mandanten sind, gehen Sie zu <https://admin.microsoft.com/adminportal/>, um das Office Admin-Portal zu öffnen, und melden Sie sich an.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-140">If you’re the admin for the main [!include[pn-azure](../includes/pn-azure.md)] tenant, go to <https://admin.microsoft.com/adminportal/> to open the Office Admin portal, and then sign in.</span></span>

2.  <span data-ttu-id="9a8c4-141">Wählen Sie im Menü auf der linken Seite **Mehr anzeigen** \> **Einstellungen** \> **Dienste & Add-Ins**.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-141">From the menu on the left, select **Show More** \> **Settings** \> **Services & add-ins**.</span></span>

    <span data-ttu-id="9a8c4-142">![Dienste & Add-Ins](media/bf81ea48e3ccd560b6f44dbc72a73eb5.png "Dienste & Add-Ins")</span><span class="sxs-lookup"><span data-stu-id="9a8c4-142">![Service & add-ins](media/bf81ea48e3ccd560b6f44dbc72a73eb5.png "Service & add-ins")</span></span>

1.  <span data-ttu-id="9a8c4-143">Wählen Sie **[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)]** aus der Anwendungsliste aus.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-143">Select **[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)]** from the list of applications.</span></span>

    <span data-ttu-id="9a8c4-144">![Microsoft Teams](media/ad846431f181b1c6df362bc2e0e03167.png "Microsoft Teams")</span><span class="sxs-lookup"><span data-stu-id="9a8c4-144">![Microsoft Teams](media/ad846431f181b1c6df362bc2e0e03167.png "Microsoft Teams")</span></span>

1.  <span data-ttu-id="9a8c4-145">Wählen Sie **Einstellungen nach Benutzer/Lizenztyp**.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-145">Select **Settings by user/license type**.</span></span>

2.  <span data-ttu-id="9a8c4-146">Wählen Sie in der Dropdown-Liste **Gast** neben **Zu konfigurierenden Benutzer/Lizenztyp auswählen**.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-146">In the drop-down list next to **Select the user/license type you want to configure**, select **Guest**.</span></span>

3.  <span data-ttu-id="9a8c4-147">Setzen Sie **[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] für alle Benutzer dieses Typs an- oder ausschalten** auf **An** und wählen Sie anschließend **Speichern**.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-147">Set **Turn [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] on or off for all users of this type** to **On**, and then choose **Save**.</span></span>

    <span data-ttu-id="9a8c4-148">![Speichern](media/9f095e7553a4af03ff13ea6a29a9343a.png "Speichern")</span><span class="sxs-lookup"><span data-stu-id="9a8c4-148">![Save](media/9f095e7553a4af03ff13ea6a29a9343a.png "Save")</span></span>

4.  <span data-ttu-id="9a8c4-149">Warten Sie eine Stunde, bis sich die Einstellungen verteilt haben.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-149">Wait an hour for the settings to propagate.</span></span>

### <a name="step-2-invite-the-expert-to-join-a-team"></a><span data-ttu-id="9a8c4-150">Schritt 2: Den Experten zum Beitritt zu einem Team einladen</span><span class="sxs-lookup"><span data-stu-id="9a8c4-150">Step 2: Invite the expert to join a team</span></span>

1.  <span data-ttu-id="9a8c4-151">Wählen Sie **Einem Team beitreten oder eines anlegen** in [!include[pn-teams](../includes/pn-teams.md)], um ein Team anzulegen, falls es noch nicht existiert.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-151">In [!include[pn-teams](../includes/pn-teams.md)], select **Join or create a team** to create a team if it doesn’t already exist.</span></span> <span data-ttu-id="9a8c4-152">Der [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer und der Experte müssen in demselben Team sein, um kommunizieren zu können.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-152">The [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user and the expert must be on the same team to communicate.</span></span>

    <span data-ttu-id="9a8c4-153">![Einem Team beitreten oder eines anlegen](media/16e00f809d210dcb3b1e8c8e859b73da.png "Einem Team beitreten oder eines anlegen")</span><span class="sxs-lookup"><span data-stu-id="9a8c4-153">![Join or create a team](media/16e00f809d210dcb3b1e8c8e859b73da.png "Join or create a team")</span></span>

1.  <span data-ttu-id="9a8c4-154">Wenn Sie dazu aufgefordert werden, Mitglieder hinzuzufügen, geben Sie das [!include[cc-microsoft](../includes/cc-microsoft.md)]-Konto des Experten ein.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-154">When asked to add members, enter the expert’s [!include[cc-microsoft](../includes/cc-microsoft.md)] account.</span></span>

    <span data-ttu-id="9a8c4-155">![Microsoft-Konto](media/71e9276273f8f47b786f743416a2cb64.png "Microsoft-Konto")</span><span class="sxs-lookup"><span data-stu-id="9a8c4-155">![Microsoft account](media/71e9276273f8f47b786f743416a2cb64.png "Microsoft account")</span></span>

    > [!NOTE]
    > <span data-ttu-id="9a8c4-156">Wenn Sie nicht die Option zum Hinzufügen eines Gastes durch Eingabe einer E-Mail-Adresse sehen, ist wahrscheinlich der Gastzugang in dem [!include[pn-azure](../includes/pn-azure.md)]-Mandanten für [!include[pn-teams](../includes/pn-teams.md)] in Ihrem Unternehmen nicht aktiviert.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-156">If you don’t see the option to add a guest by typing an email address, it’s likely that guest access isn’t enabled on your company’s [!include[pn-azure](../includes/pn-azure.md)] tenant for [!include[pn-teams](../includes/pn-teams.md)].</span></span> <span data-ttu-id="9a8c4-157">Aktivieren Sie den Gastzugang wie bereits in diesem Inhalt beschrieben.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-157">Enable guest access as described earlier in this topic.</span></span>

1.  <span data-ttu-id="9a8c4-158">Der Experte erhält sofort eine E-Mail und kann den in ihr enthaltenen Link anklicken, um [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] zu öffnen (oder herunterzuladen).</span><span class="sxs-lookup"><span data-stu-id="9a8c4-158">The expert will immediately receive an email message and can click the link in the message to open (or download) [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)].</span></span> <span data-ttu-id="9a8c4-159">Diese Version von [!include[pn-teams](../includes/pn-teams.md)] ist kostenlos. Es handelt sich nicht um eine Testversion.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-159">This version of [!include[pn-teams](../includes/pn-teams.md)] is free and is not a trial version.</span></span>

### <a name="step-3-place-a-call"></a><span data-ttu-id="9a8c4-160">Schritt 3.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-160">Step 3.</span></span> <span data-ttu-id="9a8c4-161">Tätigen Sie einen Anruf</span><span class="sxs-lookup"><span data-stu-id="9a8c4-161">Place a call</span></span>

1.  <span data-ttu-id="9a8c4-162">Der Experte startet die [!include[pn-teams](../includes/pn-teams.md)]-App und der [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer auf [!include[pn-hololens](../includes/pn-hololens.md)] meldet sich wie gewohnt auf dem Konto an.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-162">The expert launches the [!include[pn-teams](../includes/pn-teams.md)] app and the [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user on the [!include[pn-hololens](../includes/pn-hololens.md)] signs in to their account as usual.</span></span>

    > [!IMPORTANT]
    > <span data-ttu-id="9a8c4-163">Startet der Experte zum ersten Mal [!include[pn-teams](../includes/pn-teams.md)] und wurde bisher nicht zu anderen Teams eingeladen, bringt [!include[pn-teams](../includes/pn-teams.md)] den Experten automatisch an den richtigen Ort.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-163">If this is the first time the expert has launched [!include[pn-teams](../includes/pn-teams.md)] and the expert has not been invited to any other teams, [!include[pn-teams](../includes/pn-teams.md)] will automatically take the expert to the correct place.</span></span> <span data-ttu-id="9a8c4-164">Wurde der Experte bereits zu anderen Teams ein geladen, muss er möglicherweise zum entsprechenden Mandanten wechseln.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-164">If the expert has been invited to other teams, the expert might need to switch to the appropriate tenant.</span></span>  
    >     
    > <span data-ttu-id="9a8c4-165">Zum Wechseln von Mandanten, wählen Sie den entsprechenden Gastmandanten im Dropdown-Menü rechts oben im Fenster aus:</span><span class="sxs-lookup"><span data-stu-id="9a8c4-165">To switch tenants, in the drop-down menu in the upper-right corner of the window, select the appropriate guest tenant:</span></span>
    
    <span data-ttu-id="9a8c4-166">![Gastmandant](media/55237a5359fb66daf7bbb9413adab6b9.png "Gastmandant")</span><span class="sxs-lookup"><span data-stu-id="9a8c4-166">![Guest tenant](media/55237a5359fb66daf7bbb9413adab6b9.png "Guest tenant")</span></span>
       
    > [!NOTE]
    > [!include[pn-teams](../includes/pn-teams.md)] <span data-ttu-id="9a8c4-167">benötigt möglicherweise einige Sekunden, um neu zu laden.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-167">might take a few seconds to reload.</span></span>
    
1.  <span data-ttu-id="9a8c4-168">Beide Parteien können einen Anruf tätigen.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-168">Either party can make the call.</span></span> <span data-ttu-id="9a8c4-169">Unter Umständen müssen Sie in den Kontakten nach der richtigen Person suchen.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-169">You might need to search contacts to find the right person.</span></span>

    > [!NOTE]
    > <span data-ttu-id="9a8c4-170">Der Gast kann jedes Mitglied desselben Teams anrufen.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-170">The guest can call any member on the same team.</span></span> <span data-ttu-id="9a8c4-171">Zur Erweiterung dieser Funktionalität, laden Sie alle anderen Mitglieder in Ihrem Unternehmen ein, die von dem Zugriff auf diesen neuen Experten profitieren würden.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-171">To extend this functionality, invite any other members within your company who would benefit from being able to access this new expert.</span></span>

## <a name="working-with-annotations"></a><span data-ttu-id="9a8c4-172">Arbeiten mit Anmerkungen</span><span class="sxs-lookup"><span data-stu-id="9a8c4-172">Working with annotations</span></span>

<span data-ttu-id="9a8c4-173">Sobald [!include[pn-teams](../includes/pn-teams.md)] installiert ist, kann der Experte über [!include[pn-remote-assist](../includes/pn-remote-assist.md)] auf einem [!include[pn-hololens](../includes/pn-hololens.md)] Videoanrufe zu Kontakten tätigen (und von diesen empfangen).</span><span class="sxs-lookup"><span data-stu-id="9a8c4-173">Once [!include[pn-teams](../includes/pn-teams.md)] is installed, the expert can make video calls to (and receive them from) contacts using [!include[pn-remote-assist](../includes/pn-remote-assist.md)] on a [!include[pn-hololens](../includes/pn-hololens.md)].</span></span>

<span data-ttu-id="9a8c4-174">In einem Anruf sieht der Experte den Platz des Kontakts – einschließlich der Hologramme – und kann die Mixed Reality-Symbolleiste im Fenster des Videoanrufs verwenden, um Hologramme hinzuzufügen.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-174">When in a call, the expert will see the contact’s space—including the holograms—and can use the Mixed Reality toolbar in the video call window to add holograms.</span></span>

<span data-ttu-id="9a8c4-175">![Mixed Reality-Symbolleiste](media/071f358ab6bbf7c2072b15d9203a1593.png "Mixed Reality-Symbolleiste")</span><span class="sxs-lookup"><span data-stu-id="9a8c4-175">![Mixed Reality toolbar](media/071f358ab6bbf7c2072b15d9203a1593.png "Mixed Reality toolbar")</span></span>

## <a name="draw-and-annotate"></a><span data-ttu-id="9a8c4-176">Zeichnen und anmerken</span><span class="sxs-lookup"><span data-stu-id="9a8c4-176">Draw and annotate</span></span>

### <a name="edit-mode"></a><span data-ttu-id="9a8c4-177">Bearbeitungsmodus</span><span class="sxs-lookup"><span data-stu-id="9a8c4-177">Edit mode</span></span>

<span data-ttu-id="9a8c4-178">Um den Raum eines Kontaktes mit Anmerkungen zu versehen, führen Sie zunächst folgende Schritte aus, um den Videostream anzuhalten und in den Bearbeitungsmodus zu wechseln:</span><span class="sxs-lookup"><span data-stu-id="9a8c4-178">To start annotating a contact’s space, first do one of the following to pause the video stream and enter edit mode:</span></span>

-   <span data-ttu-id="9a8c4-179">Wählen Sie eine beliebige Stelle im Anruffenster aus.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-179">Select anywhere in the call window.</span></span>

-   <span data-ttu-id="9a8c4-180">Wählen Sie eines der Elemente in der Mixed Reality-Symbolleiste aus.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-180">Select one of the items on the Mixed Reality toolbar.</span></span>

-   <span data-ttu-id="9a8c4-181">Wählen Sie **Bearbeitung beginnen**.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-181">Select **Start editing**.</span></span>

<span data-ttu-id="9a8c4-182">Im Bearbeitungsmodus sieht der Experte weiterhin einen Livestream des Anrufs in einer Ecke des App-Fensters.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-182">In edit mode, the expert will still see a live stream of the call in the corner of the app window.</span></span>

### <a name="add-arrows-ink-and-files"></a><span data-ttu-id="9a8c4-183">Hinzufügen von Pfeilen, Tinte und Dateien</span><span class="sxs-lookup"><span data-stu-id="9a8c4-183">Add arrows, ink, and files</span></span>

<span data-ttu-id="9a8c4-184">Verwenden Sie die Mixed Reality-Symbolleiste zum Platzieren von Pfeilen, zum Zeichnen oder zum Hinzufügen von Dateien:</span><span class="sxs-lookup"><span data-stu-id="9a8c4-184">Use the Mixed Reality toolbar to place arrows, draw, or add files:</span></span>

-   <span data-ttu-id="9a8c4-185">Zum Hinzufügen von Pfeilen, wählen Sie **Pfeil platzieren** ![Pfeil platzieren](media/6584f4b7932378aa23f6efbf460b304c.png "Pfeil platzieren").</span><span class="sxs-lookup"><span data-stu-id="9a8c4-185">To add arrows, select **Place arrow** ![Place arrow](media/6584f4b7932378aa23f6efbf460b304c.png "Place arrow") .</span></span>

-   <span data-ttu-id="9a8c4-186">Zum Hinzufügen von Tinte, wählen Sie **Tinte** ![Tinte](media/187307e30fd713f5ae67aba854b78bc4.png "Tinte").</span><span class="sxs-lookup"><span data-stu-id="9a8c4-186">To add ink, select **Ink** ![Ink](media/187307e30fd713f5ae67aba854b78bc4.png "Ink") .</span></span>

-   <span data-ttu-id="9a8c4-187">Zum Ändern des Pfeils oder der Tintenfarbe, wählten Sie **Eine Farbe wählen** ![Eine Farbe wählen](media/5d9d3c70cf19ed175a8dc1ad71a60fc5.png "Eine Farbe wählen").</span><span class="sxs-lookup"><span data-stu-id="9a8c4-187">To change the arrow or ink color, select **Pick a color** ![Pick a color](media/5d9d3c70cf19ed175a8dc1ad71a60fc5.png "Pick a color") .</span></span>

-   <span data-ttu-id="9a8c4-188">Zum Hinzufügen einer Datei, wählen Sie **Dateien einfügen** ![Dateien einfügen](media/41aa538d3be8e163215f7d9374abe90e.png "Dateien einfügen") und fügen anschließend eine Bild- oder PDF-Datei hinzu.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-188">To add a file, select **Insert files** ![Insert files](media/41aa538d3be8e163215f7d9374abe90e.png "Insert files"), and then add an image file or a PDF file.</span></span>

    > [!NOTE]
    > <span data-ttu-id="9a8c4-189">Der Experte kann Bilder nach dem Hinzufügen nicht bewegen, entfernen oder ihre Größe ändern.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-189">After adding them, images can’t be moved, deleted, or resized by the expert.</span></span>

### <a name="finish-editing"></a><span data-ttu-id="9a8c4-190">Bearbeitung abschließen</span><span class="sxs-lookup"><span data-stu-id="9a8c4-190">Finish editing</span></span>

<span data-ttu-id="9a8c4-191">Wenn Sie mit die Anmerkungen beendet haben, führen Sie eine der folgenden Aktionen aus, um die Bearbeitung abzuschließen und in den Live-Modus zurückzukehren:</span><span class="sxs-lookup"><span data-stu-id="9a8c4-191">When done annotating, do one of the following to finish editing and return to live mode:</span></span>

-   <span data-ttu-id="9a8c4-192">Wählen Sie **Bearbeitung beenden**.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-192">Select **Stop editing**.</span></span>

-   <span data-ttu-id="9a8c4-193">Wählen Sie den Live-Video-Feed in der Ecke Ihres Bildschirms aus.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-193">Select the live video feed in the corner of your screen.</span></span>

### <a name="make-changes-to-edits"></a><span data-ttu-id="9a8c4-194">Änderungen an den Bearbeitungen vornehmen</span><span class="sxs-lookup"><span data-stu-id="9a8c4-194">Make changes to edits</span></span>

<span data-ttu-id="9a8c4-195">Um Änderungen an Bearbeitungen vorzunehmen, gehen Sie wie folgt vor:</span><span class="sxs-lookup"><span data-stu-id="9a8c4-195">To make changes to edits, do one of the following:</span></span>

-   <span data-ttu-id="9a8c4-196">Wählen Sie im Bearbeitungsmodus **Rückgängig**, um die letzte Aktion rückgängig zu machen.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-196">While in edit mode, select **Undo** to undo the last action.</span></span>

-   <span data-ttu-id="9a8c4-197">Wählen Sie im Bearbeitungsmodus **Alles löschen** ![Alles löschen](media/3aab547aa81003ad181eceadc2c83a47.png "Alles löschen"), um alle während dieser Bearbeitungssitzung erstellten Anmerkungen zu löschen.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-197">While in edit mode, select **Erase all** ![Erase all](media/3aab547aa81003ad181eceadc2c83a47.png "Erase all") to erase all of the annotations made during that editing session.</span></span>

-   <span data-ttu-id="9a8c4-198">Wählen Sie im Live-Modus **Alles löschen** ![Alles löschen](media/3aab547aa81003ad181eceadc2c83a47.png "Alles löschen"), um alle während dieses Anrufs erstellten Anmerkungen zu löschen.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-198">While in live mode, select **Erase all** ![Erase all](media/3aab547aa81003ad181eceadc2c83a47.png "Erase all") to erase all of the annotations made during that call.</span></span>

> [!NOTE]
> <span data-ttu-id="9a8c4-199">Bestimmte Zeichnungen oder Pfeile können nicht entfernt werden.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-199">Specific drawings or arrows can’t be removed.</span></span> <span data-ttu-id="9a8c4-200">Nur der [!include[pn-hololens](../includes/pn-hololens.md)]-Benutzer kann Änderungen an Bildern vornehmen oder löschen, die von einem Experten hinzugefügt wurden.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-200">Only the [!include[pn-hololens](../includes/pn-hololens.md)] user can make changes to or delete pictures added by an expert.</span></span>

## <a name="share-your-desktop-or-a-running-application-with-a-remote-assist-user"></a><span data-ttu-id="9a8c4-201">Teilen des Desktops oder einer laufenden Anwendung mit einem Remote Assist-Benutzer</span><span class="sxs-lookup"><span data-stu-id="9a8c4-201">Share your desktop or a running application with a Remote Assist user</span></span>

<span data-ttu-id="9a8c4-202">Wenn Sie Ihren Desktop oder Ihre laufende Anwendung mit einem [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer teilen, ändert sich der Video-Feed des Benutzers in eine einheitliche Farbe.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-202">When you share your desktop or running application with a [!include[pn-remote-assist](../includes/pn-remote-assist.md)] user, the user's video feed will change to a solid color.</span></span> <span data-ttu-id="9a8c4-203">Sie können weiterhin alle Werkzeuge der Symbolleiste nutzen, auch wenn ihr Video-Feed nicht mehr angezeigt wird.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-203">They'll still be able to use all the tools in the toolbar even though their video feed will no longer be displayed.</span></span>

<span data-ttu-id="9a8c4-204">Um Ihren Desktop oder eine laufende Anwendung zu teilen:</span><span class="sxs-lookup"><span data-stu-id="9a8c4-204">To share your desktop or a running application:</span></span>

1. <span data-ttu-id="9a8c4-205">Wählen Sie in [!include[pn-teams](../includes/pn-teams.md)] die Schaltfläche **Teilen-Leiste öffnen**.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-205">In [!include[pn-teams](../includes/pn-teams.md)], select the **Open share tray** button.</span></span>

   <span data-ttu-id="9a8c4-206">![Schaltfläche Teilen-Leiste](media/share-tray.PNG "Schaltfläche Teilen-Leiste")</span><span class="sxs-lookup"><span data-stu-id="9a8c4-206">![Share tray button](media/share-tray.PNG "Share tray button")</span></span>
   
2. <span data-ttu-id="9a8c4-207">Wählen Sie den Bildschirm aus, den Sie teilen möchten.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-207">Select the screen you want to share.</span></span>

> [!NOTE]
> <span data-ttu-id="9a8c4-208">Sie können nur eine Anwendung oder einen Bildschirm gleichzeitig teilen.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-208">You can only share one application or screen at a time.</span></span> <span data-ttu-id="9a8c4-209">Wählen Sie zum Teilen eines anderen Bildschirms die Schaltfläche **Teilen-Leiste schließen**, um das Teilen zu beenden. Wählen Sie nun einen anderen Bildschirm aus und beginnen erneut mit dem Teilen.</span><span class="sxs-lookup"><span data-stu-id="9a8c4-209">If you want to share a different screen, select the **Close share tray** button to stop sharing, select a different screen, and then start sharing again.</span></span>

### <a name="see-also"></a><span data-ttu-id="9a8c4-210">Siehe auch</span><span class="sxs-lookup"><span data-stu-id="9a8c4-210">See also</span></span>
[<span data-ttu-id="9a8c4-211">Benutzerhandbuch</span><span class="sxs-lookup"><span data-stu-id="9a8c4-211">User Guide</span></span>](user-guide.md)<br/>
[<span data-ttu-id="9a8c4-212">Anleitungsvideos</span><span class="sxs-lookup"><span data-stu-id="9a8c4-212">How-to videos</span></span>](videos.md)<br/>
[<span data-ttu-id="9a8c4-213">Häufig gestellte Fragen</span><span class="sxs-lookup"><span data-stu-id="9a8c4-213">FAQ</span></span>](faq.md)<br/>
