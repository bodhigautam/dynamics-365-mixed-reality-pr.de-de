---
author: MatthewJonPaul
description: Einrichten und verwenden von Microsoft Teams mit Remote Assist zur Zusammenarbeit in einem Telefonat
ms.author: mapau
ms.date: 04/01/2019
ms.service: crm-online
ms.topic: article
title: Einrichten und verwenden von Microsoft Teams mit Remote Assist
ms.reviewer: v-brycho
ms.openlocfilehash: e722a7101b62e5b533e2e51661eb608bbf321497
ms.sourcegitcommit: 157b70ec12e7cc459231aa5e32d311ebc09727d8
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 04/25/2019
ms.locfileid: "1575545"
---
# <a name="set-up-and-use-microsoft-teams-with-remote-assist-to-collaborate-on-a-call"></a>Einrichten und verwenden von Microsoft Teams mit Remote Assist zur Zusammenarbeit in einem Telefonat

Ein [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)]-Benutzer auf [!include[pn-hololens](../includes/pn-hololens.md)] kann während eines Videoanrufs mit einem Kollegen (typischerweise ein Experte auf einem bestimmten Gebiet) zusammenarbeiten, indem er [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] verwendet. Der Experte kann alles sehen, was der Benutzer [!include[pn-remote-assist](../includes/pn-remote-assist.md)] sieht, und sie können holografisch zeichnen und zusammen kommentieren. Nehmen wir beispielsweise an, ein Außendienstmitarbeiter wartet eine sehr komplexe Maschine und ist sich nicht sicher, wie er ein Problem lösen kann. Der Außendienstmitarbeiter kann überall auf der Welt einen Experten anrufen und sich von diesem bei der Wartung mit Anmerkungen oder Dateien unterstützen lassen.

Die Einrichtung dieser Zusammenarbeit mit [!include[pn-teams](../includes/pn-teams.md)] ist einfach und für die Zuhilfenahme des Experten entstehen keine Kosten.

Benötigen Sie weitere Hilfe? [Unter Remote Assist Häufig gestellte Fragen](faq.md) finden Sie Antworten auf häufig gestellte Fragen.

