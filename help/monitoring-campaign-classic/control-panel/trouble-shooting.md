---
title: Fehlerbehebung im Control Panel
description: Mit dem Control Panel können Sie Ihren SFTP-Speicher nach Instanz und IP-Adressen der Zulassungsliste überwachen und verwalten.
feature: Control Panel
kt: 2938
doc-type: article
activity: use
team: PM
source-git-commit: 8910430585bdaa0db076db9c34b34798f649d39c
workflow-type: tm+mt
source-wordcount: '344'
ht-degree: 44%

---


# Fehlerbehebung im [!UICONTROL Control Panel]

## Anmelden und Homepage

### Symptom: Anmeldung bei Experience Cloud nicht möglich

**Vorgehensweise:**
Der Benutzer muss seine IMS-Organisations-ID (xxx) finden. Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil &quot;Campaign-xxx-Admins&quot;hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich selbst als Benutzer hinzufügen.

### Symptom: Links auf der Experience Cloud-Startseite für den Zugriff auf [!UICONTROL Control Panel] werden für einen Benutzer nicht angezeigt

**Ursache:**
Diese Links werden Benutzern erst dann angezeigt, nachdem sie dem Produktprofil _Campaign-xxx-Administrators/Admin_ als Benutzer hinzugefügt wurden.

**Vorgehensweise:**
Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil  _Campaign-xxx-_  Admins hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich selbst als &quot;Benutzer&quot;hinzufügen.

### Symptom: Eine Instanz wird im [!UICONTROL Control Panel] nicht aufgeführt

**Ursache:**
Der Benutzer muss höchstwahrscheinlich als &quot;Benutzer&quot;-Produktprofil  _Campaign-xxx-Administrators/_ Administrator für die fehlende Instanz hinzugefügt werden.

**Vorgehensweise:**
Der Administrator muss den Benutzer für jede Instanz, die er verwalten möchte, dem Produktprofil  _Campaign-xxx-_  Admins hinzufügen. Wenn der Benutzer ein Administrator aller Instanzen ist, muss er sich selbst als &quot;Benutzer&quot;hinzufügen.

### Nützliche Videos

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)

*IMS-Organisations-ID prüfen (00:26 Min.)*

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)

*Hinzufügen eines Administrators zum Produktprofil „Administratoren“ für die Verwendung des [!UICONTROL Control Panel] (01:03 Min.)*

### Nützliche Dokumentation

* [Funktionsweise des Control Panels](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=de)
* [[!UICONTROL Verwalten von Berechtigungen für das ]Control Panel](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

## Herstellen einer Verbindung zum SFTP-Server (Client oder API)

Für Verbindungen mit SFTP-Servern ist Folgendes erforderlich:

* [!UICONTROL Setzen auf die Zulassungsliste] der IP-Adresse, von der Sie eine Verbindung zum SFTP-Server herstellen
* Paar aus privatem/öffentlichem Schlüssel, das bei Adobe Campaign registriert werden muss
* Wenn Sie eine direkte Verbindung zum SFTP-Server herstellen möchten, benötigen Sie SFTP-Client-Software

### Nützliche Dokumentation {#helpful-docs}

* [Anmeldung bei Ihrem SFTP-Server](https://experienceleague.adobe.com/docs/control-panel/using/control-panel-home.html?lang=en)

