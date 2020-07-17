---
title: Control Panel
seo-title: Control Panel
description: Mit dem Control Panel können Sie Ihre SFTP-Datenspeicherung nach Instanz und Zulassungsliste-IP-Adressen überwachen und verwalten.
seo-description: Mit dem Control Panel können Sie Ihre SFTP-Datenspeicherung nach Instanz und Zulassungsliste-IP-Adressen überwachen und verwalten.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: 37c36a52fb6fc7a5ccfe5d82dc9a32397b9a7d89
workflow-type: tm+mt
source-wordcount: '485'
ht-degree: 7%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>Die Begriffe &quot;[!UICONTROL Whitelist]&quot;und &quot;[!UICONTROL schwarze Liste]&quot;wurden in den Unterlagen zum Adobe Campaign durch &quot;[!UICONTROL Zulassungsliste]&quot;und &quot;[!UICONTROL Blockierungsliste]&quot;ersetzt.
>Einige Vorkommen dieser Begriffe befinden sich möglicherweise noch in der Produktoberfläche, in Optionsnamen, im internen Code sowie in den Übungsvideos. Sie werden in den kommenden Control Paneln ersetzt.

Der [!UICONTROL Control Panel] ermöglicht es Adobe Campaign-Administratoren, wichtige Assets zu überwachen und administrative Aufgaben durchzuführen, z. B. die Verwaltung der SFTP-Datenspeicherung nach Instanz oder [!UICONTROL Zulassungsliste] -IP-Adressen.

## Accessing [!UICONTROL Control Panel]

Um auf den Control Panel zuzugreifen, gehen Sie zu Experience Cloud Home: [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud-Startseite]** > **[!UICONTROL Schnellzugriff]**

   oder
* **[!UICONTROL Experience Cloud-Startseite]** > [!UICONTROL Lösungsauswahl]: **Kampagne** > **[!UICONTROL Control Panel]-Karte **

   oder

* Direkt von der URL: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Voraussetzungen

Bevor Sie beginnen, müssen Sie die folgenden Voraussetzungen erfüllen:

### Bestätigen [!DNL IMS Org ID]

Du musst dein [!DNL IMS org ID]wissen. Im folgenden Video wird beschrieben, wo Sie die Instanz suchen können [!DNL IMS org ID].

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Prüfung[!DNL IMS Org ID](00:26 Min.)*

### Administratorrechte

Für den Zugriff auf den [!UICONTROL Control Panel]sind Administratorrechte erforderlich.
Im folgenden Video wird erläutert, wie Sie einer Instanz einer Kampagne einen Administrator hinzufügen

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Hinzufügen eines Administrators zum Profil &quot;[!UICONTROL Administratoren]&quot;zur Verwendung von[!UICONTROL Control Panel](01:03 Min.)*

## [!UICONTROL Control Panel] -Lernprogramme

* **Verwalten von SFTP-Servern**

   *Erfahren Sie, wie Sie die Serverkapazität und die[!UICONTROL Zulassungsliste]-IP-Adressen überwachen und SSH-Schlüssel hinzufügen können*

   * [Überwachen der Serverkapazität, Auflisten von IP-Adressen und Hinzufügen von SSH-Schlüsseln](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Erstellen eines SSH-Schlüssels](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Herstellen einer Verbindung mit einem SFTP-Server](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Subdomänen übertragen](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *Erfahren Sie, wie Sie eine Subdomäne vollständig an[!UICONTROL Adobe Campaign delegieren ]*

* **[SSL-Zertifikate hinzufügen](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Erfahren Sie, wie Sie SSL-Zertifikate hinzufügen können, um Ihre Subdomänen mit Control Panel zu sichern.*

* **[Verwalten von SSL-Zertifikaten](/help/acc/monitoring-campaign-classic/control-panel/managing-ssl-certificates.md)**

   *Erfahren Sie, wie Sie den Status der SSL-Zertifikate Ihrer Subdomänen sowie Erneuerungen anfordern können.*

* **[URL-Berechtigungen hinzufügen](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *wie Sie einige externe URLs zur Liste autorisierter URLs hinzufügen, damit Ihre Instanz eine Verbindung zu ihnen herstellen kann.*

* **[IP-Zulassungsauflistung für den Zugriff auf Instanzen](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Erfahren Sie, wie Sie neue Verbindungen zu Ihren Instanzen einrichten, indem Sie die Auflistung[!UICONTROL von IP-Adressbereichen]zulassen.*

* **[Verwaltung von Google TXT-Einträgen](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Erfahren Sie, wie Sie allen Subdomänen, die zum Senden von E-Mails an[!DNL Google TXT]Adressen über den[!DNL GMAIL]Kampagnen-Control Panelverwendet werden, einen Site-Überprüfungsdatensatz hinzufügen.*

* **GPG-Schlüsselverwaltung**

   *Erfahren Sie, wie Sie ein Public-Private-Key-Paar für die Verschlüsselung ausländischer Kampagnen auf einer angegebenen Instanz erstellen und installieren sowie einen öffentlichen Schlüssel für die Entschlüsselung eingehender Daten importieren und auf einer Kampagne installieren:*

   * [Generieren und Installieren von GPG-Schlüsseln für die Datenverschlüsselung](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Verschlüsseln von Daten mit einem GPG-Schlüssel](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Entschlüsseln von Daten](./gpg-key-management/decrypting-data.md)

* **[Fehlerbehebung im Bedienfeld](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *Fehlerbehebung beim[!UICONTROL Control Panel ]*

## Zusätzliche Ressourcen

* [Control Panel Help Center](https://docs.adobe.com/content/help/de-DE/control-panel/using/control-panel-home.html)
