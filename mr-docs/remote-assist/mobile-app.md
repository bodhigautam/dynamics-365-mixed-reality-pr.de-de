---
author: MatthewJonPaul
description: Benutzerhandbuch für die Dynamics 365 Remote Assist Mobile-App
ms.author: mapau
ms.date: 04/02/2019
ms.service: crm-online
ms.topic: article
title: Benutzerhandbuch für die Dynamics 365 Remote Assist Mobile-App
ms.reviewer: v-brycho
ms.openlocfilehash: 12a63de66e562630ea4501fec0531ee9717379d1
ms.sourcegitcommit: 157b70ec12e7cc459231aa5e32d311ebc09727d8
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2019
ms.locfileid: "1575547"
---
# <a name="dynamics-365-remote-assist-mobile-user-guide-in-preview"></a><span data-ttu-id="9beef-103">Benutzerhandbuch für die Dynamics 365 Remote Assist Mobile-App (Vorschau)</span><span class="sxs-lookup"><span data-stu-id="9beef-103">Dynamics 365 Remote Assist Mobile User Guide (in preview)</span></span>

<span data-ttu-id="9beef-104">[Dieses Thema ist Teil der Dokumentation zur Vorabversion und kann geändert werden.]</span><span class="sxs-lookup"><span data-stu-id="9beef-104">[This topic is pre-release documentation and is subject to change.]</span></span>

<span data-ttu-id="9beef-105">Die Mobile-App Microsoft Dynamics 365 Remote Assist erweitert die Funktionen von Dynamics 365 Remote Assist für die Arbeit mit Android ARCore-fähigen Telefonen (zusätzlich zu Microsoft HoloLens).</span><span class="sxs-lookup"><span data-stu-id="9beef-105">The Microsoft Dynamics 365 Remote Assist mobile app extends the capabilities of Dynamics 365 Remote Assist to work with Android ARCore-capable phones (in addition to Microsoft HoloLens).</span></span> <span data-ttu-id="9beef-106">Techniker können sich mit ihren Telefonen mit einem Experten von Microsoft Teams verbinden und mit ihm kooperieren.</span><span class="sxs-lookup"><span data-stu-id="9beef-106">Technicians can use their phones to connect and collaborate with an expert on Microsoft Teams.</span></span> <span data-ttu-id="9beef-107">Mithilfe von Videoanruf- und Mixed Reality-Anmerkungen können sie das, was sie sehen, mit dem Experten teilen, um Probleme gemeinsam schneller zu lösen.</span><span class="sxs-lookup"><span data-stu-id="9beef-107">Using live video calling and mixed reality annotations, they can share what they see with the expert to troubleshoot problems together, faster.</span></span> 

## <a name="what-youll-need"></a><span data-ttu-id="9beef-108">Was Sie benötigen</span><span class="sxs-lookup"><span data-stu-id="9beef-108">What you’ll need</span></span>

<span data-ttu-id="9beef-109">Für die Mobile-App Remote Assist benötigen Sie:</span><span class="sxs-lookup"><span data-stu-id="9beef-109">You’ll need the following to use the Remote Assist mobile app:</span></span>

