---
title: Control Panel
seo-title: Control Panel
description: Über die Systemsteuerung können Sie Ihre SFTP-Datenspeicherung nach Instanz und Zulassungsliste-IP-Adressen überwachen und verwalten.
seo-description: Über die Systemsteuerung können Sie Ihre SFTP-Datenspeicherung nach Instanz und Zulassungsliste-IP-Adressen überwachen und verwalten.
feature: Control Panel
topics: Control Panel
kt: 3262
doc-type: feature video
activity: use
team: PM
translation-type: tm+mt
source-git-commit: ca3b7933927914b9965f6f059293041dd1db1da2
workflow-type: tm+mt
source-wordcount: '463'
ht-degree: 7%

---


# [!UICONTROL Control Panel]

>[!NOTE]
>
>Die Begriffe &quot;[!UICONTROL Whitelist]&quot;und &quot;[!UICONTROL schwarze Liste]&quot;wurden in den Unterlagen zum Adobe Campaign durch &quot;[!UICONTROL Zulassungsliste]&quot;und &quot;[!UICONTROL Blockierungsliste]&quot;ersetzt.
>Einige Vorkommen dieser Begriffe befinden sich möglicherweise noch in der Produktoberfläche, in Optionsnamen, im internen Code sowie in den Übungsvideos. Sie werden in den kommenden Versionen der Systemsteuerung ersetzt.

The [!UICONTROL Control Panel] allows Adobe Campaign administrators to monitor key assets and perform administrative tasks, such as managing the SFTP storage by instance or [!UICONTROL allow list] IP addresses.

## Accessing [!UICONTROL Control Panel]

To access the Control Panel go to Experience Cloud Home: [https://experiencecloud.adobe.com](https://experiencecloud.adobe.com):

* **[!UICONTROL Experience Cloud Home]** > **[!UICONTROL Quick Access]**

   oder
* **[!UICONTROL Experience Cloud Home]**  > [!UICONTROL Solution picker]: **Campaign** > **[!UICONTROL Control Panel]card **

   oder

* Directly from the URL: [https://experience.adobe.com/#/controlpanel](https://experience.adobe.com/#/controlpanel)

## Voraussetzungen

Before you get started, complete the following prerequisites:

### Bestätigen [!DNL IMS Org ID]

You need to know your [!DNL IMS org ID]. The following video describes where you can lookup your instance&#39;s [!DNL IMS org ID].

>[!VIDEO](https://video.tv.adobe.com/v/27183?quality=12)
*Check[!DNL IMS Org ID](00:26 min)*

### Administrator rights

Administrator rights are required to access to the [!UICONTROL Control Panel].
The following video explains how to add an administrator to a Campaign instance

>[!VIDEO](https://video.tv.adobe.com/v/27147?quality=12)
*Hinzufügen eines Administrators zum Profil &quot;[!UICONTROL Administratoren]&quot;zur Verwendung der[!UICONTROL Systemsteuerung](01:03 Min.)*

## [!UICONTROL Bedienfeldübungen]

* **Verwalten von SFTP-Servern**

   *Erfahren Sie, wie Sie die Serverkapazität und die[!UICONTROL Zulassungsliste]-IP-Adressen überwachen und SSH-Schlüssel hinzufügen können*

   * [Überwachen der Serverkapazität, Auflisten von IP-Adressen und Hinzufügen von SSH-Schlüsseln](/help/acc/monitoring-campaign-classic/control-panel/monitoring-server-capacity-allow-listing-adding-ssh-key.md)
   * [Erstellen eines SSH-Schlüssels](/help/acc/monitoring-campaign-classic/control-panel/generate-ssh-key.md)
   * [Herstellen einer Verbindung mit einem SFTP-Server](/help/acc/monitoring-campaign-classic/control-panel/connect-to-sftp-server.md)

* **[Subdomänen übertragen](/help/acc/monitoring-campaign-classic/control-panel/subdomain-delegation.md)**

   *Erfahren Sie, wie Sie eine Subdomäne vollständig an[!UICONTROL Adobe Campaign delegieren ]*

* **[SSL-Zertifikate hinzufügen](/help/acc/monitoring-campaign-classic/control-panel/adding-ssl-certificates.md)**

   *Learn how you can add a SSL certificates to secure your subdomains using Control Panel.*

* **[Adding URL permissions](/help/acc/monitoring-campaign-classic/control-panel/adding-url-permissions.md)**

   *wie Sie einige externe URLs zur Liste autorisierter URLs hinzufügen, damit Ihre Instanz eine Verbindung zu ihnen herstellen kann.*

* **[IP-Zulassungsauflistung für den Zugriff auf Instanzen](/help/acc/monitoring-campaign-classic/control-panel/ip-allow-listing.md)**

   *Learn how to set up new connections to your instances by[!UICONTROL allow listing]IP addresses ranges.*

* **[Verwaltung von Google TXT-Einträgen](/help/acc/monitoring-campaign-classic/control-panel/google-txt-record-management.md)**

   *Erfahren Sie, wie Sie allen Subdomänen, die zum Senden von E-Mails an[!DNL Google TXT]Adressen über die[!DNL GMAIL]Systemsteuerungverwendet werden, einen Site-Überprüfungsdatensatz hinzufügen.*

* **GPG-Schlüsselverwaltung**

   *Erfahren Sie, wie Sie ein Public-Private-Key-Paar für die Verschlüsselung ausländischer Kampagnen auf einer angegebenen Instanz erstellen und installieren sowie einen öffentlichen Schlüssel für die Entschlüsselung eingehender Daten importieren und auf einer Kampagne installieren:*

   * [Generieren und Installieren von GPG-Schlüsseln für die Datenverschlüsselung](./gpg-key-management/generating-and-installing-gpg-keys-for-data-encryption.md)
   * [Verschlüsseln von Daten mit einem GPG-Schlüssel](./gpg-key-management/using-a-gpg-key-to-encrypt-data.md)
   * [Entschlüsseln von Daten](./gpg-key-management/decrypting-data.md)

* **[Fehlerbehebung im Bedienfeld](/help/acc/monitoring-campaign-classic/control-panel/trouble-shooting.md)**

   *Informationen zur Fehlerbehebung in der[!UICONTROL Systemsteuerung ]*

## Zusätzliche Ressourcen

* [Hilfe-Center für Systemsteuerung](https://docs.adobe.com/content/help/de-DE/control-panel/using/control-panel-home.html)
