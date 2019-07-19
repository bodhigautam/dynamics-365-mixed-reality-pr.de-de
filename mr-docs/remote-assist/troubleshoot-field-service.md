---
author: bencorn
description: So können Sie prüfen, ob Sie die richtige Version, Ansichten und Daten für die Integration von Dynamics 365 for Field Service in Dynamics 365 Remote Assist haben
ms.author: bencorn
ms.date: 06/04/2019
ms.service: crm-online
ms.topic: article
title: Dynamics 365 for Field Service in Dynamics 365 Remote Assist integrieren
ms.reviewer: v-brycho
ms.openlocfilehash: 71d89b161d269c5559344f021f6f5aaa1a8aa3ce
ms.sourcegitcommit: 80c2a9dc71cab3914d3a96d37904bd1e16e4b450
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 06/03/2019
ms.locfileid: "1617259"
---
# <a name="troubleshoot-field-service-integration-with-dynamics-365-remote-assist"></a>Problembehandlung für die Field Service-Integration Dynamics 365 Remote Assist

Wenn Ihre Organisation [Dynamics 365 for Field Service](https://dynamics.microsoft.com/en-us/field-service/overview/?&OCID=AID720979_SEM_yeaT05hp&lnkd=Bing_D365_Brand) verwendet, um [!include[pn-field-service](../includes/pn-field-service.md)] Arbeitsaufträge zu verwalten, kann der Mitarbeiter mit direktem Kundenkontakt, der [!include[pn-hololens](../includes/pn-hololens.md)] verwendet, [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] Buchungen von [!include[pn-remote-assist](../includes/pn-remote-assist.md)] aus anzeigen und schnell die im Feld **Supportkontakt** aufgeführten Experten anzeigen. Dadurch können Mitarbeiter mit direktem Kundenkontakt Freisprechanrufe über [!include[pn-hololens](../includes/pn-hololens.md)] im Kontext einer [!include[pn-dyn-365-field-service](../includes/pn-dyn-365-field-service.md)] Buchung durchführen.

In diesem Thema wird beschrieben:

- Anforderungen für die Integration von [!include[pn-field-service](../includes/pn-field-service.md)]
- So sorgen Sie dafür, dass [!include[pn-field-service](../includes/pn-field-service.md)] korrekt eingerichtet ist 
- So aktualisieren Sie die Instanz von [!include[pn-dyn-365](../includes/pn-dyn-365.md)], wenn Sie nicht die korrekte Version von [!include[pn-field-service](../includes/pn-field-service.md)] haben
- So fügen Sie Daten für erforderliche Felder in einen [!include[pn-field-service](../includes/pn-field-service.md)]-Arbeitsauftrag und eine Buchung ein
- So passen Sie den Bereich **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** an, der in [!include[pn-remote-assist](../includes/pn-remote-assist.md)] angezeigt wird

## <a name="requirements"></a>Anforderungen

Bevor Sie beginnen, stellen Sie sicher, dass Sie Folgendes eingerichtet haben:

- Ein [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-azure](../includes/pn-azure.md)] Mandant mit einem Abonnement von [!include[pn-dyn-365](../includes/pn-dyn-365.md)] **und** einem [!include[pn-dyn-365-remote-assist](../includes/pn-dyn-365-remote-assist.md)] Abonnement. Beide sind erforderlich – [!include[pn-remote-assist](../includes/pn-remote-assist.md)] ist nicht in einem [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Paket enthalten.

  > [!NOTE]  
  > Der Mandant kann mehr als eine Instanz von [!include[pn-dyn-365](../includes/pn-dyn-365.md)] enthalten. [!include[pn-remote-assist](../includes/pn-remote-assist.md)] hat die Möglichkeit, eine Instanz in der App auszuwählen.

- Sie benötigen Administratorzugriffsrechte, um die Mandantinstanz von [!include[pn-dyn-365](../includes/pn-dyn-365.md)] hinzuzufügen oder zu aktualisieren.
- In der Instanz [!include[pn-dyn-365](../includes/pn-dyn-365.md)] muss die App [!include[pn-field-service](../includes/pn-field-service.md)] installiert sein und sie muss die Ansicht **My In Progress Bookings** enthalten. Um sicherzugehen, dass diese Ansicht installiert ist, empfehlen wir die [!include[pn-field-service](../includes/pn-field-service.md)] Version 8.2 oder später. In diesem Thema wird beschrieben, wie Sie sicherstellen können, dass Sie die korrekte Version und Ansicht haben.
- Der Mandant muss mindestens zwei Benutzerkonten haben.
- Den Benutzerkonten müssen die folgenden Lizenzen zugeordnet sein:
  - [!include[pn-office-365](../includes/pn-office-365.md)] Lizenz, die [!include[cc-microsoft](../includes/cc-microsoft.md)] [!include[pn-teams](../includes/pn-teams.md)] enthält
  - [!include[pn-remote-assist](../includes/pn-remote-assist.md)]
  - A [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Lizenz, die [!include[pn-field-service](../includes/pn-field-service.md)] enthält

## <a name="confirm-that-the-my-in-progress-bookings-view-is-included"></a>Bestätigen Sie, dass die Ansicht **Meine in Bearbeitung befindlichen Buchungen** enthalten ist

Wenn Sie eine Instanz haben, aber nicht sicher sein, ob die korrekte Ansicht installiert ist, führen Sie zur Bestätigung die folgenden Schritte durch:

1. Stellen Sie sicher, dass Sie als Administrator für die [!include[pn-dyn-365](../includes/pn-dyn-365.md)]-Instanz angemeldet sind.

2. Wählen Sie **Service** > **Einstellungen** > **Anpassungen** > **System anpassen** aus.

   ![Anpassungen auswählen](media/Customizations.PNG "Anpassungen auswählen")
   
3. Erweitern Sie auf dem [!include[pn-powerapps](../includes/pn-powerapps.md)] Bildschirm **Entitäten**, erweitern Sie die Entität **Buchbare Ressourcenbuchung** und wählen Sie dann **Ansichten** aus.

4. Überprüfen Sie auf dem Bildschirm **Ansichten**, ob die Ansicht **Meine in Bearbeitung befindlichen Buchungen** aufgelistet ist.

   ![Ansicht „Buchbare Ressource“](media/bookable-resource-views.PNG "Ansicht „Buchbare Ressource“")
   
5. Führen Sie einen der folgenden Schritte aus:

   - Wenn die Ansicht aufgelistet ist, fahren Sie mit [Einen Arbeitsauftrag und Buchung hinzufügen](#add-a-work-order-and-booking) weiter hinten in diesem Thema fort.
   
   - Wenn die Ansicht nicht aufgeführt ist, in, [aktualisieren Sie die Dynamics 365 Instanz](#upgrade-the-dynamics-365-instance), wie in der nächsten Prozedur in diesem Thema beschrieben.
   
## <a name="upgrade-the-dynamics-365-instance"></a>Die Dynamics 365-Instanz aktualisieren

Wenn die Ansicht **Meine in Bearbeitung befindlichen Buchungen** nicht aufgeführt ist, wie in der vorherigen Prozedur beschrieben, müssen Sie Ihre [!include[pn-field-service](../includes/pn-field-service.md)] Version auf mindestens 8.2 aktualisieren. [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Aktualisierungen werden nicht automatisch ausgeführt; sie werden von Kunden bestimmt. 

So aktualisieren Sie eine Instanz:

1. Rufen Sie das [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Admin Center auf, wählen Sie die Registerkarte **Instanzen** und dann **Lösungen** aus, um zu sehen, welche Version von [!include[pn-field-service](../includes/pn-field-service.md)] Sie haben. 

   ![Admin Center mit der Anzeige der Field Service-Version](media/admin-center.PNG "Admin Center mit der Anzeige der Field Service-Version")

2. Führen Sie einen der folgenden Schritte aus:

   - Wenn Sie nicht die Version 8.2 oder später haben, wird die Schaltfläche **Upgrade** auf der rechten Seite des Bildschirms im Feld **[!include[pn-field-service](../includes/pn-field-service.md)]** angezeigt. Wählen Sie die Schaltfläche **Upgrade** aus, um das Upgrade zu beginnen. 
   
     Wenn keine Schaltfläche **Upgrade** vorhanden ist, können Sie die Version 8.2 oder später abrufen, indem Sie [sich für eine Testversion anmelden](https://appsource.microsoft.com/en-us/product/dynamics-365/mscrm.40fd37ef-dca4-4b0d-9f41-d16703b7d070?tab=Overview) oder das [Dynamics Insider Portal](http://experience.dynamics.com/insider) aufrufen.

     > [!NOTE]
     > Wenn die [!include[pn-field-service](../includes/pn-field-service.md)] Installation fehlschlägt, können Sie es zurücksetzen oder eine neue Instanz erstellen. Für die [!include[pn-field-service](../includes/pn-field-service.md)] Installation sind bestimmte Schritte erforderlich und die Installation kann fehlschlagen, wenn die Schritte in anderer Reihenfolge durchgeführt werden. [Weitere Informationen zur Field Service-Installation.](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/field-service/install-field-service)

   - Wenn die richtige Version von [!include[pn-field-service](../includes/pn-field-service.md)] installiert und die Ansicht **Meine in Bearbeitung befindlichen Buchungen** enthalten ist, fahren Sie mit dem nächsten Schritt [Einen Arbeitsauftrag und Buchung hinzufügen](#add-a-work-order-and-booking) aus diesem Abschnitt fort.
   
## <a name="add-a-work-order-and-booking"></a>Einen Arbeitsauftrag und Buchung hinzufügen
   
Daten werden nicht im Bereich **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** in [!include[pn-remote-assist](../includes/pn-remote-assist.md)] angezeigt, außer die folgenden Anforderungen sind erfüllt:
   
- Es muss mindestens ein Arbeitsauftrag.

- Die folgenden Felder im Arbeitsauftrag müssen einen Wert haben:
   
   |**Feld**|**Wert**|
   |------------------|---------------------------------------------------------------------------------------------------|
   |Systemstatus|Der Wert in diesem Feld muss **In Bearbeitung** sein.|
   |Ressource|Speichert die E-Mail-Adresse für den [!include[pn-hololens](../includes/pn-hololens.md)] Benutzer. Diese Adresse muss der E-Mail-Adresse für den [!include[pn-hololens](../includes/pn-hololens.md)] Benutzer entsprechen.|
 
### <a name="create-a-work-order"></a>Arbeitsauftrag erstellen
   
1.  Öffnen Sie die [!include[pn-dyn-365](../includes/pn-dyn-365.md)] Instanz in Ihrem Browser.

2.  Wählen Sie das Pull-down-Menü neben **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]**, wählen Sie **[!include[pn-field-service](../includes/pn-field-service.md)]** und anschließend **Neu** aus.

3.  Füllen Sie alle Felder aus, die ein Sternchen enthalten.

    ![Arbeitsauftragsbildschirm](media/work-order.PNG "Arbeitsauftragsbildschirm")
    
4.  Wählen Sie in rechten unteren Ecke **Speichern** aus.

### <a name="add-values-for-the-required-fields"></a>Werte für die erforderlichen Felder einfügen

1.  Wählen Sie die Registerkarte **Einstellungen** aus.  

2.  Wählen Sie die Option **Buchen** am oberen Rand des Bildschirms aus. Sie verwenden diese Option, um eine Zeit zu buchen, in der die Ressource die Arbeit ausführt.

3.  Geben Sie im Feld **Ressource** die Ressource für den [!include[pn-hololens](../includes/pn-hololens.md)] Benutzer ein. Die E-Mail-Adresse der Ressource muss der E-Mail-Adresse für den [!include[pn-hololens](../includes/pn-hololens.md)] Benutzer entsprechen. Wenn Sie keine Ressource auswählen oder die E-Mail-Adresse nicht übereinstimmt, werden keine Daten im **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** Bereich in [!include[pn-remote-assist](../includes/pn-remote-assist.md)] angezeigt.

4.  Wählen Sie die Buchungsinformationen aus und setzen Sie das Feld **Buchungsstatus** dann auf **In Bearbeitung**.

    ![Feld Buchungsstatus](media/booking-status.PNG "Feld Buchungsstatus")
    
5.  Nehmen Sie die gewünschten Änderungen an anderen Feldern vor (keine anderen Daten sind erforderlich, damit die Daten im **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** Bereich in [!include[pn-remote-assist](../includes/pn-remote-assist.md)]) angezeigt werden können.

6.  Speichern Sie Ihre Änderungen.

## <a name="add-custom-fields-to-the-dynamics-365-pane-in-remote-assist-optional"></a>Benutzerdefinierte Felder in den Bereich **Dynamics 365** in Remote Assist einfügen (optional)

Sie können den Bereich **[!include[pn-dyn-365](../includes/pn-dyn-365.md)]** in [!include[pn-remote-assist](../includes/pn-remote-assist.md)] verändern, indem Sie Felder, Formulare oder die Ansicht **My In Progress Bookings** in [!include[pn-dyn-365](../includes/pn-dyn-365.md)] anpassen.

Weitere Felder, Formulare oder Ansichten in [!include[pn-dyn-365](../includes/pn-dyn-365.md)]anpassen:

1. Wählen Sie **Service** > **Einstellungen** > **Anpassungen** > **System anpassen** aus.

   ![Anpassungen auswählen](media/Customizations.PNG "Anpassungen auswählen")
    
2. Erweitern Sie **Entitäten**, öffnen Sie die Entität, die Sie verändern möchten, und wählen Sie dann je nachdem, was Sie tun möchten, **Felder**, **Formulare** oder **Ansichten** aus. 

Die folgende Tabelle enthält Beispiele der Arten von Änderung, die in [!include[pn-dyn-365](../includes/pn-dyn-365.md)] möglich sind, und beschreibt, wie sie vorgenommen werden.

|**Ziel**|**Vorgehensweise**|**Beispiel**|
|------------------|---------------------------------------------------|--------------------------------------------------------|
|Ein neues Feld hinzufügen, das noch nicht in [!include[pn-dyn-365](../includes/pn-dyn-365.md)] vorhanden ist|Erstellen Sie das Feld in der zu bearbeitenden Entität und fügen Sie dieses Feld in die Ansicht **Meine in Bearbeitung befindlichen Buchungen** ein.|Öffnen Sie im Fenster **Anpassungen** die Entität **Arbeitsauftrag** und fügen Sie das gewünschte Feld ein.<br /><br />**Hinweis** In das Feld müssen Daten eingefügt werden. Das Feld wird nur angezeigt, wenn es Daten enthält.|
|Ein vorhandenes Feld in die Ansicht **Meine in Bearbeitung befindlichen Buchungen** einfügen|Fügen Sie in der Ansicht **Meine in Bearbeitung befindlichen Buchungen** eine Spalte für das Feld ein. Sie können ein Feld aus jeder Entität in [!include[pn-dyn-365](../includes/pn-dyn-365.md)]einfügen.|Öffnen Sie im Fenster **Anpassungen** die Entität **Buchbare Ressourcenbuchung**, wählen Sie die Ansicht **Meine in Bearbeitung befindlichen Buchungen** aus und wählen Sie dann **Spalten hinzufügen** aus.<br /><br />**Hinweis** In das Feld müssen Daten eingefügt werden. Das Feld wird nur angezeigt, wenn es Daten enthält.|
|Fügen Sie einen [!include[pn-power-bi](../includes/pn-power-bi.md)]-Weblink ein. Wenn der Benutzer in [!include[pn-hololens](../includes/pn-hololens.md)] den Link auswählt, wird er automatisch im [!include[pn-edge](../includes/pn-edge.md)]-Browser geöffnet.|Erstellen Sie ein Feld, das Textzeichenfolgen unterstützt.|Geben Sie einen Weblink in den Felddaten ein, zum Beispiel den zum Öffnen eines [!include[pn-power-bi](../includes/pn-power-bi.md)]-Dashboards verwendeten.  Wenn es eine gültige URL ist, wird sie automatisch ein Link.|

### <a name="see-also"></a>Siehe auch

- [Felder in Dynamics 365 erstellen oder bearbeiten](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/customize/create-edit-fields)

- [Ansichten in Dynamics 365 erstellen oder bearbeiten](https://docs.microsoft.com/en-us/dynamics365/customer-engagement/customize/create-edit-views)