- <span data-ttu-id="9beef-110">An Android ARCore-fähiges Smartphone (Tablets werden derzeit nicht unterstützt) mit ARCore installiert.</span><span class="sxs-lookup"><span data-stu-id="9beef-110">An Android ARCore-capable phone (tablets are not currently supported), with ARCore installed.</span></span> [<span data-ttu-id="9beef-111">Hier erhalten Sie die vollständige Liste unterstützter Geräte:</span><span class="sxs-lookup"><span data-stu-id="9beef-111">View the full list of supported devices.</span></span>](https://developers.google.com/ar/discover/supported-devices) 

- <span data-ttu-id="9beef-112">Ein Google Play-Konto.</span><span class="sxs-lookup"><span data-stu-id="9beef-112">A Google Play account.</span></span>

- <span data-ttu-id="9beef-113">Die Mobile-App Remote Assist.</span><span class="sxs-lookup"><span data-stu-id="9beef-113">The Remote Assist mobile app.</span></span>

- <span data-ttu-id="9beef-114">Ein Microsoft Teams-Konto (kostenlos verfügbar).</span><span class="sxs-lookup"><span data-stu-id="9beef-114">A Microsoft Teams account (available for free).</span></span>

- <span data-ttu-id="9beef-115">Ein Microsoft Teams-Desktopclient, auf dem Windows 10 ausgeführt wird (für den Remote-Experten, der den Anruf erhält).</span><span class="sxs-lookup"><span data-stu-id="9beef-115">A Microsoft Teams desktop client running Windows 10 (for the remote expert receiving the call).</span></span>

- <span data-ttu-id="9beef-116">Eine Internetverbindung.</span><span class="sxs-lookup"><span data-stu-id="9beef-116">An internet connection.</span></span> <span data-ttu-id="9beef-117">Die besten Ergebnisse erzielen Sie mit mindestens 1,5 MB Bandbreite.</span><span class="sxs-lookup"><span data-stu-id="9beef-117">At least 1.5 MB of bandwidth is recommended for the best experience.</span></span>

<span data-ttu-id="9beef-118">Wenn Sie Remote Assist mit Dynamics 365 for Field Service verwenden möchten, damit Sie automatisch Anrufdaten in einem Field Service-Arbeitsauftrag erfassen können, benötigen Sie auch eine der folgenden Komponenten oder beide:</span><span class="sxs-lookup"><span data-stu-id="9beef-118">If you want to use Remote Assist together with Dynamics 365 for Field Service so you can automatically log call information to a Field Service work order, you’ll also need one or both of the following:</span></span>

- <span data-ttu-id="9beef-119">Dynamics 365 for Field Service Webanwendung</span><span class="sxs-lookup"><span data-stu-id="9beef-119">Dynamics 365 for Field Service web application</span></span>

- <span data-ttu-id="9beef-120">Mobile-App Dynamics 365 for Field Service</span><span class="sxs-lookup"><span data-stu-id="9beef-120">Dynamics 365 for Field Service mobile app</span></span> 

## <a name="get-started"></a><span data-ttu-id="9beef-121">Erste Schritte</span><span class="sxs-lookup"><span data-stu-id="9beef-121">Get started</span></span>

### <a name="step-1-sign-up-for-a-microsoft-teams-account-free"></a><span data-ttu-id="9beef-122">Schritt 1: Melden Sie sich bei einem Microsoft Teams-Konto an (kostenlos)</span><span class="sxs-lookup"><span data-stu-id="9beef-122">Step 1: Sign up for a Microsoft Teams account (free)</span></span>

<span data-ttu-id="9beef-123">Ein Microsoft Teams-Konto ist erforderlich, um die Remote Assist Mobile-App verwenden zu können.</span><span class="sxs-lookup"><span data-stu-id="9beef-123">A Microsoft Teams account is required to use Remote Assist mobile.</span></span> <span data-ttu-id="9beef-124">Wenn Sie nicht bereits ein Teams-Konto haben, können Sie [ein Teams-Konto kostenlos erstellen](https://businessstore.microsoft.com/en-us/create-account/signup?products=CFQ7TTC0K8P5:0001&lm=deeplink&lmsrc=freePageWeb&cmpid=FreemiumSignUpHeader).</span><span class="sxs-lookup"><span data-stu-id="9beef-124">If you don’t already have a Teams account, you can [create a Teams account for free](https://businessstore.microsoft.com/en-us/create-account/signup?products=CFQ7TTC0K8P5:0001&lm=deeplink&lmsrc=freePageWeb&cmpid=FreemiumSignUpHeader).</span></span> 

### <a name="step-2-download-the-app"></a><span data-ttu-id="9beef-125">Schritt 2: Laden Sie die App herunter</span><span class="sxs-lookup"><span data-stu-id="9beef-125">Step 2: Download the app</span></span>

1.  <span data-ttu-id="9beef-126">Rufen Sie den Google Play Store auf: https://play.google.com/store/apps/details?id=com.microsoft.ramobile.</span><span class="sxs-lookup"><span data-stu-id="9beef-126">Go to the Google Play Store: https://play.google.com/store/apps/details?id=com.microsoft.ramobile.</span></span>

2.  <span data-ttu-id="9beef-127">Wählen Sie **Download** aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-127">Select **Download**.</span></span> 
 
### <a name="step-3-sign-in-to-the-app-for-the-first-time"></a><span data-ttu-id="9beef-128">Schritt 3: Melden Sie sich zum ersten Mal bei der App an</span><span class="sxs-lookup"><span data-stu-id="9beef-128">Step 3: Sign in to the app for the first time</span></span>

1.  <span data-ttu-id="9beef-129">Wenn Sie die App heruntergeladen haben, öffnen Sie sie auf Ihrem Android-Smartphone.</span><span class="sxs-lookup"><span data-stu-id="9beef-129">After you’ve downloaded the app, open it on your Android phone.</span></span> 

2.  <span data-ttu-id="9beef-130">Melden Sie sich mit Ihrem Microsoft Teams-Konto an.</span><span class="sxs-lookup"><span data-stu-id="9beef-130">Sign in with your Microsoft Teams account.</span></span>

    <span data-ttu-id="9beef-131">![Anmeldebildschirm](media/sign-in.png "Anmeldebildschirm")</span><span class="sxs-lookup"><span data-stu-id="9beef-131">![Sign-in screen](media/sign-in.png "Sign-in screen")</span></span>
  
    > [!TIP]
    > <span data-ttu-id="9beef-132">Die Anmeldeadresse hat die Form: Benutzername@Unternehmen.</span><span class="sxs-lookup"><span data-stu-id="9beef-132">The sign-in address will be in the form: username@company.</span></span>
    
3.  <span data-ttu-id="9beef-133">Wählen Sie in dem daraufhin angezeigten Dialogfeld **Funktion aktivieren** aus, um Remote Assist mit Dynamics 365 for Field Service zu verknüpfen, oder wählen Sie **Überspringen** aus, wenn Sie im Moment nicht auf die Apps klicken möchten.</span><span class="sxs-lookup"><span data-stu-id="9beef-133">In the dialog box that appears, select **Enable Feature** to link Remote Assist to Dynamics 365 for Field Service, or select **Skip** if you don’t want to link the apps at this time.</span></span> <span data-ttu-id="9beef-134">Sie können sie später über **Einstellungen** verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="9beef-134">You can always link them later through **Settings**.</span></span> <span data-ttu-id="9beef-135">Wenn Sie mehr zur gemeinsamen Funktion der Apps erfahren möchten, wählen Sie **Weitere Informationen** aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-135">To learn more about how the apps work together, select **Learn More**.</span></span>

    <span data-ttu-id="9beef-136">![Field Service-Bildschirm](media/field-service.PNG "Field Service-Bildschirm")</span><span class="sxs-lookup"><span data-stu-id="9beef-136">![Field Service screen](media/field-service.PNG "Field Service screen")</span></span>
  
## <a name="make-a-call"></a><span data-ttu-id="9beef-137">Telefonanruf vornehmen</span><span class="sxs-lookup"><span data-stu-id="9beef-137">Make a call</span></span>
<span data-ttu-id="9beef-138">Nach der Anmeldung sehen Sie die Seite **Kontakte**, die Hauptseite der Mobile-App Remote Assist.</span><span class="sxs-lookup"><span data-stu-id="9beef-138">After signing in, you’ll see the **Contacts** page, which is the main page in the Remote Assist mobile app.</span></span> <span data-ttu-id="9beef-139">Auf der Seite **Kontakte** sind die Kontakte nach der Aktualität der Anrufe angeordnet.</span><span class="sxs-lookup"><span data-stu-id="9beef-139">On the **Contacts** page, your contacts are organized by the most recent calls.</span></span>

<span data-ttu-id="9beef-140">![Kontaktbildschirm](media/contacts.PNG "Kontaktbildschirm")</span><span class="sxs-lookup"><span data-stu-id="9beef-140">![Contacts screen](media/contacts.PNG "Contacts screen")</span></span>


<span data-ttu-id="9beef-141">So nehmen Sie einen Telefonanruf vor:</span><span class="sxs-lookup"><span data-stu-id="9beef-141">To make a call:</span></span>

1.  <span data-ttu-id="9beef-142">Wählen Sie ![Schaltfläche „Suchen“](media/search-icon.PNG "Schaltfläche „Suchen“") aus, geben Sie den Namen des zu suchenden Kontakts ein und wählen Sie den Kontakt dann in der Ergebnisliste aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-142">Select ![Search button](media/search-icon.PNG "Search button"), enter the name of the contact to search for, and then select the contact from the resulting list.</span></span>
       
    <span data-ttu-id="9beef-143">![Nach einem Kontakt suchen](media/search-contact.PNG "Nach einem Kontakt suchen")</span><span class="sxs-lookup"><span data-stu-id="9beef-143">![Search for a contact](media/search-contact.PNG "Search for a contact")</span></span>
    
2.  <span data-ttu-id="9beef-144">Wählen Sie auf der Kontaktkarte **Anruf starten** aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-144">In the contact card, select **Launch Call**.</span></span>

    <span data-ttu-id="9beef-145">![Bildschirm „Anruf starten“](media/launch-call.PNG "Bildschirm „Anruf starten“")</span><span class="sxs-lookup"><span data-stu-id="9beef-145">![Launch Call screen](media/launch-call.PNG "Launch Call screen")</span></span>
  
    <span data-ttu-id="9beef-146">Schalten Sie den Anruf mithilfe der Schaltflächen in der Leiste am unteren Bildschirmrand stumm, unterbrechen Sie den Videofeed, schalten Sie das Lautsprechermikrofon ein oder beenden Sie den Anruf.</span><span class="sxs-lookup"><span data-stu-id="9beef-146">Use the buttons in the bar at the bottom of the screen to mute the call, pause the video feed, turn on the speaker phone, or end the call.</span></span>
    
    <span data-ttu-id="9beef-147">![Anrufkontrollen](media/call-controls.PNG "Anrufkontrollen")</span><span class="sxs-lookup"><span data-stu-id="9beef-147">![Call controls](media/call-controls.PNG "Call controls")</span></span>
  
 
## <a name="add-annotations"></a><span data-ttu-id="9beef-148">Anmerkungen hinzufügen</span><span class="sxs-lookup"><span data-stu-id="9beef-148">Add annotations</span></span>
<span data-ttu-id="9beef-149">Sie können Anmerkungen in Ihren Bildschirm einfügen, um sie an einen Experten im Anruf weiterzugeben.</span><span class="sxs-lookup"><span data-stu-id="9beef-149">You can add annotations to your screen to share with an expert on the call.</span></span> <span data-ttu-id="9beef-150">Um Anmerkungen erstellen zu können, muss Ihr Smartphone mindestens eine Ebene (vertikal oder horizontal) in Ihrem Arbeitsbereich erkennen können.</span><span class="sxs-lookup"><span data-stu-id="9beef-150">To create annotations, your phone needs to recognize at least one plane (vertical or horizontal) in your work area.</span></span> <span data-ttu-id="9beef-151">Scannen Sie dazu Ihren Arbeitsbereich mit dem Smartphone.</span><span class="sxs-lookup"><span data-stu-id="9beef-151">You do this by scanning your work area with the phone.</span></span> <span data-ttu-id="9beef-152">Wenn eine Ebene erkannt wurde, sehen Sie eine Bestätigungsvisualisierung und die Anmerkungssymbolleiste wird am oberen Bildschirmrand angezeigt:</span><span class="sxs-lookup"><span data-stu-id="9beef-152">When a plane has been recognized, you’ll see a confirmation visualization and the annotation toolbar will appear at the top of the screen:</span></span>

<span data-ttu-id="9beef-153">![Anmerkungen hinzufügen](media/annotation-bar-full-screen.PNG "Anmerkungen hinzufügen")</span><span class="sxs-lookup"><span data-stu-id="9beef-153">![Add annotations](media/annotation-bar-full-screen.PNG "Add annotations")</span></span>
  
> [!NOTE] 
> <span data-ttu-id="9beef-154">Wenn Sie Ihr Telefon sperren oder Remote Assist minimieren, werden die erkannten Ebenen automatisch erneut angezeigt, wenn Ihr Smartphone die Umgebung erkennt.</span><span class="sxs-lookup"><span data-stu-id="9beef-154">If you lock your phone or minimize Remote Assist, the recognized planes will reappear automatically as soon as your phone recognizes the environment.</span></span>

### <a name="add-an-annotation"></a><span data-ttu-id="9beef-155">Eine Anmerkung hinzufügen</span><span class="sxs-lookup"><span data-stu-id="9beef-155">Add an annotation</span></span>
<span data-ttu-id="9beef-156">Sie können eine Anmerkung mithilfe der Schaltflächen auf der Anmerkungssymbolleiste hinzufügen:</span><span class="sxs-lookup"><span data-stu-id="9beef-156">You can add an annotation by using the buttons on the annotation toolbar:</span></span>

<span data-ttu-id="9beef-157">![Anmerkungsleiste](media/annotation-bar.PNG "Anmerkungsleiste")</span><span class="sxs-lookup"><span data-stu-id="9beef-157">![Annotation bar](media/annotation-bar.PNG "Annotation bar")</span></span>
  
<span data-ttu-id="9beef-158">Wenn Sie beispielsweise einen Pfeil hinzufügen möchten, tippen Sie auf das Pfeil-Tool und streichen mit dem Finger zu der Stelle, an der sie den Pfeil platzieren möchten.</span><span class="sxs-lookup"><span data-stu-id="9beef-158">For example, to add an arrow, tap the arrow tool and drag your finger to the spot where you want to place the arrow.</span></span>

### <a name="minimize-or-restore-the-toolbar"></a><span data-ttu-id="9beef-159">Minimieren oder stellen Sie die Symbolleiste wieder her</span><span class="sxs-lookup"><span data-stu-id="9beef-159">Minimize or restore the toolbar</span></span>

<span data-ttu-id="9beef-160">So minimieren Sie die Symbolleiste, wenn Sie einen größeren Bereich des Bildschirms sehen möchten:</span><span class="sxs-lookup"><span data-stu-id="9beef-160">To minimize the toolbar if you want to see more of the screen:</span></span>

- <span data-ttu-id="9beef-161">Wählen Sie den Pfeil rechts in der Symbolleiste aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-161">Select the arrow on the right side of the toolbar.</span></span> 

  <span data-ttu-id="9beef-162">![Leiste minimieren](media/minimize-bar.PNG "Leiste minimieren")</span><span class="sxs-lookup"><span data-stu-id="9beef-162">![Minimize bar](media/minimize-bar.PNG "Minimize bar")</span></span>
 
<span data-ttu-id="9beef-163">So stellen Sie die ursprüngliche Größe der Symbolleiste wieder her:</span><span class="sxs-lookup"><span data-stu-id="9beef-163">To restore the toolbar to its original size:</span></span>

- <span data-ttu-id="9beef-164">Wählen Sie die Schaltfläche **Stift** aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-164">Select the **Pen** button.</span></span> 

  <span data-ttu-id="9beef-165">![Schaltfläche „Stift“](media/pen-button.PNG "Schaltfläche „Stift“")</span><span class="sxs-lookup"><span data-stu-id="9beef-165">![Pen button](media/pen-button.PNG "Pen button")</span></span>

### <a name="make-the-experts-video-feed-bigger"></a><span data-ttu-id="9beef-166">Experten-Videofeed vergrößern</span><span class="sxs-lookup"><span data-stu-id="9beef-166">Make the expert’s video feed bigger</span></span>

<span data-ttu-id="9beef-167">Wenn Sie eines Experten anrufen, wird der Experten-Videofeed unten rechts auf Ihrem Smartphone angezeigt.</span><span class="sxs-lookup"><span data-stu-id="9beef-167">When you call an expert, the expert’s video feed appears in the lower-right corner of your phone screen.</span></span> <span data-ttu-id="9beef-168">Tippen Sie auf den Feed, um den Experten-Videofeed zu vergrößern.</span><span class="sxs-lookup"><span data-stu-id="9beef-168">To make the expert’s video feed bigger, tap the feed.</span></span> <span data-ttu-id="9beef-169">Tippen Sie erneut auf den Feed, um wieder die ursprüngliche Größe einzustellen.</span><span class="sxs-lookup"><span data-stu-id="9beef-169">Tap the feed again to return to the original size.</span></span>

<span data-ttu-id="9beef-170">![Experten-Videofeed](media/expert-annotating.PNG "Experten-Videofeed")</span><span class="sxs-lookup"><span data-stu-id="9beef-170">![Expert video feed](media/expert-annotating.PNG "Expert video feed")</span></span>
  
<span data-ttu-id="9beef-171">Wenn der Experte kommentiert, wird ein Benachrichtigungssymbol im Feed des Experten angezeigt.</span><span class="sxs-lookup"><span data-stu-id="9beef-171">If the expert is annotating, a notification icon will appear on the expert's feed.</span></span>  

## <a name="switch-the-camera-view-from-portrait-to-landscape"></a><span data-ttu-id="9beef-172">Kameraansicht Hochformat zu Querformat wechseln</span><span class="sxs-lookup"><span data-stu-id="9beef-172">Switch the camera view from portrait to landscape</span></span>

<span data-ttu-id="9beef-173">Sie können die Ausrichtung der Kameraansicht während eines Anrufs von Hochformat zu Querformat wechseln, indem Sie die Ausrichtung Ihres Smartphones ändern.</span><span class="sxs-lookup"><span data-stu-id="9beef-173">You can switch the orientation of the camera view from portrait to landscape while in a call by changing the orientation of your phone.</span></span> <span data-ttu-id="9beef-174">Querformat bietet ein breiteres Sichtfeld was die Benutzerfreundlichkeit für den Remote-Experten im Anruf verbessern kann.</span><span class="sxs-lookup"><span data-stu-id="9beef-174">Using landscape view provides a wider field of view, which may improve the experience for the remote expert on the call.</span></span>
   
## <a name="use-remote-assist-together-with-dynamics-365-for-field-service"></a><span data-ttu-id="9beef-175">Use Remote Assist zusammen mit Dynamics 365 for Field Service verwenden</span><span class="sxs-lookup"><span data-stu-id="9beef-175">Use Remote Assist together with Dynamics 365 for Field Service</span></span>

<span data-ttu-id="9beef-176">Sie können Remote Assist zusammen mit Dynamics 365 for Field Service verwenden, wenn Sie automatisch Anrufdaten für einen Field Service-Arbeitsauftrag protokollieren möchten, wenn Sie den Anruf beenden.</span><span class="sxs-lookup"><span data-stu-id="9beef-176">You can use Remote Assist together with Dynamics 365 for Field Service if you want to automatically log call information to a Field Service work order when you end the call.</span></span> 

<span data-ttu-id="9beef-177">Wenn Sie sich zum ersten Mal bei der Mobile-App Remote Assist anmelden, werden Sie aufgefordert, Remote Assist mit Dynamics 365 for Field Service zu verknüpfen.</span><span class="sxs-lookup"><span data-stu-id="9beef-177">When you sign in to the Remote Assist mobile app for the first time, you’re prompted to link Remote Assist to Dynamics 365 for Field Service.</span></span> <span data-ttu-id="9beef-178">Sie können die Apps über „Einstellungen“ verknüpfen, wenn Sie sie nicht bei der ersten Anmeldung verknüpfen wollten.</span><span class="sxs-lookup"><span data-stu-id="9beef-178">You can link the apps through Settings if you chose not to link them at first sign-in.</span></span>

### <a name="link-the-remote-assist-mobile-app-to-dynamics-365-for-field-service"></a><span data-ttu-id="9beef-179">Mobile-App Remote Assist mit Dynamics 365 for Field Service verknüpfen</span><span class="sxs-lookup"><span data-stu-id="9beef-179">Link the Remote Assist mobile app to Dynamics 365 for Field Service</span></span>

1.  <span data-ttu-id="9beef-180">Wählen Sie die Schaltfläche **Hauptmenü** ![Schaltfläche „Hauptmenü“](media/main-menu-button.PNG "Schaltfläche „Hauptmenü“").</span><span class="sxs-lookup"><span data-stu-id="9beef-180">Select the **Main menu** ![Main menu button](media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="9beef-181">Wählen Sie die Schaltfläche **Registrieren** aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-181">Select the **Settings** button.</span></span>  

3.  <span data-ttu-id="9beef-182">Bewegen Sie den Schieberegler im Dialogfeld **Einstellungen** auf „Ein“.</span><span class="sxs-lookup"><span data-stu-id="9beef-182">In the **Settings** dialog box, move the slider to on.</span></span>

    <span data-ttu-id="9beef-183">![Bildschirm „Einstellungen“](media/settings.PNG "Bildschirm „Einstellungen“")</span><span class="sxs-lookup"><span data-stu-id="9beef-183">![Settings screen](media/settings.PNG "Settings screen")</span></span>
  
### <a name="save-call-data-to-a-field-service-work-order"></a><span data-ttu-id="9beef-184">Anrufdaten in einem Field Service-Arbeitsauftrag speichern</span><span class="sxs-lookup"><span data-stu-id="9beef-184">Save call data to a Field Service work order</span></span>

1.  <span data-ttu-id="9beef-185">Wenn Sie den Anruf beenden, wird Folgendes angezeigt:</span><span class="sxs-lookup"><span data-stu-id="9beef-185">When you end the call, the following dialog box will appear:</span></span>

    <span data-ttu-id="9beef-186">![Bildschirm „In Arbeitsauftrag buchen“](media/post-to-work-order.PNG "Bildschirm „In Arbeitsauftrag buchen“")</span><span class="sxs-lookup"><span data-stu-id="9beef-186">![Post to Work Order screen](media/post-to-work-order.PNG "Post to Work Order screen")</span></span>
  
2.  <span data-ttu-id="9beef-187">Wählen Sie **Buchen** aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-187">Select **Post**.</span></span>


3.  <span data-ttu-id="9beef-188">Wählen Sie im Bildschirm **Eine Buchung auswählen** die entsprechende Buchung für die Einfügung der Anrufdaten.</span><span class="sxs-lookup"><span data-stu-id="9beef-188">In the **Select a Booking** screen, select the appropriate booking to post the call data to.</span></span>

    <span data-ttu-id="9beef-189">![Bildschirm „Buchung auswählen“](media/bookings-today.PNG "Bildschirm „Buchung auswählen“")</span><span class="sxs-lookup"><span data-stu-id="9beef-189">![Select a Booking screen](media/bookings-today.PNG "Select a Booking screen")</span></span>
  
    > [!NOTE]
    > <span data-ttu-id="9beef-190">Wenn Sie die gesuchte Buchung nicht sehen, kann dies daran liegen, dass Sie Zugriff auf mehrere Instanzen (Organisationen) haben.</span><span class="sxs-lookup"><span data-stu-id="9beef-190">If you don’t see the booking you’re looking for, it might be because you have access to multiple instances (organizations).</span></span> <span data-ttu-id="9beef-191">Wählen Sie zum Wechseln zu einer anderen Instanz auf das Auslassungszeichen (...) und wählen Sie dann die gewünschte Instanz aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-191">To switch to a different instance, select the ellipsis button (...), and then select the instance you want.</span></span><br><span data-ttu-id="9beef-192">![Instanz auswählen](media/select-instance.PNG "Instanz auswählen")</span><span class="sxs-lookup"><span data-stu-id="9beef-192">![Select instance](media/select-instance.PNG "Select instance")</span></span>
    
## <a name="sign-out-of-the-app"></a><span data-ttu-id="9beef-193">Von der App abmelden</span><span class="sxs-lookup"><span data-stu-id="9beef-193">Sign out of the app</span></span>

1.  <span data-ttu-id="9beef-194">Wählen Sie die Schaltfläche **Hauptmenü** ![Schaltfläche „Hauptmenü“](media/main-menu-button.PNG "Schaltfläche „Hauptmenü“").</span><span class="sxs-lookup"><span data-stu-id="9beef-194">Select the **Main menu** ![Main menu button](media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="9beef-195">Wählen Sie **Anmelden** aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-195">Select **Sign Out**.</span></span>

## <a name="get-help"></a><span data-ttu-id="9beef-196">Hilfe</span><span class="sxs-lookup"><span data-stu-id="9beef-196">Get Help</span></span>

1.  <span data-ttu-id="9beef-197">Wählen Sie die Schaltfläche **Hauptmenü** ![Schaltfläche „Hauptmenü“](media/main-menu-button.PNG "Schaltfläche „Hauptmenü“").</span><span class="sxs-lookup"><span data-stu-id="9beef-197">Select the **Main menu** ![Main menu button](media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="9beef-198">Wählen Sie **Hilfe** aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-198">Select **Help**.</span></span>

## <a name="get-support-or-provide-feedback"></a><span data-ttu-id="9beef-199">Support erhalten oder Feedback geben</span><span class="sxs-lookup"><span data-stu-id="9beef-199">Get support or provide feedback</span></span>

<span data-ttu-id="9beef-200">Wenn Sie Direktzugriff auf das Produktteamforum erhalten und Feedback auf der Vorschau der Mobile-App geben möchten:</span><span class="sxs-lookup"><span data-stu-id="9beef-200">If you’d like to get direct access to the product team forum and provide feedback on the mobile app preview:</span></span>

1.  <span data-ttu-id="9beef-201">Melden Sie sich für das Public Preview Insiders Program der Dynamics 365 Remote Assist Mobile-App unter https://experience.dynamics.com an.</span><span class="sxs-lookup"><span data-stu-id="9beef-201">Sign up for the Dynamics 365 Remote Assist Mobile Public Preview Insiders Program at https://experience.dynamics.com.</span></span> 


2.  <span data-ttu-id="9beef-202">Wählen Sie das Feld **Insider-Programm** aus, das die Anwendung Insider-Programm öffnet.</span><span class="sxs-lookup"><span data-stu-id="9beef-202">Select the **Insider Program** box, which will lead you to the Insider Program application.</span></span>

    <span data-ttu-id="9beef-203">![Schaltfläche „Insider-Programm“](media/insiders-program.PNG "Schaltfläche „Insider-Programm“")</span><span class="sxs-lookup"><span data-stu-id="9beef-203">![Insider Program button](media/insiders-program.PNG "Insider Program button")</span></span>
 
<span data-ttu-id="9beef-204">Mit der folgenden Prozedur können Sie Feedback direkt aus der App geben:</span><span class="sxs-lookup"><span data-stu-id="9beef-204">You can also provide feedback directly from the app by using the following procedure:</span></span>

1.  <span data-ttu-id="9beef-205">Wählen Sie die Schaltfläche **Hauptmenü** ![Schaltfläche „Hauptmenü“](media/main-menu-button.PNG "Schaltfläche „Hauptmenü“").</span><span class="sxs-lookup"><span data-stu-id="9beef-205">Select the **Main menu** ![Main menu button](media/main-menu-button.PNG "Main menu button") button.</span></span>

2.  <span data-ttu-id="9beef-206">Wählen Sie **Feedback** aus.</span><span class="sxs-lookup"><span data-stu-id="9beef-206">Select **Feedback**.</span></span>
