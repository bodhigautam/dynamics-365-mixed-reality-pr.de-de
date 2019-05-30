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
# <a name="dynamics-365-remote-assist-mobile-user-guide-in-preview"></a>Benutzerhandbuch für die Dynamics 365 Remote Assist Mobile-App (Vorschau)

[Dieses Thema ist Teil der Dokumentation zur Vorabversion und kann geändert werden.]

Die Mobile-App Microsoft Dynamics 365 Remote Assist erweitert die Funktionen von Dynamics 365 Remote Assist für die Arbeit mit Android ARCore-fähigen Telefonen (zusätzlich zu Microsoft HoloLens). Techniker können sich mit ihren Telefonen mit einem Experten von Microsoft Teams verbinden und mit ihm kooperieren. Mithilfe von Videoanruf- und Mixed Reality-Anmerkungen können sie das, was sie sehen, mit dem Experten teilen, um Probleme gemeinsam schneller zu lösen. 

## <a name="what-youll-need"></a>Was Sie benötigen

Für die Mobile-App Remote Assist benötigen Sie:

- An Android ARCore-fähiges Smartphone (Tablets werden derzeit nicht unterstützt) mit ARCore installiert. [Hier erhalten Sie die vollständige Liste unterstützter Geräte:](https://developers.google.com/ar/discover/supported-devices) 

- Ein Google Play-Konto.

- Die Mobile-App Remote Assist.

- Ein Microsoft Teams-Konto (kostenlos verfügbar).

- Ein Microsoft Teams-Desktopclient, auf dem Windows 10 ausgeführt wird (für den Remote-Experten, der den Anruf erhält).

- Eine Internetverbindung. Die besten Ergebnisse erzielen Sie mit mindestens 1,5 MB Bandbreite.

Wenn Sie Remote Assist mit Dynamics 365 for Field Service verwenden möchten, damit Sie automatisch Anrufdaten in einem Field Service-Arbeitsauftrag erfassen können, benötigen Sie auch eine der folgenden Komponenten oder beide:

- Dynamics 365 for Field Service Webanwendung

- Mobile-App Dynamics 365 for Field Service 

## <a name="get-started"></a>Erste Schritte

### <a name="step-1-sign-up-for-a-microsoft-teams-account-free"></a>Schritt 1: Melden Sie sich bei einem Microsoft Teams-Konto an (kostenlos)

Ein Microsoft Teams-Konto ist erforderlich, um die Remote Assist Mobile-App verwenden zu können. Wenn Sie nicht bereits ein Teams-Konto haben, können Sie [ein Teams-Konto kostenlos erstellen](https://businessstore.microsoft.com/en-us/create-account/signup?products=CFQ7TTC0K8P5:0001&lm=deeplink&lmsrc=freePageWeb&cmpid=FreemiumSignUpHeader). 

### <a name="step-2-download-the-app"></a>Schritt 2: Laden Sie die App herunter

1.  Rufen Sie den Google Play Store auf: https://play.google.com/store/apps/details?id=com.microsoft.ramobile.

2.  Wählen Sie **Download** aus. 
 
### <a name="step-3-sign-in-to-the-app-for-the-first-time"></a>Schritt 3: Melden Sie sich zum ersten Mal bei der App an

1.  Wenn Sie die App heruntergeladen haben, öffnen Sie sie auf Ihrem Android-Smartphone. 

2.  Melden Sie sich mit Ihrem Microsoft Teams-Konto an.

    ![Anmeldebildschirm](media/sign-in.png "Anmeldebildschirm")
  
    > [!TIP]
    > Die Anmeldeadresse hat die Form: Benutzername@Unternehmen.
    
3.  Wählen Sie in dem daraufhin angezeigten Dialogfeld **Funktion aktivieren** aus, um Remote Assist mit Dynamics 365 for Field Service zu verknüpfen, oder wählen Sie **Überspringen** aus, wenn Sie im Moment nicht auf die Apps klicken möchten. Sie können sie später über **Einstellungen** verknüpfen. Wenn Sie mehr zur gemeinsamen Funktion der Apps erfahren möchten, wählen Sie **Weitere Informationen** aus.

    ![Field Service-Bildschirm](media/field-service.PNG "Field Service-Bildschirm")
  
## <a name="make-a-call"></a>Telefonanruf vornehmen
Nach der Anmeldung sehen Sie die Seite **Kontakte**, die Hauptseite der Mobile-App Remote Assist. Auf der Seite **Kontakte** sind die Kontakte nach der Aktualität der Anrufe angeordnet.

![Kontaktbildschirm](media/contacts.PNG "Kontaktbildschirm")


So nehmen Sie einen Telefonanruf vor:

1.  Wählen Sie ![Schaltfläche „Suchen“](media/search-icon.PNG "Schaltfläche „Suchen“") aus, geben Sie den Namen des zu suchenden Kontakts ein und wählen Sie den Kontakt dann in der Ergebnisliste aus.
       
    ![Nach einem Kontakt suchen](media/search-contact.PNG "Nach einem Kontakt suchen")
    
2.  Wählen Sie auf der Kontaktkarte **Anruf starten** aus.

    ![Bildschirm „Anruf starten“](media/launch-call.PNG "Bildschirm „Anruf starten“")
  
    Schalten Sie den Anruf mithilfe der Schaltflächen in der Leiste am unteren Bildschirmrand stumm, unterbrechen Sie den Videofeed, schalten Sie das Lautsprechermikrofon ein oder beenden Sie den Anruf.
    
    ![Anrufkontrollen](media/call-controls.PNG "Anrufkontrollen")
  
 
## <a name="add-annotations"></a>Anmerkungen hinzufügen
Sie können Anmerkungen in Ihren Bildschirm einfügen, um sie an einen Experten im Anruf weiterzugeben. Um Anmerkungen erstellen zu können, muss Ihr Smartphone mindestens eine Ebene (vertikal oder horizontal) in Ihrem Arbeitsbereich erkennen können. Scannen Sie dazu Ihren Arbeitsbereich mit dem Smartphone. Wenn eine Ebene erkannt wurde, sehen Sie eine Bestätigungsvisualisierung und die Anmerkungssymbolleiste wird am oberen Bildschirmrand angezeigt:

![Anmerkungen hinzufügen](media/annotation-bar-full-screen.PNG "Anmerkungen hinzufügen")
  
> [!NOTE] 
> Wenn Sie Ihr Telefon sperren oder Remote Assist minimieren, werden die erkannten Ebenen automatisch erneut angezeigt, wenn Ihr Smartphone die Umgebung erkennt.

### <a name="add-an-annotation"></a>Eine Anmerkung hinzufügen
Sie können eine Anmerkung mithilfe der Schaltflächen auf der Anmerkungssymbolleiste hinzufügen:

![Anmerkungsleiste](media/annotation-bar.PNG "Anmerkungsleiste")
  
Wenn Sie beispielsweise einen Pfeil hinzufügen möchten, tippen Sie auf das Pfeil-Tool und streichen mit dem Finger zu der Stelle, an der sie den Pfeil platzieren möchten.

### <a name="minimize-or-restore-the-toolbar"></a>Minimieren oder stellen Sie die Symbolleiste wieder her

So minimieren Sie die Symbolleiste, wenn Sie einen größeren Bereich des Bildschirms sehen möchten:

- Wählen Sie den Pfeil rechts in der Symbolleiste aus. 

  ![Leiste minimieren](media/minimize-bar.PNG "Leiste minimieren")
 
So stellen Sie die ursprüngliche Größe der Symbolleiste wieder her:

- Wählen Sie die Schaltfläche **Stift** aus. 

  ![Schaltfläche „Stift“](media/pen-button.PNG "Schaltfläche „Stift“")

### <a name="make-the-experts-video-feed-bigger"></a>Experten-Videofeed vergrößern

Wenn Sie eines Experten anrufen, wird der Experten-Videofeed unten rechts auf Ihrem Smartphone angezeigt. Tippen Sie auf den Feed, um den Experten-Videofeed zu vergrößern. Tippen Sie erneut auf den Feed, um wieder die ursprüngliche Größe einzustellen.

![Experten-Videofeed](media/expert-annotating.PNG "Experten-Videofeed")
  
Wenn der Experte kommentiert, wird ein Benachrichtigungssymbol im Feed des Experten angezeigt.  

## <a name="switch-the-camera-view-from-portrait-to-landscape"></a>Kameraansicht Hochformat zu Querformat wechseln

Sie können die Ausrichtung der Kameraansicht während eines Anrufs von Hochformat zu Querformat wechseln, indem Sie die Ausrichtung Ihres Smartphones ändern. Querformat bietet ein breiteres Sichtfeld was die Benutzerfreundlichkeit für den Remote-Experten im Anruf verbessern kann.
   
## <a name="use-remote-assist-together-with-dynamics-365-for-field-service"></a>Use Remote Assist zusammen mit Dynamics 365 for Field Service verwenden

Sie können Remote Assist zusammen mit Dynamics 365 for Field Service verwenden, wenn Sie automatisch Anrufdaten für einen Field Service-Arbeitsauftrag protokollieren möchten, wenn Sie den Anruf beenden. 

Wenn Sie sich zum ersten Mal bei der Mobile-App Remote Assist anmelden, werden Sie aufgefordert, Remote Assist mit Dynamics 365 for Field Service zu verknüpfen. Sie können die Apps über „Einstellungen“ verknüpfen, wenn Sie sie nicht bei der ersten Anmeldung verknüpfen wollten.

### <a name="link-the-remote-assist-mobile-app-to-dynamics-365-for-field-service"></a>Mobile-App Remote Assist mit Dynamics 365 for Field Service verknüpfen

1.  Wählen Sie die Schaltfläche **Hauptmenü** ![Schaltfläche „Hauptmenü“](media/main-menu-button.PNG "Schaltfläche „Hauptmenü“").

2.  Wählen Sie die Schaltfläche **Registrieren** aus.  

3.  Bewegen Sie den Schieberegler im Dialogfeld **Einstellungen** auf „Ein“.

    ![Bildschirm „Einstellungen“](media/settings.PNG "Bildschirm „Einstellungen“")
  
### <a name="save-call-data-to-a-field-service-work-order"></a>Anrufdaten in einem Field Service-Arbeitsauftrag speichern

1.  Wenn Sie den Anruf beenden, wird Folgendes angezeigt:

    ![Bildschirm „In Arbeitsauftrag buchen“](media/post-to-work-order.PNG "Bildschirm „In Arbeitsauftrag buchen“")
  
2.  Wählen Sie **Buchen** aus.


3.  Wählen Sie im Bildschirm **Eine Buchung auswählen** die entsprechende Buchung für die Einfügung der Anrufdaten.

    ![Bildschirm „Buchung auswählen“](media/bookings-today.PNG "Bildschirm „Buchung auswählen“")
  
    > [!NOTE]
    > Wenn Sie die gesuchte Buchung nicht sehen, kann dies daran liegen, dass Sie Zugriff auf mehrere Instanzen (Organisationen) haben. Wählen Sie zum Wechseln zu einer anderen Instanz auf das Auslassungszeichen (...) und wählen Sie dann die gewünschte Instanz aus.<br>![Instanz auswählen](media/select-instance.PNG "Instanz auswählen")
    
## <a name="sign-out-of-the-app"></a>Von der App abmelden

1.  Wählen Sie die Schaltfläche **Hauptmenü** ![Schaltfläche „Hauptmenü“](media/main-menu-button.PNG "Schaltfläche „Hauptmenü“").

2.  Wählen Sie **Anmelden** aus.

## <a name="get-help"></a>Hilfe

1.  Wählen Sie die Schaltfläche **Hauptmenü** ![Schaltfläche „Hauptmenü“](media/main-menu-button.PNG "Schaltfläche „Hauptmenü“").

2.  Wählen Sie **Hilfe** aus.

## <a name="get-support-or-provide-feedback"></a>Support erhalten oder Feedback geben

Wenn Sie Direktzugriff auf das Produktteamforum erhalten und Feedback auf der Vorschau der Mobile-App geben möchten:

1.  Melden Sie sich für das Public Preview Insiders Program der Dynamics 365 Remote Assist Mobile-App unter https://experience.dynamics.com an. 


2.  Wählen Sie das Feld **Insider-Programm** aus, das die Anwendung Insider-Programm öffnet.

    ![Schaltfläche „Insider-Programm“](media/insiders-program.PNG "Schaltfläche „Insider-Programm“")
 
Mit der folgenden Prozedur können Sie Feedback direkt aus der App geben:

1.  Wählen Sie die Schaltfläche **Hauptmenü** ![Schaltfläche „Hauptmenü“](media/main-menu-button.PNG "Schaltfläche „Hauptmenü“").

2.  Wählen Sie **Feedback** aus.
