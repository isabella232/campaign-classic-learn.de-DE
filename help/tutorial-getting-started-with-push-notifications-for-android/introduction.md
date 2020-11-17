---
title: Übung - Erste Schritte mit Push-Benachrichtigungen für Android - Einführung
description: Dieses Tutorial führt Sie durch die Schritte, die für das Senden von Push-Benachrichtigungen von Adobe Campaign und den Empfang dieser Benachrichtigungen in Ihrer Android-App erforderlich sind.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 217b0ec1b6f5c5e17009f1103d69726aa57dcaa4
workflow-type: tm+mt
source-wordcount: '389'
ht-degree: 6%

---


# Übung - Erste Schritte mit Push-Benachrichtigungen für Android - Einführung

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android ]mobile devices.

Dieses Lernprogramm führt Sie durch die Schritte, die beim Senden von [!DNL push] Benachrichtigungen von Adobe Campaign an eine [!DNL Android] App erforderlich sind.

## Voraussetzungen

Bevor Sie beginnen können, müssen Sie die folgenden Voraussetzungen erfüllen

1) MobilanwendungIn diesem Lernprogramm werden die zum Einrichten der Mobilanwendung erforderlichen detaillierten Schritte nicht behandelt. Sie benötigen eine **[!DNL Android]mobile Anwendung mit der[!DNL Campaign SDK]** integrierten.

   * Eine detaillierte Beschreibung der erforderlichen Schritte finden Sie im SDK für die [Integration von Kampagnen in die Mobilanwendung](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html).

   * Sie können auch das Experience Platform Mobile SDK verwenden. Weitere Informationen finden Sie im Video zum [Konfigurieren des Push-Kanals mithilfe des Experience Platform Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html) -Lernprogramms.

2) Installieren des Mobile App Kanal-Pakets

   Das Kanal-Paket für die mobile App muss auf Ihrer Instanz installiert sein. Im folgenden Video wird erläutert, wie Sie überprüfen können, ob der Mobile App Kanal auf Ihrer Instanz installiert ist, und, falls nicht, wie Sie ihn installieren.

   [!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Tutorial

Wir möchten den Abonnenten der Neotrip [!DNL Android] Mobile App eine personalisierte Push-Benachrichtigung senden. Die Neotrip-App ist mit dem Kampagne SDK konfiguriert und wir haben sichergestellt, dass der Mobile App Kanal in unserer Kampagne aktiviert ist.

Die folgenden Konfigurationsschritte sind erforderlich:

### Schritt 1: Erweitern des App Abonnement-Schemas, um Push-Benachrichtigungen zu personalisieren

Da wir die Push-Benachrichtigung personalisieren möchten, [erweitern wir zunächst das App-Abonnement-Schema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) , um die Personalisierungswerte zu speichern, die wir von der App erhalten, wenn der Benutzer den Dienst abonniert.

### Schritt 2: Konfigurieren des Android-Dienstes und Erstellen der mobilen App-Anwendung in Kampagne

Als Nächstes müssen wir den Android-Dienst [konfigurieren und die mobile App-Anwendung in Kampagne](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md)erstellen. In diesem Schritt definieren wir die Neotrip-App als Zielgruppe für die Push-Benachrichtigung.

### Schritt 3: Push-Benachrichtigung konfigurieren und senden

Dann können wir die Push-Benachrichtigung [konfigurieren und senden](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## Beginn des Lernprogramms

**[Schritt 1: Erweitern des App-Abonnement-Schemas](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)**
