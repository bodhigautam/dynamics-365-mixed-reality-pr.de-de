---
author: bencorn
description: Dynamics 365 Remote Assist Benutzerhandbuch (für HoloLens)
ms.author: becorn
ms.date: 05/6/2019
ms.service: crm-online
ms.topic: article
title: Dynamics 365 Remote Assist Benutzerhandbuch (für HoloLens)
ms.reviewer: v-brycho
ms.openlocfilehash: ecaf11960fbdaa073353e6a3ca53638d82a38ae2
ms.sourcegitcommit: 8999bfecc2b117135aa9a1077044f678341c33ad
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 05/06/2019
ms.locfileid: "1575565"
---
# <a name="dynamics-365-remote-assist-user-guide-for-hololens"></a>Dynamics 365 Remote Assist Benutzerhandbuch (für HoloLens)

Verwenden Sie [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] zum Herstellen einer Verbindung sowie zur Zusammenarbeit mit freihändigen Videoanrufen, Mixed Reality-Anmerkungen und Teilen von Dateien (Bild und PDF). Verwenden Sie Ihr [!include[pn-hololens](../includes/pn-hololens.md)], um einen Experten anzurufen, der [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] verwendet, und teilen Sie, was Sie auf [!include[pn-hololens](../includes/pn-hololens.md)] sehen, um Probleme zu lösen und Aufgaben gemeinsam schneller zu erledigen.

Benötigen Sie weitere Hilfe? [Unter Remote Assist Häufig gestellte Fragen](faq.md) finden Sie Antworten auf häufig gestellte Fragen.