[Sehen Sie Anleitungsvideos](https://go.microsoft.com/fwlink/p/?linkid=2021485) über [!include[pn-remote-assist](../includes/pn-remote-assist.md)].

## <a name="what-youll-need"></a>Was Sie benötigen


Der Remote Assist-Benutzer (Außendienstmitarbeiter) auf HoloLens benötigt:

-   [Ein Abonnement für Remote Assist.](../licensing/buy-and-deploy.md) Das Abonnement für Remote Assist beinhaltet ein Abonnement für Microsoft Teams.

-   Ein [!include[pn-hololens](../includes/pn-hololens.md)] mit dem [Windows 10 April 2018 Update](https://support.microsoft.com/en-us/help/12643) (oder höher).

-   Ein [!include[pn-azure-active-directory](../includes/pn-azure-active-directory.md)]-Konto.

Der Experte benötigt:

-   Einen PC, auf dem Windows 10 mit der neuesten Version von [Microsoft Teams](https://products.office.com/microsoft-teams/group-chat-software) läuft, oder ein mobiles Gerät, auf dem die Microsoft Teams Mobile-App läuft. Der Experte verwendet Teams, um mit dem Remote Assist-Benutzer auf HoloLens zu kommunizieren. Teams kann als [kostenloser Download unter](https://teams.microsoft.com/downloads) zur Verfügung stehen.

-   Ein kostenloses [!include[cc-microsoft](../includes/cc-microsoft.md)]-Konto. Der Experte verfügt möglicherweise bereits über ein [!include[cc-microsoft](../includes/cc-microsoft.md)]-Konto, wenn er sich im [!include[cc-microsoft](../includes/cc-microsoft.md)] App Store, auf Skype, Xbox, Hotmail oder Outlook.com registriert hat. Verfügt der Experte noch nicht über ein [!include[cc-microsoft](../includes/cc-microsoft.md)]-Konto, kann er sich unter [https://account.microsoft.com/account](https://account.microsoft.com/account) für eines registrieren.

## <a name="setup"></a>Einrichtung

Einen Experten können Sie mit [!include[pn-teams](../includes/pn-teams.md)] in drei einfachen Schritten eingliedern und mit ihm zusammenarbeiten:

| **Schritt** | **Beschreibung**                                                                  | **Wer führt diesen Schritt aus?**           |
|----------|----------------------------------------------------------------------------------|-----------------------------------|
|    1.      | Aktivieren Sie einen Gastzugang für [!include[pn-teams](../includes/pn-teams.md)]                                                    | Administrator                     |
|    2.      | Laden Sie den Experten ein, als Gast einem Team beizutreten, indem Sie sein [!include[cc-microsoft](../includes/cc-microsoft.md)]-Konto verwenden, | Administrator oder [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer und -Experte (zum Download [!include[pn-teams](../includes/pn-teams.md)]) |
|    3.      | Tätigen Sie einen Anruf                                                                     | [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer oder -Experte     |

### <a name="step-1-enable-guest-access-for-teams"></a>Schritt 1: Aktivieren Sie einen Gastzugang für Teams

1.  Wenn Sie der Administrator des hauptsächlichen [!include[pn-azure](../includes/pn-azure.md)]-Mandanten sind, gehen Sie zu <https://admin.microsoft.com/adminportal/>, um das Office Admin-Portal zu öffnen, und melden Sie sich an.

2.  Wählen Sie im Menü auf der linken Seite **Mehr anzeigen** \> **Einstellungen** \> **Dienste & Add-Ins**.

    ![Dienste & Add-Ins](media/bf81ea48e3ccd560b6f44dbc72a73eb5.png "Dienste & Add-Ins")

1.  Wählen Sie **[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)]** aus der Anwendungsliste aus.

    ![Microsoft Teams](media/ad846431f181b1c6df362bc2e0e03167.png "Microsoft Teams")

1.  Wählen Sie **Einstellungen nach Benutzer/Lizenztyp**.

2.  Wählen Sie in der Dropdown-Liste **Gast** neben **Zu konfigurierenden Benutzer/Lizenztyp auswählen**.

3.  Setzen Sie **[!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] für alle Benutzer dieses Typs an- oder ausschalten** auf **An** und wählen Sie anschließend **Speichern**.

    ![Speichern Sie ](media/9f095e7553a4af03ff13ea6a29a9343a.png "Speichern")

4.  Warten Sie eine Stunde, bis sich die Einstellungen verteilt haben.

### <a name="step-2-invite-the-expert-to-join-a-team"></a>Schritt 2: Den Experten zum Beitritt zu einem Team einladen

1.  Wählen Sie **Einem Team beitreten oder eines anlegen** in [!include[pn-teams](../includes/pn-teams.md)], um ein Team anzulegen, falls es noch nicht existiert. Der [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer und der Experte müssen in demselben Team sein, um kommunizieren zu können.

    ![Einem Team beitreten oder eines anlegen](media/16e00f809d210dcb3b1e8c8e859b73da.png "Einem Team beitreten oder eines anlegen")

1.  Wenn Sie dazu aufgefordert werden, Mitglieder hinzuzufügen, geben Sie das [!include[cc-microsoft](../includes/cc-microsoft.md)]-Konto des Experten ein.

    ![Microsoft-Konto](media/71e9276273f8f47b786f743416a2cb64.png "Microsoft-Konto")

    > [!NOTE]
    > Wenn Sie nicht die Option zum Hinzufügen eines Gastes durch Eingabe einer E-Mail-Adresse sehen, ist wahrscheinlich der Gastzugang in dem [!include[pn-azure](../includes/pn-azure.md)]-Mandanten für [!include[pn-teams](../includes/pn-teams.md)] in Ihrem Unternehmen nicht aktiviert. Aktivieren Sie den Gastzugang wie bereits in diesem Inhalt beschrieben.

1.  Der Experte erhält sofort eine E-Mail und kann den in ihr enthaltenen Link anklicken, um [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] zu öffnen (oder herunterzuladen). Diese Version von [!include[pn-teams](../includes/pn-teams.md)] ist kostenlos. Es handelt sich nicht um eine Testversion.

### <a name="step-3-place-a-call"></a>Schritt 3. Tätigen Sie einen Anruf

1.  Der Experte startet die [!include[pn-teams](../includes/pn-teams.md)]-App und der [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer auf [!include[pn-hololens](../includes/pn-hololens.md)] meldet sich wie gewohnt auf dem Konto an.

    > [!IMPORTANT]
    > Startet der Experte zum ersten Mal [!include[pn-teams](../includes/pn-teams.md)] und wurde bisher nicht zu anderen Teams eingeladen, bringt [!include[pn-teams](../includes/pn-teams.md)] den Experten automatisch an den richtigen Ort. Wurde der Experte bereits zu anderen Teams ein geladen, muss er möglicherweise zum entsprechenden Mandanten wechseln.  
    >     
    > Zum Wechseln von Mandanten, wählen Sie den entsprechenden Gastmandanten im Dropdown-Menü rechts oben im Fenster aus:
    
    ![Gastmandant](media/55237a5359fb66daf7bbb9413adab6b9.png "Gastmandant")
       
    > [!NOTE]
    > [!include[pn-teams](../includes/pn-teams.md)] benötigt möglicherweise einige Sekunden, um neu zu laden.
    
1.  Beide Parteien können einen Anruf tätigen. Unter Umständen müssen Sie in den Kontakten nach der richtigen Person suchen.

    > [!NOTE]
    > Der Gast kann jedes Mitglied desselben Teams anrufen. Zur Erweiterung dieser Funktionalität, laden Sie alle anderen Mitglieder in Ihrem Unternehmen ein, die von dem Zugriff auf diesen neuen Experten profitieren würden.

## <a name="working-with-annotations"></a>Arbeiten mit Anmerkungen

Sobald [!include[pn-teams](../includes/pn-teams.md)] installiert ist, kann der Experte über [!include[pn-remote-assist](../includes/pn-remote-assist.md)] auf einem [!include[pn-hololens](../includes/pn-hololens.md)] Videoanrufe zu Kontakten tätigen (und von diesen empfangen).

In einem Anruf sieht der Experte den Platz des Kontakts – einschließlich der Hologramme – und kann die Mixed Reality-Symbolleiste im Fenster des Videoanrufs verwenden, um Hologramme hinzuzufügen.

![Mixed Reality-Symbolleiste](media/071f358ab6bbf7c2072b15d9203a1593.png "Mixed Reality-Symbolleiste")

## <a name="draw-and-annotate"></a>Zeichnen und anmerken

### <a name="edit-mode"></a>Bearbeitungsmodus

Um den Raum eines Kontaktes mit Anmerkungen zu versehen, führen Sie zunächst folgende Schritte aus, um den Videostream anzuhalten und in den Bearbeitungsmodus zu wechseln:

-   Wählen Sie eine beliebige Stelle im Anruffenster aus.

-   Wählen Sie eines der Elemente in der Mixed Reality-Symbolleiste aus.

-   Wählen Sie **Bearbeitung beginnen**.

Im Bearbeitungsmodus sieht der Experte weiterhin einen Livestream des Anrufs in einer Ecke des App-Fensters.

### <a name="add-arrows-ink-and-files"></a>Hinzufügen von Pfeilen, Tinte und Dateien

Verwenden Sie die Mixed Reality-Symbolleiste zum Platzieren von Pfeilen, zum Zeichnen oder zum Hinzufügen von Dateien:

-   Zum Hinzufügen von Pfeilen, wählen Sie **Pfeil platzieren** ![Pfeil platzieren](media/6584f4b7932378aa23f6efbf460b304c.png "Pfeil platzieren").

-   Zum Hinzufügen von Tinte, wählen Sie **Tinte** ![Tinte](media/187307e30fd713f5ae67aba854b78bc4.png "Tinte").

-   Zum Ändern des Pfeils oder der Tintenfarbe, wählten Sie **Eine Farbe wählen** ![Eine Farbe wählen](media/5d9d3c70cf19ed175a8dc1ad71a60fc5.png "Eine Farbe wählen").

-   Zum Hinzufügen einer Datei, wählen Sie **Dateien einfügen** ![Dateien einfügen](media/41aa538d3be8e163215f7d9374abe90e.png "Dateien einfügen") und fügen anschließend eine Bild- oder PDF-Datei hinzu.

    > [!NOTE]
    > Der Experte kann Bilder nach dem Hinzufügen nicht bewegen, entfernen oder ihre Größe ändern.

### <a name="finish-editing"></a>Bearbeitung abschließen

Wenn Sie mit die Anmerkungen beendet haben, führen Sie eine der folgenden Aktionen aus, um die Bearbeitung abzuschließen und in den Live-Modus zurückzukehren:

-   Wählen Sie **Bearbeitung beenden**.

-   Wählen Sie den Live-Video-Feed in der Ecke Ihres Bildschirms aus.

### <a name="make-changes-to-edits"></a>Änderungen an den Bearbeitungen vornehmen

Um Änderungen an Bearbeitungen vorzunehmen, gehen Sie wie folgt vor:

-   Wählen Sie im Bearbeitungsmodus **Rückgängig**, um die letzte Aktion rückgängig zu machen.

-   Wählen Sie im Bearbeitungsmodus **Alles löschen** ![Alles löschen](media/3aab547aa81003ad181eceadc2c83a47.png "Alles löschen"), um alle während dieser Bearbeitungssitzung erstellten Anmerkungen zu löschen.

-   Wählen Sie im Live-Modus **Alles löschen** ![Alles löschen](media/3aab547aa81003ad181eceadc2c83a47.png "Alles löschen"), um alle während dieses Anrufs erstellten Anmerkungen zu löschen.

> [!NOTE]
> Bestimmte Zeichnungen oder Pfeile können nicht entfernt werden. Nur der [!include[pn-hololens](../includes/pn-hololens.md)]-Benutzer kann Änderungen an Bildern vornehmen oder löschen, die von einem Experten hinzugefügt wurden.

## <a name="share-your-desktop-or-a-running-application-with-a-remote-assist-user"></a>Teilen des Desktops oder einer laufenden Anwendung mit einem Remote Assist-Benutzer

Wenn Sie Ihren Desktop oder Ihre laufende Anwendung mit einem [!include[pn-remote-assist](../includes/pn-remote-assist.md)]-Benutzer teilen, ändert sich der Video-Feed des Benutzers in eine einheitliche Farbe. Sie können weiterhin alle Werkzeuge der Symbolleiste nutzen, auch wenn ihr Video-Feed nicht mehr angezeigt wird.

Um Ihren Desktop oder eine laufende Anwendung zu teilen:

1. Wählen Sie in [!include[pn-teams](../includes/pn-teams.md)] die Schaltfläche **Teilen-Leiste öffnen**.

   ![Schaltfläche Teilen-Leiste](media/share-tray.PNG "Schaltfläche Teilen-Leiste")
   
2. Wählen Sie den Bildschirm aus, den Sie teilen möchten.

> [!NOTE]
> Sie können nur eine Anwendung oder einen Bildschirm gleichzeitig teilen. Wählen Sie zum Teilen eines anderen Bildschirms die Schaltfläche **Teilen-Leiste schließen**, um das Teilen zu beenden. Wählen Sie nun einen anderen Bildschirm aus und beginnen erneut mit dem Teilen.

### <a name="see-also"></a>Siehe auch
[Benutzerhandbuch](user-guide.md)<br/>
[Anleitungsvideos](https://go.microsoft.com/fwlink/p/?linkid=2021485)<br/>
[Häufig gestellte Fragen](faq.md)<br/>
