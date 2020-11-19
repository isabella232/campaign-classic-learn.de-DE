---
title: Erste Schritte mit Push-Benachrichtigungen für Android - Einführung
description: Dieses Tutorial führt Sie durch die Schritte, die für das Senden von Push-Benachrichtigungen von Adobe Campaign und den Empfang dieser Benachrichtigungen in Ihrer Android-App erforderlich sind.
feature: push
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
translation-type: tm+mt
source-git-commit: 016f47e131df9c3a25b9131da372efaedf6cd5ad
workflow-type: tm+mt
source-wordcount: '365'
ht-degree: 8%

---


# Erste Schritte mit Push-Benachrichtigungen für Android - Einführung

Adobe Campaign allows you to send personalized and segmented [!DNL push] notifications to [!DNL iOS] and [!DNL Android] mobile devices. Dieses Lernprogramm führt Sie durch die Schritte, die beim Senden von [!DNL push] Benachrichtigungen von Adobe Campaign an eine [!DNL Android] App erforderlich sind.

## Voraussetzungen

Bevor Sie beginnen können, benötigen Sie Folgendes:

1) **Android Mobile-Anwendung**

   In diesem Lernprogramm werden die zum Einrichten der mobilen Anwendung erforderlichen detaillierten Schritte nicht behandelt. Sie benötigen eine **[!DNL Android]mobile Anwendung mit [!DNL Campaign SDK] integrierter**.

   Eine ausführliche Beschreibung der erforderlichen Schritte finden Sie in der Produktdokumentation:

   [Integration des Campaign SDK in Mobile Apps](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html)

   Sie können auch das Experience Platform Mobile SDK verwenden. Weitere Informationen finden Sie im Video zum Tutorial:

   [Konfigurieren des Push-Kanals mit dem Experience Platform Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html)

2) **[!DNL Mobile App channel]Paket installiert**

   Das [!DNL Mobile App channel] Paket muss auf Ihrer [!DNL Campaign] Instanz installiert sein. In dem folgenden Video wird erläutert, wie Sie überprüfen können, ob die Instanz auf Ihrem Computer installiert [!DNL Mobile App channel] ist, und falls nicht, wie Sie sie installieren.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Übungsübersicht

Wir möchten eine personalisierte [!DNL push] Benachrichtigung an die Abonnenten der [!DNL Neotrip] [!DNL Android] mobilen App senden. Die [!DNL Neotrip] App ist mit der konfiguriert [!DNL Campaign SDK] , und wir haben sichergestellt, dass die [!DNL Mobile App channel] App in unserer [!DNL Campaign] Instanz aktiviert ist.

Die folgenden Konfigurationsschritte sind erforderlich:

### Schritt 1: Erweitern des App Abonnement-Schemas, um [!DNL push] Benachrichtigungen zu personalisieren

Da wir die [!DNL push] Benachrichtigung personalisieren möchten, [erweitern wir zunächst das App-Abonnement-Schema](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md) , um die Personalisierungswerte zu speichern, die wir von der App erhalten, wenn der Benutzer den Dienst abonniert.

### Schritt 2: Konfigurieren des Android-Dienstes und Erstellen der Mobilanwendung in Kampagne

Als Nächstes müssen wir den Android-Dienst [konfigurieren und die Mobilanwendung in Kampagne](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md)erstellen. In diesem Schritt definieren wir die [!DNL Neotrip] App als Zielgruppe für die Push-Benachrichtigung.

### Schritt 3: Push-Benachrichtigung konfigurieren und senden

Dann können wir die Push-Benachrichtigung [konfigurieren und senden](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md).

## Beginn des Lernprogramms

Schritt 1: [Erweitern des App-Abonnement-Schemas](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
