---
title: Fehlerbehebung im Control Panel
description: Mit dem Control Panel können Sie Ihren SFTP-Speicher anhand von Instanz und IP-Adressen auf der Zulassungsliste überwachen und verwalten.
feature: Control Panel
topics: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
role: Administrator
level: Erfahren
original-url: https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/administrating/control-panel-acc/trouble-shooting.html
translation-type: ht
source-git-commit: 8847c322c63adb23ea33679714336d0aaac20100
workflow-type: ht
source-wordcount: '355'
ht-degree: 100%

---


# Fehlerbehebung im [!UICONTROL Control Panel]

## Anmelden und Homepage

### Symptom: Anmeldung bei Experience Cloud nicht möglich

**Vorgehensweise:**
Der Benutzer muss seine IMS-Organisations-ID (xxx) suchen. Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Profil „Campaign-xxx-Admins“ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich möglicherweise dennoch selbst als Benutzer hinzufügen.

### Symptom: Links auf der Experience Cloud-Startseite für den Zugriff auf [!UICONTROL Control Panel] werden für einen Benutzer nicht angezeigt

**Ursache:**
Diese Links werden Benutzern erst dann angezeigt, nachdem sie dem Produktprofil _Campaign-xxx-Administrators/Admin_ als Benutzer hinzugefügt wurden.

**Vorgehensweise:**
Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil _Campaign-xxx-Admins_ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich möglicherweise dennoch selbst als Benutzer hinzufügen.

### Symptom: Eine Instanz wird im [!UICONTROL Control Panel] nicht aufgeführt

**Ursache:**
Der Benutzer muss wahrscheinlich für die fehlende Instanz dem Produktprofil _Campaign-xxx-Administrators/Admin_ als Benutzer hinzugefügt werden.

**Vorgehensweise:**
Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil _Campaign-xxx-Admins_ hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich möglicherweise dennoch selbst als „Benutzer“ hinzufügen.

### Nützliche Videos

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*IMS-Organisations-ID prüfen (00:26 Min.)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Hinzufügen eines Administrators zum Produktprofil „Administratoren“ für die Verwendung des [!UICONTROL Control Panel] (01:03 Min.)*

### Nützliche Dokumentation

* [Funktionsweise des Control Panels](https://helpx.adobe.com/de/campaign/kb/control-panel-overview.html)
* [[!UICONTROL Verwalten von Berechtigungen für das ]Control Panel](https://helpx.adobe.com/de/campaign/kb/control-panel-access.html)

## Herstellen einer Verbindung zum SFTP-Server (Client oder API)

Für Verbindungen mit SFTP-Servern ist Folgendes erforderlich:

* [!UICONTROL Setzen auf die Zulassungsliste] der IP-Adresse, von der Sie eine Verbindung zum SFTP-Server herstellen
* Schlüsselpaar aus privatem/öffentlichem Schlüssel, das bei Adobe Campaign registriert werden muss
* Wenn Sie eine direkte Verbindung zum SFTP-Server herstellen möchten, benötigen Sie auch SFTP-Client-Software

### Nützliche Dokumentation  {#helpful-docs}

* [Anmeldung bei Ihrem SFTP-Server](https://docs.adobe.com/content/help/de-DE/control-panel/using/control-panel-home.html#LoggingintoyourSFTPserver)

