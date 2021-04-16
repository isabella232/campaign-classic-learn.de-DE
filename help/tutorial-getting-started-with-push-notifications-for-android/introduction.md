---
title: Erste Schritte mit Push-Benachrichtigungen für Android – Einleitung
description: Dieses Tutorial führt Sie durch die Schritte, die für das Senden von Push-Benachrichtigungen von Adobe Campaign und den Empfang dieser Benachrichtigungen in Ihrer Android-App erforderlich sind.
feature: Push-Benachrichtigung
topics: mobile channels
kt: 6438
doc-type: article
activity: setup
team: TM
role: Administrator, Developer
level: Experienced
exl-id: 291c2e3a-c126-439d-9753-06a4091bbda0
translation-type: ht
source-git-commit: 298d3745a32d4509a82295be851f6e390f33749a
workflow-type: ht
source-wordcount: '366'
ht-degree: 100%

---

# Erste Schritte mit Push-Benachrichtigungen für Android – Einleitung

Sie können mit Adobe Campaign personalisierte und zielgruppenspezifische [!DNL push]-Benachrichtigungen an [!DNL iOS]- und [!DNL Android]-Mobilgeräte senden. Dieses Tutorial führt Sie durch die Schritte, die zum Senden von [!DNL push]-Benachrichtigungen von Adobe Campaign an eine [!DNL Android]-App erforderlich sind.

## Voraussetzungen

Bevor Sie beginnen können, benötigen Sie Folgendes:

1) **Android Mobile App**

   In diesem Tutorial werden nicht die zum Einrichten der Mobile App erforderlichen detaillierten Schritte behandelt. Sie benötigen eine **[!DNL Android]Mobile App mit integriertem [!DNL Campaign SDK]**.

   Eine ausführliche Beschreibung der erforderlichen Schritte finden Sie in der Produktdokumentation:

   [Integration des Campaign SDK in Mobile Apps](https://experienceleague.adobe.com/docs/campaign-classic/using/sending-messages/sending-push-notifications/integrating-campaign-sdk-into-the-mobile-application.html?lang=de)

   Sie können auch das Experience Platform Mobile SDK verwenden. Sehen Sie sich für weiterführende Informationen das folgende Tutorial-Video an:

   [Konfigurieren des Push-Kanals mit dem Experience Platform Mobile SDK](https://experienceleague.adobe.com/docs/campaign-classic-learn/tutorials/sending-messages/push-channel/configure-push-using-aep-mobile-sdk.html?lang=de)

2) **[!DNL Mobile App channel]Paket installiert**

   Das [!DNL Mobile App channel]-Paket muss in Ihrer [!DNL Campaign]-Instanz installiert sein. Im folgenden Video wird erläutert, wie Sie überprüfen können, ob [!DNL Mobile App channel] in Ihrer Instanz installiert ist, und wie Sie diese installieren können, falls dies nicht der Fall ist.

>[!VIDEO](https://video.tv.adobe.com/v/326544?quality=12)

## Tutorial-Übersicht

Wir möchten den Abonnenten der [!DNL Neotrip] [!DNL Android] Mobile App zu Werbezwecken eine personalisierte [!DNL push]-Benachrichtigung senden. Die [!DNL Neotrip]-App wird mit dem [!DNL Campaign SDK] konfiguriert und wir haben sichergestellt, dass die [!DNL Mobile App channel] in unserer [!DNL Campaign]-Instanz aktiviert ist.

Die folgenden Konfigurationsschritte sind erforderlich:

### Schritt 1: Erweitern des App-Abonnementschemas, um [!DNL push]-Benachrichtigungen zu personalisieren

Da wir die [!DNL push]-Benachrichtigung personalisieren möchten, erweitern wir zunächst [das Schema des App-Abonnements](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md), um die Personalisierungswerte zu speichern, die wir von der App erhalten, wenn der Benutzer den Dienst abonniert.

### Schritt 2: Konfigurieren des Android-Dienstes und Erstellen der Mobile App in Campaign

Als Nächstes müssen Sie den Android-Dienst [konfigurieren und die Mobile App in Campaign](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-an-android-service-in-campaign.md) erstellen. In diesem Schritt definieren wir die [!DNL Neotrip]-App als Ziel der Push-Benachrichtigung.

### Schritt 3: Konfigurieren und Senden der Push-Benachrichtigung

Dann können wir [die Push-Benachrichtigung konfigurieren und ](/help/tutorial-getting-started-with-push-notifications-for-android/configuring-and-sending-push-notifications.md) senden.

## Tutorial beginnen

Schritt 1: [Erweitern des App-Abonnementschemas](/help/tutorial-getting-started-with-push-notifications-for-android/extending-the-app-subscription-schema.md)