[Sehen Sie Anleitungsvideos](https://go.microsoft.com/fwlink/p/?linkid=2021485) über [!include[pn-remote-assist](../includes/pn-remote-assist.md)].

## <a name="what-youll-need"></a>Was Sie benötigen

-   Ein Abonnement für Remote Assist. Microsoft Teams ist in dem Remote Assist-Abonnement für Personen enthalten, die eine Remote Assist-Lizenz auf HoloLens verwenden. Eine Microsoft Teams-Lizenz ist auch für Personen (Experten) erforderlich, die mit einem Benutzer von Remote Assist auf HoloLens kommunizieren. Teams kann für diese Benutzer als [kostenloser Download unter](https://teams.microsoft.com/downloads) zur Verfügung stehen. Wenn Sie ein Administrator für Ihre Organisation sind, [lernen Sie, wie man den Remote Assist ausprobiert, kauft oder einsetzt](../licensing/buy-and-deploy.md). 

    > [!TIP] 
    > Sie können Dynamics 365 Remote Assist für bis zu 90 Tage kostenlos ausprobieren. [Erfahren Sie mehr über die kostenlose 90-Tage-Testversion von Dynamics 365 Remote Assist](try-remote-assist-free.md).

-   Ein [HoloLens auf dem das Windows 10 April 2018 Update](https://support.microsoft.com/en-us/help/12643) ausgeführt wird.

-   Um einen Videoanruf tätigen zu können, muss der Kontakt die neueste Version von [Microsoft Teams](https://products.office.com/en-us/microsoft-teams/group-chat-software) auf einem PC mit [!include[pn-ms-windows-short](../includes/pn-ms-windows-short.md)] 10 oder einem mobilen Gerät mit der Microsoft Teams Mobile-App verwenden. [Erfahren Sie mehr über die Verwendung von Teams mit Remote Assist.](use-microsoft-teams-with-remote-assist.md)

-   Um sich aus [!include[pn-remote-assist](../includes/pn-remote-assist.md)] mit [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] zu verbinden, benötigen Sie eine [Dynamics 365-Lizenz](https://dynamics.microsoft.com/en-us/field-service/overview/?&OCID=AID720979_SEM_yeaT05hp&lnkd=Bing_D365_Brand).

-   Eine Internetverbindung. Die besten Ergebnisse erzielen Sie mit mindestens 1,5 MB Bandbreite.

Sie müssen sich auf [!include[pn-hololens](../includes/pn-hololens.md)] einarbeiten? [Erhalten Sie Hilfe unter](https://support.microsoft.com/products/hololens).

## <a name="install-the-remote-assist-app"></a>Installieren der Remote Assist-App

Wie Sie [!include[pn-remote-assist](../includes/pn-remote-assist.md)] installieren, hängt davon ab, wie Ihr Administrator die App zur Verfügung stellt. So kann Ihr Administrator Sie [die App aus dem Microsoft Store for Consumers](https://www.microsoft.com/store/apps/9P77QGW10K9M), aus dem privaten Store Ihrer Organisation, über einen E-Mail-Link oder eine andere Methode installieren lassen.

### <a name="install-the-application-through-the-microsoft-store-for-consumers"></a>Installieren der Anwendung über den Microsoft Store for Consumers

1.  Gehen Sie auf Ihrem [!include[pn-hololens](../includes/pn-hololens.md)] auf **Start** ![Start](media/d2a2ae5e90bdd0e0642abb5458af1016.png "Start") \> **[!include[cc-microsoft](../includes/cc-microsoft.md)] Store** ![[!include[cc-microsoft](../includes/cc-microsoft.md)] Store](media/2ac602b5a7855d312f3e7d924732acca.png "Microsoft Store") und suchen Sie anschließend nach „[!include[pn-remote-assist](../includes/pn-remote-assist.md)]”.

2.  Öffnen Sie auf Ihrem [!include[pn-hololens](../includes/pn-hololens.md)] **Start** ![Start](media/d2a2ae5e90bdd0e0642abb5458af1016.png "Start") \> **Alle Apps**. Wählen Sie **[!include[pn-remote-assist](../includes/pn-remote-assist.md)]**, und wählen Sie dies anschließend noch einmal, um die App zu starten. [!include[pn-remote-assist](../includes/pn-remote-assist.md)] ist eine immersive Anwendung mit einem [holografischen Ansicht](https://support.microsoft.com/en-us/help/12635). Sie ist somit die einzige App, die Sie während ihrer Nutzung sehen.

Wenn Ihr [!include[pn-hololens](../includes/pn-hololens.md)] das April 2018 Update ausführt und Sie mit einem [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)] ([!include[pn-azure](../includes/pn-azure.md)] AD)-Konto angemeldet sind, werden Sie automatisch bei [!include[pn-remote-assist](../includes/pn-remote-assist.md)] angemeldet. Falls nicht, verwenden Sie die holografische Tastatur, um sich mit einem Arbeits- oder Schulkonto anzumelden, das über ein Abonnement für [!include[pn-office-365](../includes/pn-office-365.md)] Premium oder Essentials verfügt.Sobald Sie angemeldet sind, sehen Sie Ihre letzten Kontakte.

## <a name="using-the-user-interface-or-voice-commands"></a>Verwenden der Benutzeroberfläche oder von Sprachbefehlen

Die Abläufe in diesem Benutzerhandbuch beschreiben, wie Sie Aufgaben über die Benutzeroberfläche oder mit Sprachbefehlen (wenn verfügbar) ausführen. Um Sprachbefehle zu verwenden, sagen Sie „[!include[pn-remote-assist](../includes/pn-remote-assist.md)]” und anschließend den Sprachbefehl. [Erfahren Sie mehr über Sprachbefehle.](#voice)

## <a name="make-and-receive-calls"></a>Anrufe tätigen und empfangen

Wie Sie einen Anruf tätigen, hängt davon ab, ob Sie einen Kontakt inner- oder außerhalb Ihres Unternehmens anrufen.

### <a name="make-a-call-to-a-contact-in-your-company"></a>Einen Kontakt innerhalb Ihres Unternehmens anrufen

-   Öffnen Sie die App, und [wählen Sie](https://support.microsoft.com/en-us/help/12644) einen Ihrer letzten Kontakte. Falls Sie den gewünschten Kontakt nicht sehen, wählen Sie **Suche** ![Suche](media/e3155cd796106ea0818d8f52c7dbfcbe.png "Suche"), und verwenden Sie anschließend die holografische Tastatur, um einen Namen oder eine E-Mail-Adresse einzugeben.

Wenn Ihr Kontakt den Anruf in [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] annimmt, kann er sehen, was Sie selbst in Ihrem Raum sehen – einschließlich Hologramme.

> [!NOTE]
> Dynamic Audio passt den Lautstärkepegel basierend auf den Umgebungsgeräuschen im Raum an, sodass Sie auch in einer lauten Umgebung etwas hören können.

### <a name="make-a-call-to-a-contact-outside-your-company"></a>Einen Kontakt außerhalb Ihres Unternehmens anrufen

Sie können einen Einzelanruf mit einem Teams-Benutzer eines anderen Unternehmens tätigen oder empfangen, wenn in Microsoft Teams der externe Zugang für beide Unternehmen aktiviert wurde. Wenn Sie der Administrator für Ihre Organisation sind, lesen Sie [Einrichtung firmenübergreifender Anrufe](cross-company-calling.md), um einen externen Zugang einzurichten.

> [!NOTE]
> Zu diesem Zeitpunkt können Sie mit Kontakten außerhalb Ihres Unternehmens keine Gruppenanrufe führen oder Dateien teilen. 

Um einen Kontakt außerhalb Ihres Unternehmens anzurufen:

- Öffnen Sie die App, wählen Sie **Suche**, und verwenden Sie anschließend die holografische Tastatur, um die vollständige E-Mail-Adresse des externen Benutzers einzugeben. Sie *müssen* die vollständige E-Mail-Adresse eingeben. Es werden Ihnen keine Suchergebnisse angezeigt, wenn Sie nur einen Namen oder einen Teil einer E-Mail-Adresse eingeben.

> [!NOTE] 
> Wenn Sie den gewünschten Kontakt nicht finden, kann es möglicherweise daran liegen, dass der externe Zugang in Microsoft Teams für Ihr oder das andere Unternehmen nicht aktiviert wurde. Wenden Sie sich an Ihren Administrator, um Hilfe zu erhalten. 

## <a name="make-group-calls"></a>Gruppenanrufe tätigen

Sie können in einem Gruppenanruf bis zu 50 Personen einbeziehen. Sie können auch zwischen Video-Feeds der Teilnehmer wechseln oder Teilnehmer bei Bedarf stummschalten.

### <a name="invite-additional-contacts-to-a-call"></a>Einladen zusätzlicher Kontakte zu einem Anruf

1. Wählen Sie in den Anrufsteuerelementen die Schaltfläche **Teilnehmer hinzufügen**.

   ![Animation der Auswahl „Teilnehmer hinzufügen”](media/GC_OpenParticipantsList.gif "Animation der Auswahl „Teilnehmer hinzufügen”")

   > [!TIP]
   > Wählen Sie erneut die Schaltfläche **Teilnehmer hinzufügen**, wenn Sie das Fenster schließen möchten. 

2. Wählen Sie einen Ihrer letzten Kontakte aus oder wählen Sie **Jemanden einladen** am Ende der Liste. Eine Auflistung Ihrer letzten Kontakte erscheint. Falls die gewünschte Person nicht auf der Liste steht, geben Sie einen Namen oder eine E-Mail-Adresse unter Verwendung der holografischen Tastatur ein, und wählen Sie anschließend einen Namen in den Suchergebnissen aus, um den Anruf zu beginnen. 

   ![Animation der Suche nach einem Anruf](media/GC_SearchCall.gif "Animation der Suche nach einem Anruf")

   > [!TIP]
   > [Erfahren Sie, wie Sie weitere Kontakte vom Microsoft Teams-Desktop hinzufügen](https://support.office.com/en-us/article/add-someone-to-a-call-in-teams-267fb0c9-275a-4047-8412-7b2654dc29c3). 

### <a name="switch-the-displayed-video-feed-in-a-group-call"></a>Wechseln des angezeigten Video-Feeds in einem Gruppenanruf 

1. Wählen Sie in den Anrufsteuerelementen die Schaltfläche **Teilnehmer hinzufügen**. 

2. Fahren Sie mit der Maus über den Teilnehmer, zu dessen Video-Feed Sie wechseln möchten, und wählen Sie diesen anschließend aus. Ist der Video-Feed des Teilnehmers aktiviert, wechselt das Video zu seinem Feed. 

   > [!TIP] 
   > Sie können Video-Feeds auch über die „Teilnehmer-Leiste” unterhalb des Video-Feeds wechseln. Fahren Sie mit der Maus über den Avatar, um den Namen des Teilnehmers anzuzeigen, und tippen Sie dann, um die Video-Feeds zu wechseln. 

### <a name="mute-a-participant-in-a-group-call"></a>Stummschalten eines Teilnehmers in einem Gruppenanruf 

> [!NOTE]
> Sie können einen Teilnehmer in einem Einzelanruf stummschalten.

1. Wählen Sie in den Anrufsteuerelementen die Schaltfläche **Teilnehmer hinzufügen**. 

2. Tippen Sie auf das Stummschaltsymbol des Teilnehmers, den Sie stummschalten möchten. 

> [!NOTE]
> Wenn Sie einen Teilnehmer stummschalten, können Sie die Stummschaltung nicht wieder aufheben. Sie müssen die Stummschaltung selbst über Teams aufheben. 


## <a name="record-a-call"></a>Einen Anruf aufzeichnen

Sie können einen Anruf in einer Datei aufzeichnen, um diesen später zu prüfen. Dies ist eine gute Möglichkeit, einen Anruf zu Schulungs- oder Aufzeichnungszwecken zu erfassen.

Sie können einen Anruf auf zwei Arten aufzeichnen:

- Unter Verwendung der in Windows 10-PCs integrierten Spielleiste.

- Unter Verwendung der Aufzeichnungsfunktion in Teams.

### <a name="record-a-call-using-the-game-bar-in-windows-10-pcs"></a>Einen Anruf aufzeichnen unter Verwendung der in Windows 10-PCs integrierten Spielleiste

1. Auf einem Desktop-PC mit Windows 10 können Sie mit Microsoft Teams einem Anruf beitreten.

2. Drücken Sie die **Windows-Logo-Taste ![Windows-Logo-Taste)](media/windows-logo-key.png "Windows-Logo-Taste") + G**, um die Spielleiste zu öffnen.

   ![Spielleiste)](media/game-bar.png "Spielleiste")

3. Wählen Sie die Schaltfläche **Aufzeichnung beginnen** (oder drücken Sie die **Windows-Logo-Taste ![Windows-Logo-Taste)](media/windows-logo-key.png "Windows-Logo-Taste") + ALT + R**).

   Es erscheint ein kleines Aufnahme-Menü, das anzeigt, dass die Aufzeichnung läuft.
   
   ![Aufzeichnung](media/recording.PNG "Aufzeichnung")
   
4. Zum Beenden der Aufzeichnung, wählen Sie die Schaltfläche **Aufzeichnung beenden** aus.

   Das Aufzeichnungsvideo erscheint in Ihrem Video-/Aufzeichnungsordner.
   
[Erfahren Sie mehr über die Spielleiste.](https://support.xbox.com/xbox-on-windows/social/record-game-clips-game-bar-windows-10)

### <a name="record-a-call-from-teams"></a>Einen Anruf über Teams aufzeichnen

Microsoft Teams unterstützt [cloudbasierte Anrufaufzeichnungen von Gruppenanrufen](https://support.office.com/en-us/article/record-a-meeting-in-teams-34dfbe7f-b07d-4a27-b4c6-de62f1348c24). Aufzeichnung werden in Microsoft Stream gespeichert und geteilt.

1.  Tätigen Sie den Gruppenanruf oder treten Sie diesem bei.

2.  Zum Beginnen der Aufzeichnung wählen Sie **Weitere Optionen** ( ... ) > **Aufzeichnung beginnen**.

    ![Schaltfläche „Aufzeichnung beginnen”](media/start-recording.PNG "Schaltfläche „Aufzeichnung beginnen”")
 
3.  Zum Beenden der Aufzeichnung, wählen Sie **Weitere Optionen** ( ... ) > **Aufzeichnung beenden**.

    ![Schaltfläche „Aufzeichnung beenden”](media/stop-recording.PNG "Schaltfläche „Aufzeichnung beenden”") 
 
    Die Aufzeichnung wird bearbeitet (und kann einige Zeit in Anspruch nehmen) und in Microsoft Stream gespeichert. Derjenige, der die Aufzeichnung gestartet hat, erhält eine E-Mail von Microsoft Stream, sobald die Aufzeichnung zur Verfügung steht. Dies erscheint ebenfalls im Gruppenchat.

## <a name="receive-a-call-from-a-contact-using-microsoft-teams"></a>Empfangen eines Anrufs von einem Kontakt über Microsoft Teams empfangen

-   Wählen Sie **Video** ![Video](media/bae39e2bdb1eafec5c36c76ffa640355.png "Video") (oder sagen Sie „Video”), um den Anruf als Video-Anruf anzunehmen, oder wählen Sie **Audio** ![Audio](media/972493ccc469c4ca41c04f96fabf6ba5.png "Audio") (oder sagen Sie „Audio”), um ihn als reinen Sprachanruf anzunehmen. Wählen Sie **Ignorieren** (oder sagen Sie „Ignorieren”), um den Anruf abzulehnen.

> [!NOTE]
> Um Anrufe zu erhalten, während Sie andere Apps auf [!include[pn-hololens](../includes/pn-hololens.md)] verwenden, öffnen Sie die [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-App. Verwenden Sie die [Öffnen-Geste](https://support.microsoft.com/en-us/help/12644/hololens-use-gestures), um [!include[pn-remote-assist](../includes/pn-remote-assist.md)] zu verlassen. Fahren Sie fort mit der Verwendung anderer Apps. Sie erhalten eine Mitteilung von [!include[pn-cortana](../includes/pn-cortana.md)], wenn ein [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Anruf eintrifft. Sie können diesen dann über Ihre Stimme annehmen oder ablehnen.

## <a name="position-the-call-window"></a>Positionieren des Anruf-Fensters

Sie können Ihren Video-Feed in Ihrem Raum anheften, oder er kann Ihnen folgen.

Anheften Ihres Video-Feeds:

-   Visieren Sie die Stelle zur Positionierung des Fensters an, und wählen Sie anschließend **Anheften** ![Anheften](media/d213f48b98dc5b8e41318aaa3782c395.png "Anheften") (oder sagen Sie „Anheften”). Damit es Ihnen wieder folgt, wählen Sie **Trennen** ![Trennen](media/1f4f3c48b466bfaa7a222cd4f1158c9c.png "Trennen") (oder sagen Sie „Trennen”).

## <a name="text-chat"></a>Text-Chat

Sie können mit dem anderen Benutzer während des Anrufs einen Text-Chat führen.Das Chat-Fenster zeigt nur die während des Anrufs versandten Textnachrichten an.

Zum Öffnen des Chat-Fensters und zur Eingabe einer Nachricht:

1.  Wählen Sie „Anzeigen” ![Anzeigen](media/chaticon3.png "Anzeigen") (oder sagen Sie „Anzeigen”).

2.  Wählen Sie das Textvorschaufenster unten im Chat-Fenster aus.Dadurch wird die holografische Tastatur angezeigt.

3.  Führen Sie einen der folgenden Schritte aus:

    -   Wählen Sie die Zeichen auf der holografischen Tastatur.

    -   Wählen Sie **Mikrofon** ![Mikrofon](media/microphone3.png "Mikrofon"), und diktieren Sie anschließend Ihre Nachricht. [!include[pn-hololens](../includes/pn-hololens.md)] konvertiert die Nachricht in Text.

    -   Verbinden Sie eine Bluetooth-Tastatur direkt mit [!include[pn-hololens](../includes/pn-hololens.md)], und geben Sie Ihre Nachricht ein.

1.  Wählen Sie **Senden**.

Um frühere Nachrichten im Chat-Fensters zu lesen:

-   Tippen und ziehen Sie das Chat-Fenster.

> [!NOTE]
> Wird eine Nachricht von einem anderen Benutzer versandt, während das Chat-Fenster geschlossen ist, erhalten Sie eine Benachrichtigung.

## <a name="screen-sharing-with-an-expert-on-microsoft-teams"></a>Bildschirmfreigabe mit einem Experten auf Microsoft Teams

Wenn Sie mit einem Experten in einem Anruf arbeiten, kann der Experte sein Desktop- oder Anwendungsfenster mit Ihnen teilen, um Sie während des Anrufs zu unterstützen. Wenn der Experte seinen Desktop oder seine laufende Anwendung auf diese Weise teilt, ändert sich der Video-Feed des Experten in eine einheitliche Farbe. Sie können weiterhin alle Werkzeuge der Symbolleiste nutzen, auch wenn Ihr Video-Feed nicht mehr angezeigt wird.

Um das gemeinsame Fenster zu verschieben, zu vergrößern oder zu schließen, verwenden Sie die Steuerelemente oben rechts im gemeinsamen Fenster.

![Gemeinsame Desktop-Steuerelemente](media/screen-sharing-controls.jpg "Gemeinsame Desktop-Steuerelemente")

## <a name="collaborate-and-annotate"></a>Zusammenarbeiten und anmerken

Sobald Sie mit einem Videoanruf verbunden sind, sieht Ihr Kontakt alles, was Sie in Ihrem Raum sehen – einschließlich Ihrer Hologramme.

Verwenden Sie [HoloLens-Gesten](https://support.microsoft.com/en-us/help/12644) zum Zeichnen, Platzieren von Pfeilen und um Dateien zu Ihrem Raum hinzuzufügen. Ihr Kontakt sieht Ihre Ergänzungen und kann eigenen Anmerkungen machen.

### <a name="add-an-arrow"></a>Hinzufügen eines Pfeils

1.  Wählen Sie während eines Videoanrufs das **Pfeil**-Werkzeug aus (oder sagen Sie „Pfeil”).

2.  Visieren Sie die Stelle an, an der Sie den Pfeil hinzufügen möchten. Sie sehen eine Silhouette des Pfeils, die anzeigt, wo er platziert wird. Beachten Sie beispielsweise den blassen Pfeil im folgenden Screenshot:

    ![Geistpfeil](media/ghost-arrow-before.PNG "Geistpfeil")

3.  Tippen Sie zum Platzieren des Pfeils.

    ![Pfeil platziert](media/ghost-arrow-after.PNG "Pfeil platziert")

> [!NOTE]
> Wenn Sie die Richtung, in die der Pfeil zeigt, bestimmen möchten, tippen und halten Sie und rotieren Sie anschließend Ihre Hand zur Positionierung des Pfeils.

### <a name="draw-in-your-space"></a>In Ihrem Raum zeichnen

1.  Wählen Sie während eines Videoanrufs das **Tinten**-Werkzeug aus (oder sagen Sie „Tinte”).

2.  Visieren Sie die Stelle an, an der Sie zeichnen möchten. Tippen und halten Sie zum Zeichnen.

3.  Um eine Zeichnung zu beenden, heben Sie den einfach den Finger.

### <a name="change-arrow-or-ink-color"></a>Ändern eines Pfeils oder einer Tintenfarbe

-   Wählen Sie **Farben** (oder sagen Sie „Farben wählen”) und wählen Sie nun die gewünschte Farbe aus.

### <a name="add-an-image-or-pdf-file"></a>Hinzufügen eines Bildes oder einer PDF-Datei

Importieren Sie ein Bild oder eine PDF-Datei aus [!include[pn-onedrive-for-business](../includes/pn-onedrive-for-business.md)] und platzieren Sie es in Ihrem Raum. Fügen Sie beispielsweise ein Diagrammbild hinzu, um den Anruf zu unterstützen. Die von Ihnen angerufenen Personen können das Bild oder die PDF-Datei während des Anrufs in der [!include[pn-teams](../includes/pn-teams.md)]-App sehen.

Hinzufügen einer Datei:

1.  Wählen Sie während eines Videoanrufs **[!include[pn-onedrive](../includes/pn-onedrive.md)]** ![OneDrive](media/12b28856b051be23e665c896cd21b7d2.png "OneDrive") (oder sagen Sie „OneDrive”).

2.  Suchen und wählen Sie die Datei aus, die Sie hinzufügen möchten.

Bewegen eines Bildes:

1.  Visieren Sie es an und wählen Sie **Bewegen** (oder sagen Sie „Bewegen”).

2.  Tippen und halten Sie das Bild. Bewegen Sie nun Ihre Hand, um es anders zu positionieren.

Ändern der Größe eines Bildes:

1.  Visieren Sie es an und wählen Sie **Skalieren** (oder sagen Sie „Skalieren”).

2.  Tippen und halten Sie eine Ecke des Bildes. Bewegen Sie nun Ihre Hand, um es größer oder kleiner zu machen.

In einer PDF-Datei navigieren:

| **Ziel**                        | **Vorgehensweise**                                                                                       |
|-------------------------------|---------------------------------------------------------------------------------------------------|
| Gehen Sie die Seiten nacheinander durch | Verwenden die Pfeiltasten                                                                                |
| Springen zu einer bestimmten Seite       | Wählen die Seitenzahl aus, um den holografischen Ziffernblock anzuzeigen, und wählen anschließend die gewünschte Seite aus. |

### <a name="take-a-snapshot-of-your-annotations"></a>Machen einen Schnappschuss Ihrer Anmerkungen

Während eines Anrufs können Sie einen Schnappschuss Ihrer Mixed Reality-Anmerkungen machen, um diese für später zu speichern.

Um einen Schnappschuss zu machen:

-   Wählen Sie **Kamera** ![Kamera](media/cameraicon3.png "Kamera") (oder sagen Sie „Kamera”). Tippen Sie nun (oder sagen Sie „Fangen”), um das Foto zu machen.

>   Das Foto wird in Ihrem [!include[pn-hololens](../includes/pn-hololens.md)]-Kameraalbum gespeichert.

## <a name="make-changes"></a>Änderungen vornehmen

Um alle Pfeile und Zeichnungen, die Sie während eines Video-Anrufs hinzugefügt haben, zu löschen:

-   Wählen Sie **Alle löschen** oben im Anruf-Fenster (oder sagen Sie „Alle löschen”).

Um Ihre letzte Aktion rückgängig zu machen, einschließlich **Alle löschen**:

-   Wählen Sie **Rückgängig** oben im Anruf-Fenster (oder sagen Sie „Rückgängig”).

## Verwenden Sie Sprachbefehle und visieren Sie <a name="voice"></a>an.

In vielen Fällen können Sie Sprachbefehle und statt Gesten Anvisieren verwenden. Einige Sprachbefehle sind kontextabhängig, sodass sie nur in bestimmten Bereichen der Benutzeroberfläche funktionieren.

> [!IMPORTANT]
> Um Sprachbefehle zu verwenden, sagen Sie „[!include[pn-remote-assist](../includes/pn-remote-assist.md)]” und anschließend einen der Sprachbefehl aus der folgenden Tabelle. Sagen Sie beispielsweise „Remote Assist, Bewegen”, um in den Bewegungsmodus für eine Tafel (Fenster) zu gelangen. Sie können auch eine Schaltfläche anvisieren und „Remote Assist, Auswählen” sagen, um diese Schaltfläche auszuwählen.

| **Sprachbefehl**            | **Beschreibung**                                                                      |
|------------------------------|--------------------------------------------------------------------------------------|
| **Allgemeines**                  |                                                                                      |
| Abmelden                     | Abmelden von [!include[pn-remote-assist](../includes/pn-remote-assist.md)].           |
| Hoch                           | Hochgehen.                                                                               |
| Vorherige                     | Zur vorherigen Seite gehen.                                                                 |
| Nächste                         | Zum nächsten Menü gehen.                                                                     |
| Zurück                         | Zum vorherigen Menü gehen.                                                                 |
| Rückgängig                         | Die vorherige Aktion rückgängig machen.                                                            |
| **Anheften und Trennen eines Video-Feeds** |                                                                                      |
| Anheften                          | Heften Sie den Video-Feed in Ihrem Raum an, damit er Ihnen nicht folgen kann.                    |
| Trennen                        | Trennen Sie den Video-Feed von Ihrem Raum, damit er Ihnen folgen kann.                         |
| **Anruf-Verwaltung**          |                                                                                      |
| Anruf                         | Einen Kontakt anrufen.                                                                      |
| Auflegen                      | Den Anruf beenden.                                                                        |
| Audio                        | Einen eingehenden Anruf nur mit Audio annehmen.                                             |
| Video                        | Einen eingehenden Anruf mit Video annehmen.                                                  |
| Ignorieren                       | Einen eingehenden Anruf ablehnen.                                                            |
| Video starten                  | Video für einen Anruf einschalten.                                                        |
| Video beenden                   | Video während eines Anrufs ausschalten.                                                        |
| Stummschalten                         | Stummschalten des Anrufs.                                                                 |
| Stummschaltung aufheben                       | Stummschaltung des Anrufs aufheben.                                                               |
| Suche                       | Im Fenster „Kontakte” verwendet, öffnet sich das Suchfenster, um einen Kontakt zu suchen. |
| Nächste                         | Im Fenster „Kontakte” verwendet, wird der nächste Kontakt in der Liste angezeigt.              |
| Vorherige                     | Im Fenster „Kontakte” verwendet, wird der vorherige Kontakt in der Liste angezeigt.          |
| Anzeigen                         | Anzeigen des Text-Chat-Fensters.                                                           |
| Ausblenden                         | Ausblenden des Text-Chat-Fensters.                                                           |
| **Anmerkungen**              |                                                                                      |
| Pfeil                        | Wählen Sie das **Pfeil**-Werkzeug aus, um einen Pfeil in Ihrem Raum zu platzieren.                           |
| Tinte                          | Wählen Sie das **Tinten**-Werkzeug aus, um auf den Mauern und Oberflächen Ihres Raumes zu zeichnen.             |
| Bewegen                         | Wählen Sie das **Bewegen**-Werkzeug aus, um ein Objekt zu bewegen.                                          |
| Skalieren                        | Wählen Sie das **Skalieren**-Werkzeug aus, um die Größe eines Objekts zu ändern.                                       |
| Kamera                       | Wählen Sie das **Kamera**-Werkzeug aus, um ein Foto Ihres Raums zu machen.                          |
| Fangen                         | Machen Sie ein Foto, wenn das Kamera-Werkzeug geöffnet ist.                                         |
| Farben                       | Eine Farbe auswählen.                                                                        |
| Blau                         | Die Farbe Blau auswählen.                                                                 |
| Grau                         | Die Farbe Grau auswählen.                                                                 |
| Grün                        | Die Farbe Grün auswählen.                                                                |
| Rot                          | Die Farbe Rot auswählen.                                                                  |
| Gelb                       | Die Farbe Gelb auswählen.                                                               |
| Alles löschen                    | Alle visuellen Elemente aus Ihrem Raum entfernen.                                          |
| **Verwalten einer Tafel (Fenster)**        |                                                                                      |
| Bewegen                         | In den Bewegungsmodus wechseln. |
| Tafel auswählen                 | Nach dem Wechsel in den Bewegungsmodus, visieren Sie die Tafel an, die Sie bewegen möchten, und sagen Sie anschließend „Tafel auswählen”. Die Tafel beginnt, Ihrem Blick zu folgen.
| Akzeptieren                       | Nach dem Wechsel in den Bewegungsmodus und der Auswahl der Tafel, platzieren Sie die Tafel an der Stelle, die Sie derzeit anvisieren, indem Sie „Akzeptieren” sagen.                                          | 
| Abbrechen                       | Stoppt eine derzeit ausgewählte Tafel, die Ihrem Blick folgt, und bringt sie zu ihrer Ausgangsposition zurück. |
| Skalieren                        | In den Skalierungsmodus wechseln, um die Größe der Tafel zu ändern. </br><br>Sie können auch das Skalierungs-Werkzeug zur Auswahl anvisieren und anschließend „Auswählen” sagen, um in den Skalierungsmodus zu wechseln.                                                                     |
| Größer oder kleiner            | Vergrößern oder verkleinern Sie das Fenster nach dem Wechsel in den Skalierungsmodus. Wiederholen Sie den „Vergrößern”- oder „Verkleinern”-Befehl, bis das Fenster die gewünschte Größe hat.                          |
| Zurücksetzen                        | Beim Anvisieren einer Tafel, die kürzlich bewegt wurde, wird die Tafel auf ihre Ausgansposition zurückgeführt, wenn man den Befehl „Zurücksetzen” sagt.          |
| **[!include[pn-onedrive](../includes/pn-onedrive.md)]**                 |                                                                                      |
| [!include[pn-onedrive](../includes/pn-onedrive.md)]                     | Öffnen Sie [!include[pn-onedrive](../includes/pn-onedrive.md)] im Stammordner, um eine Datei einzufügen.                                   |
| Schließen                        | Schließen Sie [!include[pn-onedrive](../includes/pn-onedrive.md)].                                                                      |
| Nächste                         | Zur nächsten Seite wechseln in [!include[pn-onedrive](../includes/pn-onedrive.md)].                                                         |
| Vorherige                     | Zur vorherigen Seite wechseln in [!include[pn-onedrive](../includes/pn-onedrive.md)].                                                     |
| **Sonstiges**                    |                                                                                      |
| Einstellungen                     | Zur Einstellungsseite wechseln.                                                                 |

## <a name="use-the-narrator-to-announce-incoming-calls"></a>Verwenden der Sprachausgabe zum Melden eingehender Anrufe

Sie können die Sprachausgabe aktivieren, wenn Sie diese für eingehende Aufrufe nutzen möchten. Wenn Sie die Sprachausgabe für eingehende Anrufe einschalten, wird zusätzlich zur Anzeige des Anrufernamens, dieser auch angesagt. Sie können nun „Video”, „Audio” oder „Ignorieren” sagen, um auf den eingehenden Anruf zu reagieren.

Einschalten der Sprachausgabe zum Melden eingehender Anrufe:

- Wechseln Sie zu den Einstellungen, und wählen Sie dann die Schaltfläche **An** für die Sprachausgabe aus.

  ![Sprachausgabe öffnen](media/narrator.PNG "Sprachausgabe öffnen")

## <a name="use-remote-assist-to-get-help-in-another-hololens-app"></a>Verwenden von Remote Assist zur Unterstützung in einer weiteren HoloLens-App

Haben Sie Schwierigkeiten in einer anderen [!include[pn-hololens](../includes/pn-hololens.md)]-App? Verwenden Sie [!include[pn-remote-assist](../includes/pn-remote-assist.md)], um einem Experten anzuzeigen, was geschieht, und Hilfe zu erhalten.

Tun Sie Folgendes:

1.  Öffnen Sie eine App auf Ihrem [!include[pn-hololens](../includes/pn-hololens.md)].

2.  Verwenden Sie [Öffnen-Geste](https://support.microsoft.com/en-us/help/12644/hololens-use-gestures), um die 3D-Ansicht zu verlassen, schließen Sie jedoch nicht das App-Startprogramm.

3.  Starten Sie [!include[pn-remote-assist](../includes/pn-remote-assist.md)] und rufen Sie Ihren Kontakt an.

4.  Sobald der Videoanruf verbunden wird, verwenden Sie die Öffnen-Geste, um [!include[pn-remote-assist](../includes/pn-remote-assist.md)] zu verlassen. Ihr Anruf bleibt verbunden.

5.  Wählen Sie den Livecube der App aus, für die Sie Hilfe benötigen. Sobald die App gestartet ist, kann Ihr Kontakt den Inhalt sehen und Sie anleiten.

> [!NOTE]
> Sobald Sie keine Hilfe mehr von dem Kontakt benötigen, stellen Sie sicher, dass Sie zu [!include[pn-remote-assist](../includes/pn-remote-assist.md)] zurückzukehren und den Anruf trennen. Bis dahin bleibt der Anruf verbunden und Ihr Kontakt hört und sieht, was auf Ihrem [!include[pn-hololens](../includes/pn-hololens.md)] geschieht.

## <a name="use-dynamics-365-for-field-service-from-remote-assist"></a>Verwenden von Dynamics 365 for Field Service mit Remote Assist

Wenn Ihre Organisation [Dynamics 365 for Field Service](https://dynamics.microsoft.com/en-us/field-service/overview/?&OCID=AID720979_SEM_yeaT05hp&lnkd=Bing_D365_Brand) verwendet, um Field Service-Arbeitsaufträge zu verwalten, können Sie (der Außendienstmitarbeiter) [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)]-Buchungen von [!include[pn-remote-assist](../includes/pn-remote-assist.md)] anzeigen und den im Feld **Supportkontakt** aufgelisteten Experten anrufen.
Dies ermöglicht Freisprechvideoanrufe mit [!include[pn-hololens](../includes/pn-hololens.md)] im Rahmen einer [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)]-Buchung.

> [!NOTE]
> Wenn Sie ein Administrator sind, finden Sie Informationen zur Einrichtung und Problembehandlung zur [!include[pn-field-service](../includes/pn-field-service.md)]-Integration unter [Problembehandlung Field Service-Integration](troubleshoot-field-service.md). **Beachten Sie**, dass [eine Dynamics 365-Lizenz](https://dynamics.microsoft.com/en-us/field-service/overview/?&OCID=AID720979_SEM_yeaT05hp&lnkd=Bing_D365_Brand) erforderlich ist, um [!include[pn-field-service](../includes/pn-field-service.md)]-Buchungen durch [!include[pn-remote-assist](../includes/pn-remote-assist.md)] anzuzeigen.

### <a name="view-a-field-service-booking-and-call-an-expert-from-remote-assist"></a>Anzeigen einer Field Service-Buchung und eines Expertenanrufs durch Remote Assist

1.  Wählen Sie im Kontaktmenü **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** ![Dynamics 365](media/d365-button3.png "Dynamics 365"), um das **Buchungs**-Fenster zu öffnen. (Wählen Sie erneut **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** ![Dynamics 365](media/d365-button3.png "Dynamics 365"), um das **Buchungs**-Fenster zu schließen.)  
      
    Der Bildschirm **Letzte Kontakte** wird mit einem **Buchungs**-Fenster auf der rechten Seite erscheinen.
    
    > [!NOTE]
    > Es sind nur Buchungen mit dem Status „In Bearbeitung” aufgelistet.
    
1.  Wählen Sie im **Buchungs**-Fenster die Ressource (Experten) aus. 

    ![Ressource (Experte) auswählen](media/61c6885a58d179a39e18b3af01554fcc.png "Ressource (Experte) auswählen")

1.  Wählen Sie in der gefilterten Kontaktliste die Kachel des Experten aus. Wenn Sie den gewünschten Kontakt nicht sehen, wählen Sie **Suchen**, um die holografische Tastatur zu öffnen.  
      
    Wenn Sie einen Kontakt auswählen, wird folgende Anzeige dargestellt. 

    ![Einen Kontakt auswählen](media/712a579fd6c37af3087cd31fd01bab74.png "Einen Kontakt auswählen")
    
    > [!NOTE]
    > Buchungsinformationen werden während des Videoanrufs verschwommen dargestellt, sind aber während eines Audio-Anrufs sichtbar.

### <a name="open-a-power-bi-dashboard-from-a-field-service-booking"></a>Öffnen eines Power BI-Dashboard einer Field Service-Buchung

-   Wählen Sie einen [!include[pn-power-bi](../includes/pn-power-bi.md)]-Link, um [!include[pn-power-bi](../includes/pn-power-bi.md)] in einem Browser online zu öffnen oder um die [!include[pn-power-bi](../includes/pn-power-bi.md)] Desktop-Anwendung zu öffnen.
    
    > [!NOTE]
    > Wenn Sie ein [!include[pn-power-bi](../includes/pn-power-bi.md)]-Dashboard öffnen, wird [!include[pn-remote-assist](../includes/pn-remote-assist.md)] geschlossen. Falls Sie sich in einem Anruf mit einem Experten befinden, bleibt der Experte zugeschaltet. Kehren Sie zu [!include[pn-remote-assist](../includes/pn-remote-assist.md)] zurück, indem Sie die Anwendung wieder über das Anwendungsmenü oder den Livecube öffnen.

### <a name="modify-the-default-booking-view"></a>Ändern der Standardbuchungsansicht

Um die Standardansicht von Informationen im **Buchungs**-Fenster zu ändern, [bearbeiten Sie die Ansicht wie jede andere Dynamics 365-Ansicht](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/customize/create-and-edit-views).

### <a name="see-also"></a>Siehe auch
[Microsoft Teams einrichten und mit Remote Assist verwenden](use-microsoft-teams-with-remote-assist.md)<br/>
[Anleitungsvideos](https://go.microsoft.com/fwlink/p/?linkid=2021485)<br/>
[Häufig gestellte Fragen](faq.md)<br/>
