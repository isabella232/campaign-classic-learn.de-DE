---
title: Control Panel mit Problemen beim Schießen
description: Mit dem Control Panel können Sie Ihre SFTP-Datenspeicherung nach Instanz und Zulassungsliste-IP-Adressen überwachen und verwalten.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
translation-type: tm+mt
source-git-commit: b2820c65a88d25f9b7a4ed5005cd5083463e000a
workflow-type: tm+mt
source-wordcount: '351'
ht-degree: 3%

---


# Probleme beim Schießen [!UICONTROL des Control Panels]

## Anmelden und Homepage

### Symptom: Anmeldung bei Experience Cloud nicht möglich

**Vorgehensweise:**
Der Benutzer muss seine IMS-Organisations-ID (xxx) suchen. Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Profil &quot;Kampagne-xxx-Admins&quot;hinzufügen. Wenn der Benutzer Administrator aller Instanzen ist, muss er sich möglicherweise noch als Benutzer hinzufügen.

### Symptom: Links im Experience Cloud-Home für den Zugriff auf [!UICONTROL Control Panel] werden nicht angezeigt

**Ursache:**
Die Links werden erst dann angezeigt, wenn sie als Benutzer zu Product Profil _Kampagne-xxx-Administrators/Admin_ hinzugefügt wurden.

**Vorgehensweise:**
Der Administrator muss den Profil für jede Instanz, die er verwalten möchte, der _Kampagne-xxx-Admins_ des Produkts hinzufügen. Wenn der Benutzer Administrator aller Instanzen ist, muss er sich möglicherweise als &quot;Benutzer&quot;hinzufügen.

### Symptom: Eine Instanz wird nicht im [!UICONTROL Control Panel aufgeführt]

**Ursache:**
Der Benutzer muss höchstwahrscheinlich als &quot;user&quot; Product Profil _Kampagne-xxx-Administrators/Admin_ für die fehlende Instanz hinzugefügt werden

**Vorgehensweise:**
Der Administrator muss den Profil für jede Instanz, die er verwalten möchte, der _Kampagne-xxx-Admins_ des Produkts hinzufügen. Wenn der Benutzer Administrator aller Instanzen ist, muss er sich möglicherweise noch als &quot;Benutzer&quot;hinzufügen.

### Hilfreiche Videos

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*IMS-Organisations-ID überprüfen (00:26 Min.)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Hinzufügen eines Administrators zu Produktadministratoren, um die[!UICONTROL Systemsteuerung]verwenden zu können (01:03 Min.)*

### Hilfreiche Dokumentation

* [Entdecken Sie den Control Panel](https://helpx.adobe.com/campaign/kb/control-panel-overview.html)
* [[!UICONTROL Berechtigungen für das Control Panel verwalten]](https://helpx.adobe.com/campaign/kb/control-panel-access.html)

## Verbindung zum SFTP-Server herstellen (Client oder API)

Für die Verbindung mit den SFTP-Servern ist Folgendes erforderlich:

* [!UICONTROL Zulassen der Auflistung] der IP-Adresse, von der Sie eine Verbindung zum SFTP-Server herstellen
* Private/öffentliche Schlüsselpaare, die bei Adobe Campaign registriert werden müssen
* Wenn Sie eine direkte Verbindung zum SFTP-Server herstellen, benötigen Sie auch die SFTP-Clientsoftware

### Hilfreiche Dokumentation

* [Anmeldung bei Ihrem SFTP-Server](https://helpx.adobe.com/campaign/kb/control-panel-sftp.html#LoggingintoyourSFTPserver)

